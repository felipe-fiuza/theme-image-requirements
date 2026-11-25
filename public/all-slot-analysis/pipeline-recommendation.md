# Image pipeline recommendation and utilization

## Choose the image format for the slot

Use the slot’s width divided by its height to select the closest source format. These four rules minimize the image area hidden by `object-fit: cover`.

| Slot ratio (width ÷ height) | Recommended image format |
|---|---|
| Below 0.89 | **4:5** |
| 0.89 to below 1.15 | **1:1** |
| 1.15 to 1.54 | **4:3** |
| Above 1.54 | **16:9** |

These boundaries are rounded for readability; the placement lab calculates the closest format using exact ratios. Center images by default and adjust the focal position when needed. The original image file stays unchanged. **21:9 is an optional theme-specific top-up for especially wide slots**, rather than part of the four-format starting pool.

## Two recommended pipeline options

| Format | Balanced approach | Global approach |
|---|---:|---:|
| **4:5** | **5** | **9** |
| **16:9** | **4** | **8** |
| **4:3** | **4** | **11** |
| **1:1** | **3** | **7** |
| **Total generated** | **16 images** | **35 images** |

### Balanced approach — 16 images, then top up

**Recommended default when additional generation is available after theme selection.**

Generate 5 portrait (4:5), 4 wide landscape (16:9), 4 landscape (4:3), and 3 square (1:1) images. Reserve one image per format as a spare. The remaining 12-image inventory fills 78 of the 97 current themes (80.4%) without repeating images within a page. The other 19 themes need format-specific top-ups to fill their slots while retaining those reserves.

This limits upfront generation and offers selection flexibility. It does not cover every theme with spares upfront.

### Global approach — 35 images upfront

**Recommended when one shared library must support every current theme without additional generation for quantity or ratio requirements.**

Generate 9 portrait (4:5), 8 wide landscape (16:9), 11 landscape (4:3), and 7 square (1:1) images. This covers each format's maximum demand across the current themes, plus two spare images per format, assuming images are interchangeable across themes.

Treat this as a reusable library across pages, not a batch to regenerate for each page. Current pages use only 1–11 non-product images; an equally weighted average page uses 4.34. Much of the library will remain unused on any single page.

### Current production versus proposed pools

| Format / scope | Current production | Balanced approach | Global approach |
|---|---:|---:|---:|
| 4:5 — products | 28 | Excluded | Excluded |
| 4:5 — other images | 8 (1 hero, 4 editorials, 3 collections) | 5 | 9 |
| 16:9 | 10 | 4 | 8 |
| 21:9 | 5 | 0 | 0 |
| 1:1 | 3 | 3 | 7 |
| 4:3 | 3 | 4 | 11 |
| 2:3 | 3 | 0 | 0 |
| **Non-product subtotal** | **32** | **16** | **35** |
| **Total including 28 product images¹** | **60** | **44** | **63** |

¹ Comparison assumes the current 28 product images remain unchanged. The proposed pools cover non-product imagery only. Current production quantities and the 4:5 usage breakdown are user-provided; the remaining current formats are counted as non-product images for this comparison. A zero means that format is not generated separately in the proposed pool; its slots use the closest of the four proposed formats.

Both recommendations concern image quantities and closest source ratios at 1440px. They do not guarantee subject suitability, acceptable cropping, or coverage of future or mobile layouts.

## Analysis scope

Based on the current 97 themes at a 1440 × 1000 CSS-pixel viewport. Includes hero and other audited non-product image slots. Products are excluded. There are 421 visible slots; three additional source slots are hidden at this viewport.

## Assumptions

- Images can be reused across themes.
- Each visible slot gets a distinct image within a page.
- Each slot is assigned the closest of 16:9, 4:3, 4:5, and 1:1, minimizing image area hidden by `object-fit: cover`.
- Counts describe the current rendered content. They do not guarantee future theme or mobile requirements.
- An unused image on one page may still be useful elsewhere in a shared library.

## Universal image pool

| Format | Assigned slots across all themes | Share of slots | Highest demand in one theme | Spare images | Recommended pool |
|---|---:|---:|---:|---:|---:|
| 16:9 | 130 | 30.9% | 6 | 2 | 8 |
| 4:3 | 72 | 17.1% | 9 | 2 | 11 |
| 4:5 | 158 | 37.5% | 7 | 2 | 9 |
| 1:1 | 61 | 14.5% | 5 | 2 | 7 |
| **Total** | **421** | **100%** | **27 summed format maxima** | **8** | **35** |

