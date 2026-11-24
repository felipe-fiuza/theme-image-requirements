# Hero image-slot analysis at 1440px

Open `index.html` for the measured Table / Screenshots views. Both retain the theme and ratio filters when switching views. All section screenshots are embedded in this HTML, so previewing requires no separate image-file requests. The full-resolution JPEG originals from this run also live in `screenshots/`.

- `findings.md`: coverage, measured ratio distribution, full slot inventory.
- `rendered-1440.json` / `.csv`: measured outer-slot dimensions.
- `rendered/`: per-theme raw browser evidence, including wrapper styles and ancestor boxes.
- `hero-slots-1440.json` / `.csv`: source-only slot inventory used to identify wrappers. Its ratio preferences are not rendered measurements.
- `source-only.html`: preserved initial report.

Measurements use the local Storefront Renderer, the existing World checkout, a 1440 × 1000 CSS-pixel viewport, device scale factor 1, and reduced motion. Every section whose `data-section` contains `hero` is included, including secondary hero sections. Theme IDs distinguish variants with the same display name.

The measured ratio uses the wrapper's untransformed CSS border-box width/height. A few in-flow image elements directly define their grid slot without a separate sizing wrapper; for those, their CSS layout box defines the slot. Intrinsic image dimensions, zoom, and image scale are excluded. Pink overlays locate the slot; rotated cards use approximate visual bounding rectangles.

## Resume or reproduce

The existing Storefront Renderer must be running, as documented in `../Decisions on Harness/theme-gallery/README.md` in the parent ChatGPT directory. No remote Git operations are involved.

From the Prompt analysis workspace:

1. `node hero-slot-analysis/measure-rendered.mjs`
2. `python3 hero-slot-analysis/render-report.py`

The measurement script rebuilds the latest local source for each outstanding theme, loads it into the local preview shop, verifies the served theme and hero inventory, and saves measurements and section screenshots. It skips per-theme JSON records already marked successful. Delete only the relevant JSON records to remeasure changed themes. Do not reuse successful records across source revisions without verifying them.

The loader uses a persistent Ruby task and UTF-8 encoding, avoiding the old gallery launcher's encoding issue. The browser uses the renderer's development `walrus-no-cache-deep` option to avoid previous-theme cache responses. Theme source files are read-only; generated local builds, local preview-shop data, and local asset cache change during capture.

`build.py` recreates the initial source-only audit and overwrites `index.html`; run `render-report.py` afterwards to restore the measured report.
