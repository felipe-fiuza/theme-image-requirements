# Rendered hero image slots at 1440px

Measured 146/146 image slots in 110/110 hero-marked sections; 97/97 themes processed. Local revision `7aef0b0db4024e9b69b8643c3a35d7b2164113d0`.

Live local Storefront Renderer, latest local theme rebuilt before capture. Fresh browser context per theme. CSS viewport 1440×1000, device scale factor 1, reduced motion. Untransformed outer wrapper CSS border box; when no separate wrapper defines the slot, untransformed in-flow CSS layout box. Decorative card rotations do not change the reported slot aspect ratio. No intrinsic image sizes or image transforms used. Ratios are width/height. Distribution groups to two decimal places; exact fractional CSS pixels retained.

Every section with `hero` in `data-section` is included, including secondary hero sections and multi-image card groups. Repeated slots count individually; theme counts distinguish broad reuse from repetition within one theme.

## Most common measured outer-slot ratios

| Measured W:H, rounded to 0.01 | Slots | Themes | Sections |
|---|---:|---:|---:|
| 0.80:1 | 13 | 5 | 5 |
| 1.00:1 | 10 | 8 | 8 |
| 2.00:1 | 9 | 9 | 9 |
| 1.67:1 | 9 | 9 | 9 |
| 1.78:1 | 6 | 6 | 6 |
| 1.25:1 | 4 | 1 | 1 |
| 1.76:1 | 4 | 4 | 4 |
| 1.89:1 | 4 | 4 | 4 |
| 1.80:1 | 4 | 4 | 4 |
| 0.56:1 | 4 | 1 | 1 |
| 1.60:1 | 3 | 3 | 3 |
| 1.34:1 | 3 | 2 | 2 |
| 0.75:1 | 3 | 3 | 3 |
| 1.85:1 | 3 | 3 | 3 |
| 1.71:1 | 3 | 3 | 3 |
| 0.88:1 | 3 | 1 | 1 |
| 0.78:1 | 2 | 1 | 1 |
| 1.50:1 | 2 | 2 | 2 |
| 0.86:1 | 2 | 2 | 2 |
| 0.90:1 | 2 | 1 | 1 |
| 1.79:1 | 2 | 2 | 2 |
| 1.57:1 | 2 | 2 | 2 |
| 1.65:1 | 2 | 2 | 2 |
| 0.87:1 | 2 | 1 | 1 |
| 1.64:1 | 2 | 2 | 2 |
| 1.53:1 | 2 | 2 | 2 |
| 1.37:1 | 2 | 1 | 1 |
| 1.68:1 | 2 | 2 | 2 |
| 0.99:1 | 2 | 1 | 1 |
| 0.82:1 | 2 | 1 | 1 |
| 0.95:1 | 2 | 1 | 1 |
| 1.45:1 | 2 | 2 | 2 |
| 1.17:1 | 1 | 1 | 1 |
| 1.49:1 | 1 | 1 | 1 |
| 0.85:1 | 1 | 1 | 1 |
| 1.73:1 | 1 | 1 | 1 |
| 2.33:1 | 1 | 1 | 1 |
| 1.58:1 | 1 | 1 | 1 |
| 1.66:1 | 1 | 1 | 1 |
| 2.29:1 | 1 | 1 | 1 |
| 1.35:1 | 1 | 1 | 1 |
| 0.97:1 | 1 | 1 | 1 |
| 1.15:1 | 1 | 1 | 1 |
| 0.61:1 | 1 | 1 | 1 |
| 1.18:1 | 1 | 1 | 1 |
| 1.59:1 | 1 | 1 | 1 |
| 1.75:1 | 1 | 1 | 1 |
| 2.67:1 | 1 | 1 | 1 |
| 1.61:1 | 1 | 1 | 1 |
| 1.33:1 | 1 | 1 | 1 |
| 2.57:1 | 1 | 1 | 1 |
| 0.91:1 | 1 | 1 | 1 |
| 1.20:1 | 1 | 1 | 1 |
| 2.18:1 | 1 | 1 | 1 |
| 2.10:1 | 1 | 1 | 1 |
| 1.21:1 | 1 | 1 | 1 |
| 0.64:1 | 1 | 1 | 1 |
| 1.28:1 | 1 | 1 | 1 |
| 2.03:1 | 1 | 1 | 1 |
| 1.02:1 | 1 | 1 | 1 |
| 2.40:1 | 1 | 1 | 1 |

Measured range: 0.558:1 (Waveform / hero-mixed-type-strip) to 2.667:1 (Luminous Minimalism / hero-lowline). Width-to-height spread: 4.78×.

## Shape families

- Landscape: 76 slots (52.1%).
- Wide landscape: 17 slots (11.6%).
- Portrait: 39 slots (26.7%).
- Near square: 14 slots (9.6%).

Families use W/H thresholds: portrait <0.95; near square 0.95–1.05; landscape >1.05 and <1.90; wide landscape ≥1.90. These are report categories, not theme conventions.

## Image fit and placement

All 146 hero image elements declare object-cover in the source. Per-slot tags distinguish absolute image layers from in-flow images, show the active focal position at 1440px, and flag masks, scale/transform rules, and image boxes that differ from the outer slot. These are source-rule tags; the measured outer sizes remain separate.

The element tag (img versus a decorative CSS background) does not itself make a crop safe. Cover fills its own image box and may crop. Contain preserves the entire image in that box and may leave spare space. A shared slot component should expose fit mode and per-image focal point. Keep masks and deliberate zoom as explicit variants.