The per-format maximum determines how many images are needed to fill any current theme without repetition. Adding two spare images per format creates a modest selection buffer. The summed maxima come from different themes: no single current theme needs 27 or 35 images.

Overall frequency suggests prioritizing 4:5 and then 16:9 when expanding the library. Together these formats serve approximately 68% of assigned slots.

## Estimated unused production per page

| Scenario | Images used | Unused from a 35-image batch | Unused share |
|---|---:|---:|---:|
| Average theme | 4.34 | 30.66 | 87.6% |
| Typical theme (median) | 4 | 31 | 88.6% |
| Most image-heavy theme | 11 | 24 | 68.6% |

The average weights each of the 97 themes equally. It is not weighted by actual theme selection or page traffic. All current themes use between 1 and 11 audited visible non-product image slots.

These percentages measure images unused on a single page. They do not estimate how many images will never be used across a shared library: that depends on theme selection, image selection, and reuse across pages.

## Recommendation

**If the theme is selected before generation:** generate its exact per-format requirements, then add a small selection buffer. Avoid generating the entire 35-image pool for every individual page.

**If the theme is unknown, or images form a shared reusable library:** use the 35-image pool as a conservative starting inventory that covers the current per-format maxima plus two spares each. Treat it as library capacity rather than expected page consumption.

The most effective way to reduce unused production is to select the theme before generating images, or generate additional formats and quantities on demand.

## Balanced starting pool and spares

For a smaller reusable starting pool, generate **12 images**, then top up the formats required by the selected theme.

| Format | Balanced starting pool | With one reserved spare per format |
|---|---:|---:|
| 4:5 | 4 | 5 |
| 16:9 | 3 | 4 |
| 4:3 | 3 | 4 |
| 1:1 | 2 | 3 |
| **Total** | **12** | **16** |

The 12-image pool fully supplies **78 of 97 current themes (80.4%)**, assigning each slot its closest format and using a distinct image per slot. The remaining 19 themes require format-specific top-ups. This coverage weights all themes equally; it does not predict actual theme selection frequency.

The 12 images offer selection flexibility above average page consumption, but **do not guarantee any spare images per format**. Some covered themes consume all available images in a format.

The **16-image option reserves one spare per format** while preserving coverage of those same 78 themes: its usable inventory after reserving the spares equals the 12-image pool. It does not guarantee that every current theme can be filled while retaining those spares. Generate theme-specific top-ups when necessary.

**Balanced recommendation:** start with 12 images if on-demand top-ups are available; start with 16 if keeping one spare per format is a requirement. Use the 35-image universal pool only when covering every current theme with two spares per format upfront is necessary.

## High-consumption themes

Using six or more images of a single format as a practical high-consumption threshold, nine themes qualify:

| Theme | Format | Images required |
|---|---|---:|
| Gold Accent Vitality | 4:3 | 9 |
| Playful Green Utility | 4:5 | 7 |
| Zenith Motion | 4:5 | 7 |
| Bake Central Pop Studio | 4:5 | 6 |
| Brew & Play | 4:5 | 6 |
| Common Iron | 4:5 | 6 |
| Lumen Club | 4:5 | 6 |
| Plain Stock | 4:5 | 6 |
| Woven Journeys | 16:9 | 6 |

Gold Accent Vitality is the strongest inventory outlier: its nine assigned 4:3 slots compare with five in the next-highest theme. High 4:5 consumption is more widespread.

## Proportion limitations

Seventeen slots across 13 themes hide more than 25% of the closest available image format's area when using `cover`. Six are unusually tall and eleven unusually wide. The browser hides the overflow; the original image file remains unchanged.

More images at the same four ratios do not reduce this geometric loss. These slots may need suitable image composition, focal positioning, another source ratio, or revised slot proportions.

## Supporting data

- [Per-theme format requirements and recommendation](pipeline-image-requirements.json)
- [Combined measured slots](rendered-1440.json)
- [Per-theme slot counts](theme-slot-counts.csv)
- [Interactive report](../general.html)

## Separate product-image findings

Product image slots have their own audit and recommendation. See [Product image slots — findings and recommendation](../product-slot-analysis/product-ratio-findings.md) for the 420-slot analysis, 4:5 versus 9:16 comparison, and 33 tall-slot flags across nine themes. Product quantities remain excluded from the non-product pools above.