## Measurement details

Each row identifies the selected outer wrapper and its exact source classes. Browser-computed dimensions resolve the former layout-dependent slots at 1440px. They describe this content/font state at a 1000px-tall viewport; content changes or viewport-height sizing can change the result. Screenshots are fresh section captures, with slot outlines added only by the report viewer. Original saved screenshots are unchanged.

When an in-flow image directly occupies a grid slot with no separate clipping/sizing wrapper, its untransformed CSS layout box defines that slot. This is distinct from intrinsic asset dimensions.

Serene Sculpted Minimalism variant a78d0625 has no hero-marked section; its other variant is included. Lumina Botanica has a hero-marked section without an image slot. Both are included in theme coverage.

## Every measured slot

| Theme | Hero section | Slot | Outer size (CSS px) | Measured W:H | Screenshot |
|---|---|---|---|---|---|
| Aero Minimalism | `hero-wordmark-card` | `home.hero_wordmark_card.image_1_alt` | 960.00 × 822.84 | 1.1667:1 | [Section](screenshots/feed-aero-minimalism-34e6d992--hero-wordmark-card.jpg) |
| Runout | `hero-weighted-line` | `home.hero_weighted_line.image_1_alt` | 661.66 × 529.31 | 1.2500:1 | [Section](screenshots/feed-analog-obsession-d2fc1b43--hero-weighted-line.jpg) |
| Runout | `hero-weighted-line` | `home.hero_weighted_line.image_2_alt` | 661.66 × 529.31 | 1.2500:1 | [Section](screenshots/feed-analog-obsession-d2fc1b43--hero-weighted-line.jpg) |
| Runout | `hero-weighted-line` | `home.hero_weighted_line.image_3_alt` | 661.66 × 529.31 | 1.2500:1 | [Section](screenshots/feed-analog-obsession-d2fc1b43--hero-weighted-line.jpg) |
| Runout | `hero-weighted-line` | `home.hero_weighted_line.image_4_alt` | 661.66 × 529.31 | 1.2500:1 | [Section](screenshots/feed-analog-obsession-d2fc1b43--hero-weighted-line.jpg) |
| Après Refresh | `hero-studio-ledger` | `home.hero_studio_ledger.image_1_alt` | 1440.00 × 720.00 | 2.0000:1 | [Section](screenshots/feed-apres-refresh-58387694--hero-studio-ledger.jpg) |
| Atelier Alegre | `hero-corner-note` | `home.hero_corner_note.image_1_alt` | 1440.00 × 720.00 | 2.0000:1 | [Section](screenshots/feed-atelier-alegre-b54494bc--hero-corner-note.jpg) |
| Bake Central Pop Studio | `hero-quiet-portrait` | `home.hero_quiet_portrait.image_1_alt` | 1440.00 × 820.00 | 1.7561:1 | [Section](screenshots/feed-bake-central-pop-studio-c09d7458--hero-quiet-portrait.jpg) |
| Bold on Every Table | `hero-diptych-rail` | `home.hero_diptych_rail.image_1_alt` | 720.00 × 920.00 | 0.7826:1 | [Section](screenshots/feed-bold-on-every-table-4b87b962--hero-diptych-rail.jpg) |
| Bold on Every Table | `hero-diptych-rail` | `home.hero_diptych_rail.image_2_alt` | 720.00 × 920.00 | 0.7826:1 | [Section](screenshots/feed-bold-on-every-table-4b87b962--hero-diptych-rail.jpg) |
| Bold on Every Table | `hero-spotlight-top` | `home.hero_spotlight_top.image_1_alt` | 1440.00 × 760.00 | 1.8947:1 | [Section](screenshots/feed-bold-on-every-table-4b87b962--hero-spotlight-top.jpg) |
| Brew & Play | `hero-collab-lockup` | `home.hero_collab_lockup.image_1_alt` | 294.66 × 368.31 | 0.8000:1 | [Section](screenshots/feed-brew-play-f9e55d21--hero-collab-lockup.jpg) |
| Brew & Play | `hero-collab-lockup` | `home.hero_collab_lockup.image_2_alt` | 294.67 × 368.33 | 0.8000:1 | [Section](screenshots/feed-brew-play-f9e55d21--hero-collab-lockup.jpg) |
| Brew & Play | `hero-collab-lockup` | `home.hero_collab_lockup.image_3_alt` | 294.66 × 368.31 | 0.8000:1 | [Section](screenshots/feed-brew-play-f9e55d21--hero-collab-lockup.jpg) |
| Brew & Play | `hero-collab-lockup` | `home.hero_collab_lockup.image_4_alt` | 294.66 × 368.31 | 0.8000:1 | [Section](screenshots/feed-brew-play-f9e55d21--hero-collab-lockup.jpg) |
| Brew & Play | `hero-collab-lockup` | `home.hero_collab_lockup.image_5_alt` | 294.67 × 368.33 | 0.8000:1 | [Section](screenshots/feed-brew-play-f9e55d21--hero-collab-lockup.jpg) |
| Brew & Play | `hero-collection-intro` | `home.hero_collection_intro.image_1_alt` | 1396.00 × 698.00 | 2.0000:1 | [Section](screenshots/feed-brew-play-f9e55d21--hero-collection-intro.jpg) |
| Brew & Play | `hero-stacked-2` | `home.hero_stacked_2.image_1_alt` | 1440.00 × 967.84 | 1.4878:1 | [Section](screenshots/feed-brew-play-f9e55d21--hero-stacked-2.jpg) |
| Brew & Play | `hero-stacked-2` | `home.hero_stacked_2.image_2_alt` | 546.41 × 640.00 | 0.8538:1 | [Section](screenshots/feed-brew-play-f9e55d21--hero-stacked-2.jpg) |
| Canvas Bloom Studio | `hero-centered-display` | `home.hero.image_1_alt` | 1440.00 × 720.00 | 2.0000:1 | [Section](screenshots/feed-canvas-bloom-studio-58769c9d--hero-centered-display.jpg) |
| Cheerful Pop | `hero-triptych-labels` | `home.hero_triptych_labels.image_1_alt` | 192.00 × 192.00 | 1.0000:1 | [Section](screenshots/feed-cheerful-pop-ba54b077--hero-triptych-labels.jpg) |
| City Sanctuary | `hero-wordmark-reel` | `home.hero_wordmark_reel.image_1_alt` | 759.00 × 506.00 | 1.5000:1 | [Section](screenshots/feed-city-sanctuary-a3408300--hero-wordmark-reel.jpg) |
| Common Iron | `hero-full-bleed-1` | `home.hero_full_bleed_1.image_1_alt` | 1440.00 × 900.00 | 1.6000:1 | [Section](screenshots/feed-common-iron-c99e3f8d--hero-full-bleed-1.jpg) |
| Common Iron | `hero-full-bleed-1` | `home.hero_full_bleed_1.image_2_alt` | 96.00 × 96.00 | 1.0000:1 | [Section](screenshots/feed-common-iron-c99e3f8d--hero-full-bleed-1.jpg) |
| Concrete Pulse | `hero-collection-intro` | `home.hero_collection_intro.image_1_alt` | 1440.00 × 832.00 | 1.7308:1 | [Section](screenshots/feed-concrete-pulse-ca531534--hero-collection-intro.jpg) |
| Contemporary Heirlooms | `hero-full-bleed-1` | `home.hero_full_bleed_1.image_1_alt` | 1440.00 × 1072.00 | 1.3433:1 | [Section](screenshots/feed-contemporary-heirlooms-464aae1b--hero-full-bleed-1.jpg) |
| Contemporary Heirlooms | `hero-full-bleed-1` | `home.hero_full_bleed_1.image_2_alt` | 152.00 × 152.00 | 1.0000:1 | [Section](screenshots/feed-contemporary-heirlooms-464aae1b--hero-full-bleed-1.jpg) |
| Court Culture | `hero-still-life` | `home.hero_still_life.image_1_alt` | 1440.00 × 860.00 | 1.6744:1 | [Section](screenshots/feed-court-culture-cbcc330d--hero-still-life.jpg) |
| Creative Playground | `hero-overlap-1` | `home.hero_overlap_1.image_1_alt` | 1280.00 × 720.00 | 1.7778:1 | [Section](screenshots/feed-creative-playground-2a7e4846--hero-overlap-1.jpg) |
| Desk Objects in Motion | `hero-wordmark-reel` | `home.hero_wordmark_reel.image_1_alt` | 1344.00 × 576.00 | 2.3333:1 | [Section](screenshots/feed-desk-objects-in-motion-5a7b5319--hero-wordmark-reel.jpg) |
| Desk to Drinks | `hero-flatlay-eyebrow` | `home.hero_flatlay_eyebrow.image_1_alt` | 1440.00 × 912.00 | 1.5789:1 | [Section](screenshots/feed-desk-to-drinks-3492b0dc--hero-flatlay-eyebrow.jpg) |
| Desk to Drinks | `hero-paired-frames` | `home.hero_paired_frames.image_1_alt` | 721.33 × 841.55 | 0.8571:1 | [Section](screenshots/feed-desk-to-drinks-605d453a--hero-paired-frames.jpg) |
| Desk to Drinks | `hero-paired-frames` | `home.hero_paired_frames.image_2_alt` | 304.00 × 405.33 | 0.7500:1 | [Section](screenshots/feed-desk-to-drinks-605d453a--hero-paired-frames.jpg) |
| Driftline | `hero-panel-crossover` | `home.hero_panel_crossover.image_1_alt` | 1440.00 × 780.00 | 1.8462:1 | [Section](screenshots/feed-driftline-aac4d214--hero-panel-crossover.jpg) |
| Effortless Rituals | `hero-collab-lockup` | `home.hero_collab_lockup.image_1_alt` | 720.00 × 800.00 | 0.9000:1 | [Section](screenshots/feed-effortless-rituals-3899a311--hero-collab-lockup.jpg) |
| Effortless Rituals | `hero-collab-lockup` | `home.hero_collab_lockup.image_2_alt` | 720.00 × 800.00 | 0.9000:1 | [Section](screenshots/feed-effortless-rituals-3899a311--hero-collab-lockup.jpg) |
| Effortless Rituals | `hero-still-life` | `home.hero_still_life.image_1_alt` | 1440.00 × 820.00 | 1.7561:1 | [Section](screenshots/feed-effortless-rituals-3899a311--hero-still-life.jpg) |
| Effortless Rituals | `hero-studio-ledger` | `home.hero_studio_ledger.image_1_alt` | 1440.00 × 868.00 | 1.6590:1 | [Section](screenshots/feed-effortless-rituals-3899a311--hero-studio-ledger.jpg) |
| Electric Ember | `hero-forecast-type` | `home.hero_forecast_type.image_1_alt` | 1280.00 × 560.00 | 2.2857:1 | [Section](screenshots/feed-electric-ember-0489b72f--hero-forecast-type.jpg) |
| ERESU | `hero-statement-split` | `home.hero_statement_split.image_1_alt` | 720.00 × 900.00 | 0.8000:1 | [Section](screenshots/feed-eresu-6b7e93b2--hero-statement-split.jpg) |
| Everyday Elevated | `hero-stacked-2` | `home.hero_stacked_2.image_1_alt` | 840.00 × 620.00 | 1.3548:1 | [Section](screenshots/feed-everyday-elevated-3acc8cc4--hero-stacked-2.jpg) |
| Everyday Elevated | `hero-stacked-2` | `home.hero_stacked_2.image_2_alt` | 600.00 × 620.00 | 0.9677:1 | [Section](screenshots/feed-everyday-elevated-3acc8cc4--hero-stacked-2.jpg) |
| Everyday Luxe Editorial | `hero-stacked-1` | `home.hero_stacked_1.image_1_alt` | 1440.00 × 810.00 | 1.7778:1 | [Section](screenshots/feed-everyday-luxe-editorial-351eedcd--hero-stacked-1.jpg) |
| Feel-Good Fuel | `hero-stacked-1` | `home.hero_stacked_1.image_1_alt` | 1440.00 × 810.00 | 1.7778:1 | [Section](screenshots/feed-feel-good-fuel-e35eff31--hero-stacked-1.jpg) |
| Festive Table Stories | `hero-statement-split` | `home.hero_statement_split.image_1_alt` | 514.67 × 643.33 | 0.8000:1 | [Section](screenshots/feed-festive-table-stories-9d092267--hero-statement-split.jpg) |
| Frame Club | `hero-statement-split` | `home.hero_statement_split.image_1_alt` | 660.00 × 660.00 | 1.0000:1 | [Section](screenshots/feed-frame-club-b76f7d53--hero-statement-split.jpg) |
| Gathered at the Table | `hero-centered-display` | `home.hero_centered_display.image_1_alt` | 1440.00 × 778.38 | 1.8500:1 | [Section](screenshots/feed-gathered-at-the-table-0f227565--hero-centered-display.jpg) |
| Glim | `hero-weighted-line` | `home.hero_weighted_line.image_1_alt` | 1440.00 × 780.00 | 1.8462:1 | [Section](screenshots/feed-glim-1955fe62--hero-weighted-line.jpg) |
| Gold Accent Vitality | `hero-split-centered` | `home.hero_split_centered.image_1_alt` | 692.00 × 600.00 | 1.1533:1 | [Section](screenshots/feed-gold-accent-vitality-b6c45efa--hero-split-centered.jpg) |
| Golden Hour Heritage | `hero-stacked-2` | `home.hero_stacked_2.image_1_alt` | 675.98 × 901.33 | 0.7500:1 | [Section](screenshots/feed-golden-hour-heritage-cf0e8500--hero-stacked-2.jpg) |
| Golden Hour Heritage | `hero-stacked-2` | `home.hero_stacked_2.image_2_alt` | 720.00 × 1186.70 | 0.6067:1 | [Section](screenshots/feed-golden-hour-heritage-cf0e8500--hero-stacked-2.jpg) |
| Golden Interval | `hero-full-bleed-1` | `home.hero_full_bleed_1.image_1_alt` | 1440.00 × 800.00 | 1.8000:1 | [Section](screenshots/feed-golden-interval-616ba7c1--hero-full-bleed-1.jpg) |
| Saltglass Swim | `hero-contrast-words` | `home.hero_contrast_words.image_1_alt` | 1440.00 × 720.00 | 2.0000:1 | [Section](screenshots/feed-golden-tide-collective-cbe226a1--hero-contrast-words.jpg) |
| Haunted Hearth | `hero-offer-top` | `home.hero_offer_top.image_1_alt` | 1440.00 × 803.72 | 1.7917:1 | [Section](screenshots/feed-haunted-hearth-74841fa7--hero-offer-top.jpg) |
| Haven & Hearth | `hero-full-bleed-1` | `home.hero_full_bleed_1.image_1_alt` | 1440.00 × 760.00 | 1.8947:1 | [Section](screenshots/feed-haven-hearth-02c64983--hero-full-bleed-1.jpg) |
| Haven & Hearth | `hero-full-bleed-1` | `home.hero_full_bleed_1.image_2_alt` | 112.00 × 112.00 | 1.0000:1 | [Section](screenshots/feed-haven-hearth-02c64983--hero-full-bleed-1.jpg) |
| Haze & Co. | `hero-wordmark-card` | `home.hero_wordmark_card.image_1_alt` | 1440.00 × 919.00 | 1.5669:1 | [Section](screenshots/feed-haze-co-ddebc1c9--hero-wordmark-card.jpg) |
| Joyful Spectrum | `hero-panel-crossover` | `home.hero_panel_crossover.image_1_alt` | 904.00 × 768.00 | 1.1771:1 | [Section](screenshots/feed-joyful-spectrum-13c173a0--hero-panel-crossover.jpg) |
| Kumo | `hero-corner-note` | `home.hero_corner_note.image_1_alt` | 1440.00 × 904.00 | 1.5929:1 | [Section](screenshots/feed-kumo-9411624c--hero-corner-note.jpg) |
| Lacé | `hero-showcase-frame` | `home.hero_showcase_frame.image_1_alt` | 1440.00 × 822.84 | 1.7500:1 | [Section](screenshots/feed-lace-c6c3cf61--hero-showcase-frame.jpg) |
| Light as Art | `hero-centered-display` | `home.hero_centered_display.image_1_alt` | 1440.00 × 872.00 | 1.6514:1 | [Section](screenshots/feed-light-as-art-d46a8a34--hero-centered-display.jpg) |
| Lived-In Glow | `hero-offer-top` | `home.hero_offer_top.image_1_alt` | 1440.00 × 860.00 | 1.6744:1 | [Section](screenshots/feed-lived-in-glow-adf847a3--hero-offer-top.jpg) |
| Lumen Club | `hero-collab-lockup` | `home.hero_collab_lockup.image_1_alt` | 720.00 × 832.00 | 0.8654:1 | [Section](screenshots/feed-lumen-club-f6014c3f--hero-collab-lockup.jpg) |
| Lumen Club | `hero-collab-lockup` | `home.hero_collab_lockup.image_2_alt` | 720.00 × 832.00 | 0.8654:1 | [Section](screenshots/feed-lumen-club-f6014c3f--hero-collab-lockup.jpg) |
| Lumina Grain | `hero-twin-labels` | `home.hero_twin_labels.image_1_alt` | 720.00 × 720.00 | 1.0000:1 | [Section](screenshots/feed-lumina-grain-94e00c53--hero-twin-labels.jpg) |
| Lumina Grain | `hero-twin-labels` | `home.hero_twin_labels.image_2_alt` | 720.00 × 720.00 | 1.0000:1 | [Section](screenshots/feed-lumina-grain-94e00c53--hero-twin-labels.jpg) |
| Luminous Minimalism | `hero-lowline` | `home.hero_lowline.image_1_alt` | 1440.00 × 540.00 | 2.6667:1 | [Section](screenshots/feed-luminous-minimalism-07f12a93--hero-lowline.jpg) |
| Marée | `hero-quiet-portrait` | `home.hero_quiet_portrait.image_1_alt` | 1440.00 × 880.00 | 1.6364:1 | [Section](screenshots/feed-maree-fb912b0d--hero-quiet-portrait.jpg) |
| Modern Earth | `hero-corner-note` | `home.hero_corner_note.image_1_alt` | 1440.00 × 896.00 | 1.6071:1 | [Section](screenshots/feed-modern-earth-6969d979--hero-corner-note.jpg) |
| Modern Expedition | `hero-offer-top` | `home.hero_offer_top.image_1_alt` | 1440.00 × 900.00 | 1.6000:1 | [Section](screenshots/feed-modern-expedition-27be91a3--hero-offer-top.jpg) |
| Modern Muse | `hero-spotlight-top` | `home.hero_spotlight_top.image_1_alt` | 1440.00 × 820.00 | 1.7561:1 | [Section](screenshots/feed-modern-muse-22d857ed--hero-spotlight-top.jpg) |
| Modern Nest | `hero-still-life` | `home.hero_still_life.image_1_alt` | 1440.00 × 760.00 | 1.8947:1 | [Section](screenshots/feed-modern-nest-5d62c811--hero-still-life.jpg) |
| Modern Sanctuary | `hero-wordmark-card` | `home.hero_wordmark_card.image_1_alt` | 1440.00 × 940.00 | 1.5319:1 | [Section](screenshots/feed-modern-sanctuary-cdd9004a--hero-wordmark-card.jpg) |
| Monochrome Statement | `hero-quiet-portrait` | `home.hero_quiet_portrait.image_1_alt` | 1440.00 × 860.00 | 1.6744:1 | [Section](screenshots/feed-monochrome-statement-664fa55c--hero-quiet-portrait.jpg) |
| murmure | `hero-quiet-portrait` | `home.hero_quiet_portrait.image_1_alt` | 1440.00 × 872.00 | 1.6514:1 | [Section](screenshots/feed-murmure-6f516ba3--hero-quiet-portrait.jpg) |
| Neo-Japan Everyday | `hero-collection-intro` | `home.hero_collection_intro.image_1_alt` | 933.33 × 699.98 | 1.3334:1 | [Section](screenshots/feed-neo-japan-everyday-1beada46--hero-collection-intro.jpg) |
| Neo-Japan Everyday | `hero-collection-intro` | `home.hero_collection_intro.image_2_alt` | 458.66 × 341.98 | 1.3412:1 | [Section](screenshots/feed-neo-japan-everyday-1beada46--hero-collection-intro.jpg) |
| Neo-Japan Everyday | `hero-collection-intro` | `home.hero_collection_intro.image_3_alt` | 458.66 × 342.00 | 1.3411:1 | [Section](screenshots/feed-neo-japan-everyday-1beada46--hero-collection-intro.jpg) |
| Odile Grey | `hero-corner-note` | `home.hero_corner_note.image_1_alt` | 1440.00 × 860.00 | 1.6744:1 | [Section](screenshots/feed-odile-grey-5db868a6--hero-corner-note.jpg) |
| ORVENORIA | `hero-paired-frames` | `home.hero_paired_frames.image_1_alt` | 721.33 × 841.55 | 0.8571:1 | [Section](screenshots/feed-orvenoria-64caa630--hero-paired-frames.jpg) |
| ORVENORIA | `hero-paired-frames` | `home.hero_paired_frames.image_2_alt` | 304.00 × 405.33 | 0.7500:1 | [Section](screenshots/feed-orvenoria-64caa630--hero-paired-frames.jpg) |
| ORVENORIA | `hero-full-bleed-1` | `home.hero_full_bleed_1.image_1_alt` | 1440.00 × 760.00 | 1.8947:1 | [Section](screenshots/feed-orvenoria-af7d9e27--hero-full-bleed-1.jpg) |
| ORVENORIA | `hero-full-bleed-1` | `home.hero_full_bleed_1.image_2_alt` | 112.00 × 112.00 | 1.0000:1 | [Section](screenshots/feed-orvenoria-af7d9e27--hero-full-bleed-1.jpg) |
| Parallax | `hero-quiet-portrait` | `home.hero_quiet_portrait.image_1_alt` | 1440.00 × 840.00 | 1.7143:1 | [Section](screenshots/feed-parallax-32540ff0--hero-quiet-portrait.jpg) |
| pipkin | `hero-collab-lockup` | `home.hero_collab_lockup.image_1_alt` | 1440.00 × 560.00 | 2.5714:1 | [Section](screenshots/feed-pipkin-9a94d0f0--hero-collab-lockup.jpg) |
| Plain Stock | `hero-collab-lockup` | `home.hero_collab_lockup.image_1_alt` | 1440.00 × 1052.58 | 1.3681:1 | [Section](screenshots/feed-plain-stock-401de08f--hero-collab-lockup.jpg) |
| Plain Stock | `hero-collab-lockup` | `home.hero_collab_lockup.image_2_alt` | 1440.00 × 1052.58 | 1.3681:1 | [Section](screenshots/feed-plain-stock-401de08f--hero-collab-lockup.jpg) |
| Plain Stock | `hero-locker-display` | `home.hero_locker_display.image_1_alt` | 1440.00 × 840.00 | 1.7143:1 | [Section](screenshots/feed-plain-stock-401de08f--hero-locker-display.jpg) |
| Playful Function Atelier | `hero-panel-crossover` | `home.hero_panel_crossover.image_1_alt` | 840.00 × 920.00 | 0.9130:1 | [Section](screenshots/feed-playful-function-atelier-121b8a99--hero-panel-crossover.jpg) |
| Playful Green Utility | `hero-forecast-type` | `home.hero_forecast_type.image_1_alt` | 1440.00 × 856.00 | 1.6822:1 | [Section](screenshots/feed-playful-green-utility-ca58e492--hero-forecast-type.jpg) |
| Playful Green Utility | `hero-mixed-type-strip` | `home.hero_mixed_type_strip.image_1_alt` | 311.00 × 388.75 | 0.8000:1 | [Section](screenshots/feed-playful-green-utility-ca58e492--hero-mixed-type-strip.jpg) |
| Playful Green Utility | `hero-mixed-type-strip` | `home.hero_mixed_type_strip.image_2_alt` | 311.00 × 388.75 | 0.8000:1 | [Section](screenshots/feed-playful-green-utility-ca58e492--hero-mixed-type-strip.jpg) |
| Playful Green Utility | `hero-mixed-type-strip` | `home.hero_mixed_type_strip.image_3_alt` | 311.00 × 388.75 | 0.8000:1 | [Section](screenshots/feed-playful-green-utility-ca58e492--hero-mixed-type-strip.jpg) |
| Playful Green Utility | `hero-mixed-type-strip` | `home.hero_mixed_type_strip.image_4_alt` | 311.00 × 388.75 | 0.8000:1 | [Section](screenshots/feed-playful-green-utility-ca58e492--hero-mixed-type-strip.jpg) |
| Playful Green Utility | `hero-triptych-labels` | `home.hero_triptych_labels.image_1_alt` | 418.66 × 478.45 | 0.8750:1 | [Section](screenshots/feed-playful-green-utility-ca58e492--hero-triptych-labels.jpg) |
| Playful Green Utility | `hero-triptych-labels` | `home.hero_triptych_labels.image_2_alt` | 418.67 × 478.47 | 0.8750:1 | [Section](screenshots/feed-playful-green-utility-ca58e492--hero-triptych-labels.jpg) |
| Playful Green Utility | `hero-triptych-labels` | `home.hero_triptych_labels.image_3_alt` | 418.66 × 478.45 | 0.8750:1 | [Section](screenshots/feed-playful-green-utility-ca58e492--hero-triptych-labels.jpg) |
| Precision in Detail | `hero-crossing-line` | `home.hero_crossing_line.image_1_alt` | 875.00 × 583.33 | 1.5000:1 | [Section](screenshots/feed-precision-in-detail-b51839a8--hero-crossing-line.jpg) |
| Quiet Precision | `hero-centered-display` | `home.hero_centered_display.image_1_alt` | 1440.00 × 810.00 | 1.7778:1 | [Section](screenshots/feed-quiet-precision-cfbde3ce--hero-centered-display.jpg) |
| RadiantCurve Collective | `hero-centered-display` | `home.hero.image_1_alt` | 1440.00 × 720.00 | 2.0000:1 | [Section](screenshots/feed-radiantcurve-collective-2f845859--hero-centered-display.jpg) |
| Rally Club | `hero-framed-headline` | `home.hero_framed_headline.image_1_alt` | 1376.00 × 820.00 | 1.6780:1 | [Section](screenshots/feed-rally-club-0f8d8efd--hero-framed-headline.jpg) |
| Reckless Table | `hero-forecast-type` | `home.hero_forecast_type.image_1_alt` | 1440.00 × 800.00 | 1.8000:1 | [Section](screenshots/feed-reckless-table-e9821c4f--hero-forecast-type.jpg) |
| Ricrac | `hero-centered-display` | `home.hero_centered_display.image_1_alt` | 1440.00 × 860.00 | 1.6744:1 | [Section](screenshots/feed-ricrac-4ecc6a74--hero-centered-display.jpg) |
| rillen.berlin | `hero-split-centered` | `home.hero_split_centered.image_1_alt` | 1008.00 × 840.00 | 1.2000:1 | [Section](screenshots/feed-rillen-berlin-e3fea2a2--hero-split-centered.jpg) |
| rillen.berlin | `hero-twin-labels` | `home.hero_twin_labels.image_1_alt` | 714.00 × 720.00 | 0.9917:1 | [Section](screenshots/feed-rillen-berlin-e3fea2a2--hero-twin-labels.jpg) |
| rillen.berlin | `hero-twin-labels` | `home.hero_twin_labels.image_2_alt` | 714.00 × 720.00 | 0.9917:1 | [Section](screenshots/feed-rillen-berlin-e3fea2a2--hero-twin-labels.jpg) |
| Ruelle | `hero-opposite-corners` | `home.hero_opposite_corners.image_1_alt` | 1440.00 × 940.00 | 1.5319:1 | [Section](screenshots/feed-ruelle-38248a43--hero-opposite-corners.jpg) |
| Ruelle | `hero-twin-labels` | `home.hero_twin_labels.image_1_alt` | 720.00 × 880.00 | 0.8182:1 | [Section](screenshots/feed-ruelle-38248a43--hero-twin-labels.jpg) |
| Ruelle | `hero-twin-labels` | `home.hero_twin_labels.image_2_alt` | 720.00 × 880.00 | 0.8182:1 | [Section](screenshots/feed-ruelle-38248a43--hero-twin-labels.jpg) |
| Sable Sanctuary | `hero-stacked-2` | `home.hero_stacked_2.image_1_alt` | 1440.00 × 660.00 | 2.1818:1 | [Section](screenshots/feed-sable-sanctuary-cbcb73c3--hero-stacked-2.jpg) |
| Saikhu | `hero-wordmark-reel` | `home.hero_wordmark_reel.image_1_alt` | 573.33 × 322.48 | 1.7778:1 | [Section](screenshots/feed-saikhu-f3c811df--hero-wordmark-reel.jpg) |
| Second Pour | `hero-crossing-line` | `home.hero_crossing_line.image_1_alt` | 1033.33 × 492.05 | 2.1001:1 | [Section](screenshots/feed-second-pour-fed58ee8--hero-crossing-line.jpg) |
| Serene Sculpted Minimalism | `hero-opposite-corners` | `home.hero_opposite_corners.image_1_alt` | 1440.00 × 900.00 | 1.6000:1 | [Section](screenshots/feed-serene-sculpted-minimalism-dd6e696a--hero-opposite-corners.jpg) |
| Signed & Amplified | `hero-weighted-line` | `home.hero_weighted_line.image_1_alt` | 1440.00 × 860.00 | 1.6744:1 | [Section](screenshots/feed-signed-amplified-dfc34130--hero-weighted-line.jpg) |
| Situ | `hero-lowline` | `home.hero_lowline.image_1_alt` | 1440.00 × 720.00 | 2.0000:1 | [Section](screenshots/feed-situ-9827b0dc--hero-lowline.jpg) |
| Solé Swim | `hero-opposite-corners` | `home.hero_opposite_corners.image_1_alt` | 1440.00 × 1189.59 | 1.2105:1 | [Section](screenshots/feed-sole-swim-a30204f5--hero-opposite-corners.jpg) |
| Solé Swim | `hero-statement-split` | `home.hero_statement_split.image_1_alt` | 1440.00 × 820.00 | 1.7561:1 | [Section](screenshots/feed-sole-swim-a30204f5--hero-statement-split.jpg) |
| Sonic Haven | `hero-spotlight-top` | `home.hero_spotlight_top.image_1_alt` | 1440.00 × 840.00 | 1.7143:1 | [Section](screenshots/feed-sonic-haven-823fbd22--hero-spotlight-top.jpg) |
| Sonic Haven | `hero-diptych-rail` | `home.hero_diptych_rail.image_1_alt` | 461.33 × 720.00 | 0.6407:1 | [Section](screenshots/feed-sonic-haven-bdf1cbb5--hero-diptych-rail.jpg) |
| Sonic Haven | `hero-diptych-rail` | `home.hero_diptych_rail.image_2_alt` | 922.67 × 720.00 | 1.2815:1 | [Section](screenshots/feed-sonic-haven-bdf1cbb5--hero-diptych-rail.jpg) |
| Sotto | `hero-framed-headline` | `home.hero_framed_headline.image_1_alt` | 1440.00 × 860.00 | 1.6744:1 | [Section](screenshots/feed-sotto-7453b325--hero-framed-headline.jpg) |
| Sotto | `hero-twin-labels` | `home.hero_twin_labels.image_1_alt` | 720.00 × 760.00 | 0.9474:1 | [Section](screenshots/feed-sotto-7453b325--hero-twin-labels.jpg) |
| Sotto | `hero-twin-labels` | `home.hero_twin_labels.image_2_alt` | 720.00 × 760.00 | 0.9474:1 | [Section](screenshots/feed-sotto-7453b325--hero-twin-labels.jpg) |
| Sotto | `hero-weighted-line` | `home.hero_weighted_line.image_1_alt` | 1440.00 × 920.00 | 1.5652:1 | [Section](screenshots/feed-sotto-7453b325--hero-weighted-line.jpg) |
| Sourdine | `hero-opposite-corners` | `home.hero_opposite_corners.image_1_alt` | 1440.00 × 800.00 | 1.8000:1 | [Section](screenshots/feed-sourdine-485bbec8--hero-opposite-corners.jpg) |
| Studio Stillness | `hero-paired-frames` | `home.hero_paired_frames.image_1_alt` | 684.00 × 855.00 | 0.8000:1 | [Section](screenshots/feed-studio-stillness-36ce88e0--hero-paired-frames.jpg) |
| Studio Stillness | `hero-paired-frames` | `home.hero_paired_frames.image_2_alt` | 684.00 × 855.00 | 0.8000:1 | [Section](screenshots/feed-studio-stillness-36ce88e0--hero-paired-frames.jpg) |
| Sunlit Craft | `hero-staggered-serif` | `home.hero_staggered_serif.image_1_alt` | 1440.00 × 708.44 | 2.0326:1 | [Section](screenshots/feed-sunlit-craft-013f7a6e--hero-staggered-serif.jpg) |
| The Archivist’s Atelier | `hero-centered-display` | `home.hero_centered_display.image_1_alt` | 1440.00 × 880.00 | 1.6364:1 | [Section](screenshots/feed-the-archivist-s-atelier-3c245f74--hero-centered-display.jpg) |
| The Rehearsal Room | `hero-corner-note` | `home.hero_corner_note.image_1_alt` | 1440.00 × 860.00 | 1.6744:1 | [Section](screenshots/feed-the-rehearsal-room-ac54d970--hero-corner-note.jpg) |
| The Scented Atelier | `hero-split-centered` | `home.hero_split_centered.image_1_alt` | 806.39 × 790.58 | 1.0200:1 | [Section](screenshots/feed-the-scented-atelier-a895c870--hero-split-centered.jpg) |
| Trail Stories: In Motion | `hero-lowline` | `home.hero_lowline.image_1_alt` | 1440.00 × 600.00 | 2.4000:1 | [Section](screenshots/feed-trail-stories-in-motion-90190a52--hero-lowline.jpg) |
| Urban Phantom | `hero-diptych-rail` | `home.hero_diptych_rail.image_1_alt` | 720.00 × 720.00 | 1.0000:1 | [Section](screenshots/feed-urban-phantom-709c8612--hero-diptych-rail.jpg) |
| Urban Phantom | `hero-diptych-rail` | `home.hero_diptych_rail.image_2_alt` | 720.00 × 720.00 | 1.0000:1 | [Section](screenshots/feed-urban-phantom-709c8612--hero-diptych-rail.jpg) |
| Urban Phantom | `hero-locker-display` | `home.hero_locker_display.image_1_alt` | 1440.00 × 992.00 | 1.4516:1 | [Section](screenshots/feed-urban-phantom-709c8612--hero-locker-display.jpg) |
| Vintage Birdy | `hero-overlap-1` | `home.hero_overlap_1.image_1_alt` | 1280.00 × 720.00 | 1.7778:1 | [Section](screenshots/feed-vintage-birdy-e5914231--hero-overlap-1.jpg) |
| Waveform | `hero-mixed-type-strip` | `home.hero_mixed_type_strip.image_1_alt` | 332.50 × 595.72 | 0.5581:1 | [Section](screenshots/feed-waveform-3d17fa10--hero-mixed-type-strip.jpg) |
| Waveform | `hero-mixed-type-strip` | `home.hero_mixed_type_strip.image_2_alt` | 332.50 × 595.72 | 0.5581:1 | [Section](screenshots/feed-waveform-3d17fa10--hero-mixed-type-strip.jpg) |
| Waveform | `hero-mixed-type-strip` | `home.hero_mixed_type_strip.image_3_alt` | 332.50 × 595.72 | 0.5581:1 | [Section](screenshots/feed-waveform-3d17fa10--hero-mixed-type-strip.jpg) |
| Waveform | `hero-mixed-type-strip` | `home.hero_mixed_type_strip.image_4_alt` | 332.50 × 595.72 | 0.5581:1 | [Section](screenshots/feed-waveform-3d17fa10--hero-mixed-type-strip.jpg) |
| Waymark Supply Co. | `hero-quiet-portrait` | `home.hero_quiet_portrait.image_1_alt` | 1440.00 × 800.00 | 1.8000:1 | [Section](screenshots/feed-waymark-supply-co-20f6199d--hero-quiet-portrait.jpg) |
| Wingtip Coffee Co. | `hero-product-callout` | `home.hero_product_callout.image_1_alt` | 1440.00 × 806.39 | 1.7857:1 | [Section](screenshots/feed-wingtip-coffee-co-5fd54365--hero-product-callout.jpg) |
| Wonderworks Studio | `hero-crossing-line` | `home.hero_crossing_line.image_1_alt` | 769.34 × 528.92 | 1.4546:1 | [Section](screenshots/feed-wonderworks-studio-ad24704d--hero-crossing-line.jpg) |
| Work/Life Curated | `hero-forecast-type` | `home.hero_forecast_type.image_1_alt` | 1440.00 × 860.00 | 1.6744:1 | [Section](screenshots/feed-work-life-curated-d6bf2fc9--hero-forecast-type.jpg) |
| Woven Journeys | `hero-showcase-frame` | `home.hero_showcase_frame.image_1_alt` | 1200.00 × 600.00 | 2.0000:1 | [Section](screenshots/feed-woven-journeys-9bb09915--hero-showcase-frame.jpg) |
| Zenith Motion | `hero-locker-display` | `home.hero_locker_display.image_1_alt` | 1440.00 × 720.00 | 2.0000:1 | [Section](screenshots/feed-zenith-motion-bb81c54d--hero-locker-display.jpg) |
