# Rendered product image slots at 1440px

Measured 420/420 eligible image slots in 149/149 image sections; 97/97 themes processed. Local revision `7aef0b0db4024e9b69b8643c3a35d7b2164113d0`.

Live local Storefront Renderer, latest local theme rebuilt before capture. Fresh browser context per theme. CSS viewport 1440×1000, device scale factor 1, reduced motion. Untransformed outer wrapper CSS border box; when no separate wrapper defines the slot, untransformed in-flow CSS layout box. Decorative card rotations do not change the reported slot aspect ratio. No intrinsic image sizes or image transforms used. Ratios are width/height. Distribution groups to two decimal places; exact fractional CSS pixels retained.

This audit includes only image slots explicitly linked to product records in template metadata. Editorial, brand, category, lifestyle and decorative images without a product metadata link are excluded. Repeated slots count individually; theme counts distinguish broad reuse from repetition within one theme.

## Most common measured outer-slot ratios

| Measured W:H, rounded to 0.01 | Slots | Themes | Sections |
|---|---:|---:|---:|
| 0.80:1 | 184 | 49 | 61 |
| 0.75:1 | 97 | 26 | 31 |
| 0.67:1 | 42 | 11 | 13 |
| 1.00:1 | 27 | 6 | 9 |
| 0.60:1 | 20 | 5 | 6 |
| 0.56:1 | 11 | 3 | 3 |
| 0.83:1 | 7 | 3 | 3 |
| 1.06:1 | 4 | 1 | 1 |
| 1.33:1 | 3 | 3 | 3 |
| 0.78:1 | 2 | 1 | 1 |
| 1.25:1 | 2 | 2 | 2 |
| 0.72:1 | 2 | 1 | 1 |
| 0.58:1 | 2 | 1 | 1 |
| 1.94:1 | 2 | 2 | 2 |
| 0.94:1 | 1 | 1 | 1 |
| 1.83:1 | 1 | 1 | 1 |
| 1.80:1 | 1 | 1 | 1 |
| 1.78:1 | 1 | 1 | 1 |
| 0.70:1 | 1 | 1 | 1 |
| 1.20:1 | 1 | 1 | 1 |
| 1.42:1 | 1 | 1 | 1 |
| 1.44:1 | 1 | 1 | 1 |
| 1.50:1 | 1 | 1 | 1 |
| 2.12:1 | 1 | 1 | 1 |
| 1.67:1 | 1 | 1 | 1 |
| 2.03:1 | 1 | 1 | 1 |
| 1.60:1 | 1 | 1 | 1 |
| 1.02:1 | 1 | 1 | 1 |
| 2.10:1 | 1 | 1 | 1 |

Measured range: 0.556:1 (Solé Swim / commerce-product-index) to 2.118:1 (Situ / product-campaign-banner). Width-to-height spread: 3.81×.

## Shape families

- Portrait: 369 slots (87.9%).
- Landscape: 18 slots (4.3%).
- Near square: 28 slots (6.7%).
- Wide landscape: 5 slots (1.2%).

Families use W/H thresholds: portrait <0.95; near square 0.95–1.05; landscape >1.05 and <1.90; wide landscape ≥1.90. These are report categories, not theme conventions.

## Image fit and placement

Current browser-computed fit modes are tagged for every measured image. Per-slot tags distinguish absolute image layers from in-flow images, show the active focal position at 1440px, and flag masks, scale/transform rules, and image boxes that differ from the outer slot. Fit and focal position come from browser-computed CSS; positioning and special-effect flags also reference the source rules. The measured outer sizes remain separate.

The element tag (img versus a decorative CSS background) does not itself make a crop safe. Cover fills its own image box and may crop. Contain preserves the entire image in that box and may leave spare space. A shared slot component should expose fit mode and per-image focal point. Keep masks and deliberate zoom as explicit variants.

## Measurement details

Each row identifies the selected outer wrapper and its exact source classes. Browser-computed dimensions resolve the former layout-dependent slots at 1440px. They describe this content/font state at a 1000px-tall viewport; content changes or viewport-height sizing can change the result. Screenshots are fresh section captures, with slot outlines added only by the report viewer. Original saved screenshots are unchanged.

When an in-flow image directly occupies a grid slot with no separate clipping/sizing wrapper, its untransformed CSS layout box defines that slot. This is distinct from intrinsic asset dimensions.

All 97 themes are included in the count table, including themes with zero eligible slots. Only image slots explicitly linked to product records in template metadata are included; the complete exclusion inventory is saved in section-slots-1440.json. Images inside product-selling sections that lack an explicit product metadata link are outside this audit, so these counts should not be interpreted as every image in a commerce section.

## Every measured slot

| Theme | Image section | Slot | Outer size (CSS px) | Measured W:H | Screenshot |
|---|---|---|---|---|---|
| Aero Minimalism | `commerce-product-row` | `home.commerce_product_row.image_1_alt` | 373.33 × 497.77 | 0.7500:1 | [Section](screenshots/feed-aero-minimalism-34e6d992--commerce-product-row.jpg) |
| Aero Minimalism | `commerce-product-row` | `home.commerce_product_row.image_2_alt` | 373.33 × 497.77 | 0.7500:1 | [Section](screenshots/feed-aero-minimalism-34e6d992--commerce-product-row.jpg) |
| Aero Minimalism | `commerce-product-row` | `home.commerce_product_row.image_3_alt` | 373.34 × 497.78 | 0.7500:1 | [Section](screenshots/feed-aero-minimalism-34e6d992--commerce-product-row.jpg) |
| Runout | `product-split-1` | `home.product_split_1.image_1_alt` | 282.00 × 376.00 | 0.7500:1 | [Section](screenshots/feed-analog-obsession-d2fc1b43--product-split-1.jpg) |
| Runout | `product-split-1` | `home.product_split_1.image_2_alt` | 282.00 × 376.00 | 0.7500:1 | [Section](screenshots/feed-analog-obsession-d2fc1b43--product-split-1.jpg) |
| Runout | `product-split-1` | `home.product_split_1.image_3_alt` | 282.00 × 376.00 | 0.7500:1 | [Section](screenshots/feed-analog-obsession-d2fc1b43--product-split-1.jpg) |
| Runout | `product-split-1` | `home.product_split_1.image_4_alt` | 282.00 × 376.00 | 0.7500:1 | [Section](screenshots/feed-analog-obsession-d2fc1b43--product-split-1.jpg) |
| Après Refresh | `cta-carousel` | `home.cta_carousel.image_1_alt` | 332.00 × 498.00 | 0.6667:1 | [Section](screenshots/feed-apres-refresh-58387694--cta-carousel.jpg) |
| Après Refresh | `cta-carousel` | `home.cta_carousel.image_2_alt` | 332.00 × 498.00 | 0.6667:1 | [Section](screenshots/feed-apres-refresh-58387694--cta-carousel.jpg) |
| Après Refresh | `cta-carousel` | `home.cta_carousel.image_3_alt` | 332.00 × 498.00 | 0.6667:1 | [Section](screenshots/feed-apres-refresh-58387694--cta-carousel.jpg) |
| Après Refresh | `cta-carousel` | `home.cta_carousel.image_4_alt` | 332.00 × 498.00 | 0.6667:1 | [Section](screenshots/feed-apres-refresh-58387694--cta-carousel.jpg) |
| Atelier Alegre | `product-carousel` | `home.product_carousel.image_1_alt` | 405.33 × 506.66 | 0.8000:1 | [Section](screenshots/feed-atelier-alegre-b54494bc--product-carousel.jpg) |
| Atelier Alegre | `product-carousel` | `home.product_carousel.image_2_alt` | 405.33 × 506.66 | 0.8000:1 | [Section](screenshots/feed-atelier-alegre-b54494bc--product-carousel.jpg) |
| Atelier Alegre | `product-carousel` | `home.product_carousel.image_3_alt` | 405.34 × 506.67 | 0.8000:1 | [Section](screenshots/feed-atelier-alegre-b54494bc--product-carousel.jpg) |
| Atelier Alegre | `product-carousel` | `home.product_carousel.image_4_alt` | 405.33 × 506.66 | 0.8000:1 | [Section](screenshots/feed-atelier-alegre-b54494bc--product-carousel.jpg) |
| Bake Central Pop Studio | `product-tile-grid` | `home.product_tile_grid.image_1_alt` | 361.33 × 451.66 | 0.8000:1 | [Section](screenshots/feed-bake-central-pop-studio-c09d7458--product-tile-grid.jpg) |
| Bake Central Pop Studio | `product-tile-grid` | `home.product_tile_grid.image_2_alt` | 361.33 × 451.66 | 0.8000:1 | [Section](screenshots/feed-bake-central-pop-studio-c09d7458--product-tile-grid.jpg) |
| Bake Central Pop Studio | `product-tile-grid` | `home.product_tile_grid.image_3_alt` | 361.34 × 451.67 | 0.8000:1 | [Section](screenshots/feed-bake-central-pop-studio-c09d7458--product-tile-grid.jpg) |
| Bake Central Pop Studio | `product-tile-grid` | `home.product_tile_grid.image_4_alt` | 361.33 × 451.66 | 0.8000:1 | [Section](screenshots/feed-bake-central-pop-studio-c09d7458--product-tile-grid.jpg) |
| Bake Central Pop Studio | `product-tile-grid` | `home.product_tile_grid.image_5_alt` | 361.33 × 451.66 | 0.8000:1 | [Section](screenshots/feed-bake-central-pop-studio-c09d7458--product-tile-grid.jpg) |
| Bake Central Pop Studio | `product-tile-grid` | `home.product_tile_grid.image_6_alt` | 361.34 × 451.67 | 0.8000:1 | [Section](screenshots/feed-bake-central-pop-studio-c09d7458--product-tile-grid.jpg) |
| Bold on Every Table | `commerce-product-index` | `home.commerce_product_index.image_1_alt` | 742.39 × 700.00 | 1.0606:1 | [Section](screenshots/feed-bold-on-every-table-4b87b962--commerce-product-index.jpg) |
| Bold on Every Table | `commerce-product-index` | `home.commerce_product_index.image_2_alt` | 742.39 × 700.00 | 1.0606:1 | [Section](screenshots/feed-bold-on-every-table-4b87b962--commerce-product-index.jpg) |
| Bold on Every Table | `commerce-product-index` | `home.commerce_product_index.image_3_alt` | 742.39 × 700.00 | 1.0606:1 | [Section](screenshots/feed-bold-on-every-table-4b87b962--commerce-product-index.jpg) |
| Bold on Every Table | `commerce-product-index` | `home.commerce_product_index.image_4_alt` | 742.39 × 700.00 | 1.0606:1 | [Section](screenshots/feed-bold-on-every-table-4b87b962--commerce-product-index.jpg) |
| Bold on Every Table | `hero-diptych-rail` | `home.hero_diptych_rail.image_1_alt` | 720.00 × 920.00 | 0.7826:1 | [Section](screenshots/feed-bold-on-every-table-4b87b962--hero-diptych-rail.jpg) |
| Bold on Every Table | `hero-diptych-rail` | `home.hero_diptych_rail.image_2_alt` | 720.00 × 920.00 | 0.7826:1 | [Section](screenshots/feed-bold-on-every-table-4b87b962--hero-diptych-rail.jpg) |
| Brew & Play | `hero-collab-lockup` | `home.hero_collab_lockup.image_1_alt` | 294.66 × 368.31 | 0.8000:1 | [Section](screenshots/feed-brew-play-f9e55d21--hero-collab-lockup.jpg) |
| Brew & Play | `hero-collab-lockup` | `home.hero_collab_lockup.image_2_alt` | 294.67 × 368.33 | 0.8000:1 | [Section](screenshots/feed-brew-play-f9e55d21--hero-collab-lockup.jpg) |
| Brew & Play | `hero-collab-lockup` | `home.hero_collab_lockup.image_3_alt` | 294.66 × 368.31 | 0.8000:1 | [Section](screenshots/feed-brew-play-f9e55d21--hero-collab-lockup.jpg) |
| Brew & Play | `hero-collab-lockup` | `home.hero_collab_lockup.image_4_alt` | 294.66 × 368.31 | 0.8000:1 | [Section](screenshots/feed-brew-play-f9e55d21--hero-collab-lockup.jpg) |
| Brew & Play | `hero-collab-lockup` | `home.hero_collab_lockup.image_5_alt` | 294.67 × 368.33 | 0.8000:1 | [Section](screenshots/feed-brew-play-f9e55d21--hero-collab-lockup.jpg) |
| Canvas Bloom Studio | `commerce-product-row` | `home.commerce_product_row.image_1_alt` | 412.81 × 516.02 | 0.8000:1 | [Section](screenshots/feed-canvas-bloom-studio-58769c9d--commerce-product-row.jpg) |
| Canvas Bloom Studio | `commerce-product-row` | `home.commerce_product_row.image_2_alt` | 412.81 × 516.02 | 0.8000:1 | [Section](screenshots/feed-canvas-bloom-studio-58769c9d--commerce-product-row.jpg) |
| Canvas Bloom Studio | `commerce-product-row` | `home.commerce_product_row.image_3_alt` | 412.81 × 516.02 | 0.8000:1 | [Section](screenshots/feed-canvas-bloom-studio-58769c9d--commerce-product-row.jpg) |
| Cheerful Pop | `product-ready-to-wear` | `home.product_ready_to_wear.image_1_alt` | 346.66 × 346.66 | 1.0000:1 | [Section](screenshots/feed-cheerful-pop-ba54b077--product-ready-to-wear.jpg) |
| Cheerful Pop | `product-ready-to-wear` | `home.product_ready_to_wear.image_2_alt` | 346.67 × 346.67 | 1.0000:1 | [Section](screenshots/feed-cheerful-pop-ba54b077--product-ready-to-wear.jpg) |
| Cheerful Pop | `product-ready-to-wear` | `home.product_ready_to_wear.image_3_alt` | 346.66 × 346.66 | 1.0000:1 | [Section](screenshots/feed-cheerful-pop-ba54b077--product-ready-to-wear.jpg) |
| City Sanctuary | `commerce-bundle-columns` | `home.commerce_bundle_columns.image_1_alt` | 440.00 × 586.66 | 0.7500:1 | [Section](screenshots/feed-city-sanctuary-a3408300--commerce-bundle-columns.jpg) |
| City Sanctuary | `commerce-bundle-columns` | `home.commerce_bundle_columns.image_2_alt` | 440.00 × 586.66 | 0.7500:1 | [Section](screenshots/feed-city-sanctuary-a3408300--commerce-bundle-columns.jpg) |
| City Sanctuary | `commerce-bundle-columns` | `home.commerce_bundle_columns.image_3_alt` | 440.00 × 586.66 | 0.7500:1 | [Section](screenshots/feed-city-sanctuary-a3408300--commerce-bundle-columns.jpg) |
| Common Iron | `commerce-product-lineup` | `home.commerce_product_lineup.image_1_alt` | 302.00 × 402.66 | 0.7500:1 | [Section](screenshots/feed-common-iron-c99e3f8d--commerce-product-lineup.jpg) |
| Common Iron | `commerce-product-lineup` | `home.commerce_product_lineup.image_2_alt` | 302.00 × 402.66 | 0.7500:1 | [Section](screenshots/feed-common-iron-c99e3f8d--commerce-product-lineup.jpg) |
| Common Iron | `commerce-product-lineup` | `home.commerce_product_lineup.image_3_alt` | 302.00 × 402.66 | 0.7500:1 | [Section](screenshots/feed-common-iron-c99e3f8d--commerce-product-lineup.jpg) |
| Common Iron | `commerce-product-lineup` | `home.commerce_product_lineup.image_4_alt` | 302.00 × 402.66 | 0.7500:1 | [Section](screenshots/feed-common-iron-c99e3f8d--commerce-product-lineup.jpg) |
| Concrete Pulse | `commerce-lookbook` | `home.commerce_lookbook.image_1_alt` | 552.66 × 828.98 | 0.6667:1 | [Section](screenshots/feed-concrete-pulse-ca531534--commerce-lookbook.jpg) |
| Concrete Pulse | `commerce-lookbook` | `home.commerce_lookbook.image_2_alt` | 322.00 × 483.00 | 0.6667:1 | [Section](screenshots/feed-concrete-pulse-ca531534--commerce-lookbook.jpg) |
| Concrete Pulse | `commerce-lookbook` | `home.commerce_lookbook.image_3_alt` | 322.00 × 483.00 | 0.6667:1 | [Section](screenshots/feed-concrete-pulse-ca531534--commerce-lookbook.jpg) |
| Contemporary Heirlooms | `commerce-grid` | `home.commerce_grid.image_1_alt` | 312.50 × 390.62 | 0.8000:1 | [Section](screenshots/feed-contemporary-heirlooms-464aae1b--commerce-grid.jpg) |
| Contemporary Heirlooms | `commerce-grid` | `home.commerce_grid.image_2_alt` | 312.50 × 390.62 | 0.8000:1 | [Section](screenshots/feed-contemporary-heirlooms-464aae1b--commerce-grid.jpg) |
| Contemporary Heirlooms | `commerce-grid` | `home.commerce_grid.image_3_alt` | 312.50 × 390.62 | 0.8000:1 | [Section](screenshots/feed-contemporary-heirlooms-464aae1b--commerce-grid.jpg) |
| Contemporary Heirlooms | `commerce-grid` | `home.commerce_grid.image_4_alt` | 312.50 × 390.62 | 0.8000:1 | [Section](screenshots/feed-contemporary-heirlooms-464aae1b--commerce-grid.jpg) |
| Court Culture | `features-stacked` | `home.features_stacked.image_1_alt` | 458.45 × 489.02 | 0.9375:1 | [Section](screenshots/feed-court-culture-cbcc330d--features-stacked.jpg) |
| Court Culture | `product-ritual-trio` | `home.product_ritual_trio.image_1_alt` | 341.33 × 568.88 | 0.6000:1 | [Section](screenshots/feed-court-culture-cbcc330d--product-ritual-trio.jpg) |
| Court Culture | `product-ritual-trio` | `home.product_ritual_trio.image_2_alt` | 341.33 × 568.88 | 0.6000:1 | [Section](screenshots/feed-court-culture-cbcc330d--product-ritual-trio.jpg) |
| Court Culture | `product-ritual-trio` | `home.product_ritual_trio.image_3_alt` | 341.34 × 568.91 | 0.6000:1 | [Section](screenshots/feed-court-culture-cbcc330d--product-ritual-trio.jpg) |
| Creative Playground | `product-color-panel` | `home.product_color_panel.image_1_alt` | 853.33 × 465.98 | 1.8312:1 | [Section](screenshots/feed-creative-playground-2a7e4846--product-color-panel.jpg) |
| Desk Objects in Motion | `product-featured-trio` | `home.product_featured_trio.image_1_alt` | 442.66 × 553.31 | 0.8000:1 | [Section](screenshots/feed-desk-objects-in-motion-5a7b5319--product-featured-trio.jpg) |
| Desk Objects in Motion | `product-featured-trio` | `home.product_featured_trio.image_2_alt` | 442.67 × 553.33 | 0.8000:1 | [Section](screenshots/feed-desk-objects-in-motion-5a7b5319--product-featured-trio.jpg) |
| Desk Objects in Motion | `product-featured-trio` | `home.product_featured_trio.image_3_alt` | 442.66 × 553.31 | 0.8000:1 | [Section](screenshots/feed-desk-objects-in-motion-5a7b5319--product-featured-trio.jpg) |
| Desk to Drinks | `content-grid-articles` | `home.content_grid_articles.image_1_alt` | 444.00 × 555.00 | 0.8000:1 | [Section](screenshots/feed-desk-to-drinks-3492b0dc--content-grid-articles.jpg) |
| Desk to Drinks | `content-grid-articles` | `home.content_grid_articles.image_2_alt` | 444.00 × 555.00 | 0.8000:1 | [Section](screenshots/feed-desk-to-drinks-3492b0dc--content-grid-articles.jpg) |
| Desk to Drinks | `content-grid-articles` | `home.content_grid_articles.image_3_alt` | 444.00 × 555.00 | 0.8000:1 | [Section](screenshots/feed-desk-to-drinks-3492b0dc--content-grid-articles.jpg) |
| Desk to Drinks | `product-split-2` | `home.product_split_2.image_1_alt` | 1440.00 × 800.00 | 1.8000:1 | [Section](screenshots/feed-desk-to-drinks-3492b0dc--product-split-2.jpg) |
| Desk to Drinks | `commerce-grid` | `home.commerce_grid.image_1_alt` | 308.00 × 410.66 | 0.7500:1 | [Section](screenshots/feed-desk-to-drinks-605d453a--commerce-grid.jpg) |
| Desk to Drinks | `commerce-grid` | `home.commerce_grid.image_2_alt` | 308.00 × 410.66 | 0.7500:1 | [Section](screenshots/feed-desk-to-drinks-605d453a--commerce-grid.jpg) |
| Desk to Drinks | `commerce-grid` | `home.commerce_grid.image_3_alt` | 308.00 × 410.66 | 0.7500:1 | [Section](screenshots/feed-desk-to-drinks-605d453a--commerce-grid.jpg) |
| Desk to Drinks | `commerce-grid` | `home.commerce_grid.image_4_alt` | 308.00 × 410.66 | 0.7500:1 | [Section](screenshots/feed-desk-to-drinks-605d453a--commerce-grid.jpg) |
| Driftline | `product-tile-grid` | `home.product_tile_grid.image_1_alt` | 334.00 × 417.50 | 0.8000:1 | [Section](screenshots/feed-driftline-aac4d214--product-tile-grid.jpg) |
| Driftline | `product-tile-grid` | `home.product_tile_grid.image_2_alt` | 334.00 × 417.50 | 0.8000:1 | [Section](screenshots/feed-driftline-aac4d214--product-tile-grid.jpg) |
| Driftline | `product-tile-grid` | `home.product_tile_grid.image_3_alt` | 334.00 × 417.50 | 0.8000:1 | [Section](screenshots/feed-driftline-aac4d214--product-tile-grid.jpg) |
| Driftline | `product-tile-grid` | `home.product_tile_grid.image_4_alt` | 334.00 × 417.50 | 0.8000:1 | [Section](screenshots/feed-driftline-aac4d214--product-tile-grid.jpg) |
| Effortless Rituals | `cta-shoppable-video-strip` | `home.cta_shoppable_video_strip.image_1_alt` | 323.00 × 403.75 | 0.8000:1 | [Section](screenshots/feed-effortless-rituals-3899a311--cta-shoppable-video-strip.jpg) |
| Effortless Rituals | `cta-shoppable-video-strip` | `home.cta_shoppable_video_strip.image_2_alt` | 323.00 × 403.75 | 0.8000:1 | [Section](screenshots/feed-effortless-rituals-3899a311--cta-shoppable-video-strip.jpg) |
| Effortless Rituals | `cta-shoppable-video-strip` | `home.cta_shoppable_video_strip.image_3_alt` | 323.00 × 403.75 | 0.8000:1 | [Section](screenshots/feed-effortless-rituals-3899a311--cta-shoppable-video-strip.jpg) |
| Effortless Rituals | `cta-shoppable-video-strip` | `home.cta_shoppable_video_strip.image_4_alt` | 323.00 × 403.75 | 0.8000:1 | [Section](screenshots/feed-effortless-rituals-3899a311--cta-shoppable-video-strip.jpg) |
| Effortless Rituals | `cta-shoppable-video-strip` | `home.cta_shoppable_video_strip.image_5_alt` | 324.00 × 405.00 | 0.8000:1 | [Section](screenshots/feed-effortless-rituals-3899a311--cta-shoppable-video-strip.jpg) |
| Electric Ember | `commerce-spec-sheet` | `home.commerce_spec_sheet.image_1_alt` | 638.89 × 479.16 | 1.3334:1 | [Section](screenshots/feed-electric-ember-0489b72f--commerce-spec-sheet.jpg) |
| Electric Ember | `product-tile-grid` | `home.product_tile_grid.image_1_alt` | 279.00 × 372.00 | 0.7500:1 | [Section](screenshots/feed-electric-ember-0489b72f--product-tile-grid.jpg) |
| Electric Ember | `product-tile-grid` | `home.product_tile_grid.image_2_alt` | 279.00 × 372.00 | 0.7500:1 | [Section](screenshots/feed-electric-ember-0489b72f--product-tile-grid.jpg) |
| Electric Ember | `product-tile-grid` | `home.product_tile_grid.image_3_alt` | 279.00 × 372.00 | 0.7500:1 | [Section](screenshots/feed-electric-ember-0489b72f--product-tile-grid.jpg) |
| Electric Ember | `product-tile-grid` | `home.product_tile_grid.image_4_alt` | 280.00 × 373.33 | 0.7500:1 | [Section](screenshots/feed-electric-ember-0489b72f--product-tile-grid.jpg) |
| ERESU | `commerce-split` | `home.commerce_split.image_1_alt` | 720.00 × 960.00 | 0.7500:1 | [Section](screenshots/feed-eresu-6b7e93b2--commerce-split.jpg) |
| ERESU | `editorial-quote-portrait` | `home.editorial_quote_portrait.image_1_alt` | 720.00 × 960.00 | 0.7500:1 | [Section](screenshots/feed-eresu-6b7e93b2--editorial-quote-portrait.jpg) |
| ERESU | `editorial-split` | `home.editorial_split.image_1_alt` | 720.00 × 960.00 | 0.7500:1 | [Section](screenshots/feed-eresu-6b7e93b2--editorial-split.jpg) |
| ERESU | `hero-statement-split` | `home.hero_statement_split.image_1_alt` | 720.00 × 900.00 | 0.8000:1 | [Section](screenshots/feed-eresu-6b7e93b2--hero-statement-split.jpg) |
| ERESU | `product-collection-portrait` | `home.product_collection_portrait.image_1_alt` | 480.00 × 640.00 | 0.7500:1 | [Section](screenshots/feed-eresu-6b7e93b2--product-collection-portrait.jpg) |
| Everyday Elevated | `commerce-lookbook` | `home.commerce_lookbook.image_1_alt` | 480.00 × 640.00 | 0.7500:1 | [Section](screenshots/feed-everyday-elevated-3acc8cc4--commerce-lookbook.jpg) |
| Everyday Elevated | `commerce-lookbook` | `home.commerce_lookbook.image_2_alt` | 480.00 × 640.00 | 0.7500:1 | [Section](screenshots/feed-everyday-elevated-3acc8cc4--commerce-lookbook.jpg) |
| Everyday Elevated | `commerce-lookbook` | `home.commerce_lookbook.image_3_alt` | 480.00 × 640.00 | 0.7500:1 | [Section](screenshots/feed-everyday-elevated-3acc8cc4--commerce-lookbook.jpg) |
| Everyday Luxe Editorial | `content-split-howto` | `home.content_split_howto.image_1_alt` | 560.00 × 448.00 | 1.2500:1 | [Section](screenshots/feed-everyday-luxe-editorial-351eedcd--content-split-howto.jpg) |
| Everyday Luxe Editorial | `product-featured-trio` | `home.product_featured_trio.image_1_alt` | 343.00 × 457.33 | 0.7500:1 | [Section](screenshots/feed-everyday-luxe-editorial-351eedcd--product-featured-trio.jpg) |
| Everyday Luxe Editorial | `product-featured-trio` | `home.product_featured_trio.image_2_alt` | 343.00 × 457.33 | 0.7500:1 | [Section](screenshots/feed-everyday-luxe-editorial-351eedcd--product-featured-trio.jpg) |
| Everyday Luxe Editorial | `product-featured-trio` | `home.product_featured_trio.image_3_alt` | 343.00 × 457.33 | 0.7500:1 | [Section](screenshots/feed-everyday-luxe-editorial-351eedcd--product-featured-trio.jpg) |
| Everyday Luxe Editorial | `product-featured-trio` | `home.product_featured_trio.image_4_alt` | 343.00 × 457.33 | 0.7500:1 | [Section](screenshots/feed-everyday-luxe-editorial-351eedcd--product-featured-trio.jpg) |
| Everyday Luxe Editorial | `product-featured-trio` | `home.product_featured_trio.image_5_alt` | 343.00 × 457.33 | 0.7500:1 | [Section](screenshots/feed-everyday-luxe-editorial-351eedcd--product-featured-trio.jpg) |
| Everyday Luxe Editorial | `product-featured-trio` | `home.product_featured_trio.image_6_alt` | 343.00 × 457.33 | 0.7500:1 | [Section](screenshots/feed-everyday-luxe-editorial-351eedcd--product-featured-trio.jpg) |
| Everyday Luxe Editorial | `product-featured-trio` | `home.product_featured_trio.image_7_alt` | 343.00 × 457.33 | 0.7500:1 | [Section](screenshots/feed-everyday-luxe-editorial-351eedcd--product-featured-trio.jpg) |
| Feel-Good Fuel | `product-lookbook-banner` | `home.product_lookbook_banner.image_1_alt` | 1440.00 × 810.00 | 1.7778:1 | [Section](screenshots/feed-feel-good-fuel-e35eff31--product-lookbook-banner.jpg) |
| Feel-Good Fuel | `product-tile-grid` | `home.product_tile_grid.image_1_alt` | 359.00 × 448.75 | 0.8000:1 | [Section](screenshots/feed-feel-good-fuel-e35eff31--product-tile-grid.jpg) |
| Feel-Good Fuel | `product-tile-grid` | `home.product_tile_grid.image_2_alt` | 359.00 × 448.75 | 0.8000:1 | [Section](screenshots/feed-feel-good-fuel-e35eff31--product-tile-grid.jpg) |
| Feel-Good Fuel | `product-tile-grid` | `home.product_tile_grid.image_3_alt` | 359.00 × 448.75 | 0.8000:1 | [Section](screenshots/feed-feel-good-fuel-e35eff31--product-tile-grid.jpg) |
| Feel-Good Fuel | `product-tile-grid` | `home.product_tile_grid.image_4_alt` | 359.00 × 448.75 | 0.8000:1 | [Section](screenshots/feed-feel-good-fuel-e35eff31--product-tile-grid.jpg) |
| Festive Table Stories | `product-grid-1` | `home.product_grid_1.image_1_alt` | 719.50 × 1028.42 | 0.6996:1 | [Section](screenshots/feed-festive-table-stories-9d092267--product-grid-1.jpg) |
| Festive Table Stories | `product-grid-1` | `home.product_grid_1.image_2_alt` | 359.25 × 449.06 | 0.8000:1 | [Section](screenshots/feed-festive-table-stories-9d092267--product-grid-1.jpg) |
| Festive Table Stories | `product-grid-1` | `home.product_grid_1.image_3_alt` | 359.25 × 449.06 | 0.8000:1 | [Section](screenshots/feed-festive-table-stories-9d092267--product-grid-1.jpg) |
| Festive Table Stories | `product-grid-1` | `home.product_grid_1.image_4_alt` | 359.25 × 449.06 | 0.8000:1 | [Section](screenshots/feed-festive-table-stories-9d092267--product-grid-1.jpg) |
| Festive Table Stories | `product-grid-1` | `home.product_grid_1.image_5_alt` | 359.25 × 449.06 | 0.8000:1 | [Section](screenshots/feed-festive-table-stories-9d092267--product-grid-1.jpg) |
| Festive Table Stories | `product-ritual-trio` | `home.product_ritual_trio.image_1_alt` | 413.33 × 516.66 | 0.8000:1 | [Section](screenshots/feed-festive-table-stories-9d092267--product-ritual-trio.jpg) |
| Frame Club | `features-split` | `home.features_split.image_1_alt` | 16.00 × 16.00 | 1.0000:1 | [Section](screenshots/feed-frame-club-b76f7d53--features-split.jpg) |
| Frame Club | `features-split` | `home.features_split.image_2_alt` | 16.00 × 16.00 | 1.0000:1 | [Section](screenshots/feed-frame-club-b76f7d53--features-split.jpg) |
| Frame Club | `features-split` | `home.features_split.image_3_alt` | 16.00 × 16.00 | 1.0000:1 | [Section](screenshots/feed-frame-club-b76f7d53--features-split.jpg) |
| Frame Club | `features-split` | `home.features_split.image_4_alt` | 16.00 × 16.00 | 1.0000:1 | [Section](screenshots/feed-frame-club-b76f7d53--features-split.jpg) |
| Frame Club | `product-finish-variants` | `home.product_finish_variants.image_1_alt` | 16.00 × 16.00 | 1.0000:1 | [Section](screenshots/feed-frame-club-b76f7d53--product-finish-variants.jpg) |
| Gathered at the Table | `cta-carousel` | `home.cta_carousel.image_1_alt` | 321.00 × 401.25 | 0.8000:1 | [Section](screenshots/feed-gathered-at-the-table-0f227565--cta-carousel.jpg) |
| Gathered at the Table | `cta-carousel` | `home.cta_carousel.image_2_alt` | 321.00 × 401.25 | 0.8000:1 | [Section](screenshots/feed-gathered-at-the-table-0f227565--cta-carousel.jpg) |
| Gathered at the Table | `cta-carousel` | `home.cta_carousel.image_3_alt` | 321.00 × 401.25 | 0.8000:1 | [Section](screenshots/feed-gathered-at-the-table-0f227565--cta-carousel.jpg) |
| Gathered at the Table | `cta-carousel` | `home.cta_carousel.image_4_alt` | 321.00 × 401.25 | 0.8000:1 | [Section](screenshots/feed-gathered-at-the-table-0f227565--cta-carousel.jpg) |
| Gathered at the Table | `product-split-1` | `home.product_split_1.image_2_alt` | 184.00 × 230.00 | 0.8000:1 | [Section](screenshots/feed-gathered-at-the-table-0f227565--product-split-1.jpg) |
| Glim | `commerce-product-lineup` | `home.commerce_product_lineup.image_1_alt` | 317.23 × 528.72 | 0.6000:1 | [Section](screenshots/feed-glim-1955fe62--commerce-product-lineup.jpg) |
| Glim | `commerce-product-lineup` | `home.commerce_product_lineup.image_2_alt` | 317.23 × 528.72 | 0.6000:1 | [Section](screenshots/feed-glim-1955fe62--commerce-product-lineup.jpg) |
| Glim | `commerce-product-lineup` | `home.commerce_product_lineup.image_3_alt` | 317.23 × 528.72 | 0.6000:1 | [Section](screenshots/feed-glim-1955fe62--commerce-product-lineup.jpg) |
| Glim | `commerce-product-lineup` | `home.commerce_product_lineup.image_4_alt` | 317.23 × 528.72 | 0.6000:1 | [Section](screenshots/feed-glim-1955fe62--commerce-product-lineup.jpg) |
| Golden Hour Heritage | `hero-stacked-2` | `home.hero_stacked_2.image_1_alt` | 675.98 × 901.33 | 0.7500:1 | [Section](screenshots/feed-golden-hour-heritage-cf0e8500--hero-stacked-2.jpg) |
| Golden Hour Heritage | `product-campaign-scene` | `home.product_campaign_scene.image_1_alt` | 458.67 × 688.00 | 0.6667:1 | [Section](screenshots/feed-golden-hour-heritage-cf0e8500--product-campaign-scene.jpg) |
| Golden Hour Heritage | `product-campaign-scene` | `home.product_campaign_scene.image_2_alt` | 458.66 × 687.98 | 0.6667:1 | [Section](screenshots/feed-golden-hour-heritage-cf0e8500--product-campaign-scene.jpg) |
| Golden Interval | `commerce-overlap-feature` | `home.commerce_overlap_feature.image_1_alt` | 518.00 × 647.50 | 0.8000:1 | [Section](screenshots/feed-golden-interval-616ba7c1--commerce-overlap-feature.jpg) |
| Golden Interval | `commerce-product-lineup` | `home.commerce_product_lineup.image_1_alt` | 318.00 × 397.50 | 0.8000:1 | [Section](screenshots/feed-golden-interval-616ba7c1--commerce-product-lineup.jpg) |
| Golden Interval | `commerce-product-lineup` | `home.commerce_product_lineup.image_2_alt` | 318.00 × 397.50 | 0.8000:1 | [Section](screenshots/feed-golden-interval-616ba7c1--commerce-product-lineup.jpg) |
| Golden Interval | `commerce-product-lineup` | `home.commerce_product_lineup.image_3_alt` | 318.00 × 397.50 | 0.8000:1 | [Section](screenshots/feed-golden-interval-616ba7c1--commerce-product-lineup.jpg) |
| Golden Interval | `commerce-product-lineup` | `home.commerce_product_lineup.image_4_alt` | 318.00 × 397.50 | 0.8000:1 | [Section](screenshots/feed-golden-interval-616ba7c1--commerce-product-lineup.jpg) |
| Saltglass Swim | `product-carousel` | `home.product_carousel.image_1_alt` | 305.00 × 381.25 | 0.8000:1 | [Section](screenshots/feed-golden-tide-collective-cbe226a1--product-carousel.jpg) |
| Saltglass Swim | `product-carousel` | `home.product_carousel.image_2_alt` | 305.00 × 381.25 | 0.8000:1 | [Section](screenshots/feed-golden-tide-collective-cbe226a1--product-carousel.jpg) |
| Saltglass Swim | `product-carousel` | `home.product_carousel.image_3_alt` | 305.00 × 381.25 | 0.8000:1 | [Section](screenshots/feed-golden-tide-collective-cbe226a1--product-carousel.jpg) |
| Haunted Hearth | `commerce-lookbook` | `home.commerce_lookbook.image_1_alt` | 325.98 × 434.64 | 0.7500:1 | [Section](screenshots/feed-haunted-hearth-74841fa7--commerce-lookbook.jpg) |
| Haunted Hearth | `commerce-lookbook` | `home.commerce_lookbook.image_2_alt` | 326.00 × 434.66 | 0.7500:1 | [Section](screenshots/feed-haunted-hearth-74841fa7--commerce-lookbook.jpg) |
| Haunted Hearth | `commerce-lookbook` | `home.commerce_lookbook.image_3_alt` | 326.00 × 434.66 | 0.7500:1 | [Section](screenshots/feed-haunted-hearth-74841fa7--commerce-lookbook.jpg) |
| Haunted Hearth | `commerce-lookbook` | `home.commerce_lookbook.image_4_alt` | 326.00 × 434.66 | 0.7500:1 | [Section](screenshots/feed-haunted-hearth-74841fa7--commerce-lookbook.jpg) |
| Haven & Hearth | `commerce-grid` | `home.commerce_grid.image_1_alt` | 305.00 × 381.25 | 0.8000:1 | [Section](screenshots/feed-haven-hearth-02c64983--commerce-grid.jpg) |
| Haven & Hearth | `commerce-grid` | `home.commerce_grid.image_2_alt` | 305.00 × 381.25 | 0.8000:1 | [Section](screenshots/feed-haven-hearth-02c64983--commerce-grid.jpg) |
| Haven & Hearth | `commerce-grid` | `home.commerce_grid.image_3_alt` | 305.00 × 381.25 | 0.8000:1 | [Section](screenshots/feed-haven-hearth-02c64983--commerce-grid.jpg) |
| Haven & Hearth | `commerce-grid` | `home.commerce_grid.image_4_alt` | 305.00 × 381.25 | 0.8000:1 | [Section](screenshots/feed-haven-hearth-02c64983--commerce-grid.jpg) |
| Haven & Hearth | `product-carousel` | `home.product_carousel.image_1_alt` | 305.00 × 381.25 | 0.8000:1 | [Section](screenshots/feed-haven-hearth-02c64983--product-carousel.jpg) |
| Haven & Hearth | `product-carousel` | `home.product_carousel.image_2_alt` | 305.00 × 381.25 | 0.8000:1 | [Section](screenshots/feed-haven-hearth-02c64983--product-carousel.jpg) |
| Haven & Hearth | `product-carousel` | `home.product_carousel.image_3_alt` | 305.00 × 381.25 | 0.8000:1 | [Section](screenshots/feed-haven-hearth-02c64983--product-carousel.jpg) |
| Haze & Co. | `product-collection-pair` | `home.product_collection_pair.image_2_alt` | 738.34 × 922.92 | 0.8000:1 | [Section](screenshots/feed-haze-co-ddebc1c9--product-collection-pair.jpg) |
| Haze & Co. | `product-grid-1` | `home.product_grid_1.image_2_alt` | 296.00 × 370.00 | 0.8000:1 | [Section](screenshots/feed-haze-co-ddebc1c9--product-grid-1.jpg) |
| Haze & Co. | `product-grid-1` | `home.product_grid_1.image_3_alt` | 296.00 × 370.00 | 0.8000:1 | [Section](screenshots/feed-haze-co-ddebc1c9--product-grid-1.jpg) |
| Haze & Co. | `product-grid-1` | `home.product_grid_1.image_4_alt` | 296.00 × 370.00 | 0.8000:1 | [Section](screenshots/feed-haze-co-ddebc1c9--product-grid-1.jpg) |
| Haze & Co. | `product-grid-1` | `home.product_grid_1.image_5_alt` | 296.00 × 370.00 | 0.8000:1 | [Section](screenshots/feed-haze-co-ddebc1c9--product-grid-1.jpg) |
| Joyful Spectrum | `commerce-lookbook` | `home.commerce_lookbook.image_1_alt` | 235.55 × 235.55 | 1.0000:1 | [Section](screenshots/feed-joyful-spectrum-13c173a0--commerce-lookbook.jpg) |
| Joyful Spectrum | `commerce-lookbook` | `home.commerce_lookbook.image_2_alt` | 235.55 × 235.55 | 1.0000:1 | [Section](screenshots/feed-joyful-spectrum-13c173a0--commerce-lookbook.jpg) |
| Joyful Spectrum | `commerce-lookbook` | `home.commerce_lookbook.image_3_alt` | 235.55 × 235.55 | 1.0000:1 | [Section](screenshots/feed-joyful-spectrum-13c173a0--commerce-lookbook.jpg) |
| Joyful Spectrum | `commerce-lookbook` | `home.commerce_lookbook.image_4_alt` | 235.55 × 235.55 | 1.0000:1 | [Section](screenshots/feed-joyful-spectrum-13c173a0--commerce-lookbook.jpg) |
| Joyful Spectrum | `features-overlap` | `home.features_overlap.image_1_alt` | 56.00 × 56.00 | 1.0000:1 | [Section](screenshots/feed-joyful-spectrum-13c173a0--features-overlap.jpg) |
| Joyful Spectrum | `features-overlap` | `home.features_overlap.image_2_alt` | 56.00 × 56.00 | 1.0000:1 | [Section](screenshots/feed-joyful-spectrum-13c173a0--features-overlap.jpg) |
| Joyful Spectrum | `features-overlap` | `home.features_overlap.image_3_alt` | 56.00 × 56.00 | 1.0000:1 | [Section](screenshots/feed-joyful-spectrum-13c173a0--features-overlap.jpg) |
| Kumo | `commerce-product-lineup` | `home.commerce_product_lineup.image_1_alt` | 308.00 × 410.66 | 0.7500:1 | [Section](screenshots/feed-kumo-9411624c--commerce-product-lineup.jpg) |
| Kumo | `commerce-product-lineup` | `home.commerce_product_lineup.image_2_alt` | 308.00 × 410.66 | 0.7500:1 | [Section](screenshots/feed-kumo-9411624c--commerce-product-lineup.jpg) |
| Kumo | `commerce-product-lineup` | `home.commerce_product_lineup.image_3_alt` | 308.00 × 410.66 | 0.7500:1 | [Section](screenshots/feed-kumo-9411624c--commerce-product-lineup.jpg) |
| Kumo | `commerce-product-lineup` | `home.commerce_product_lineup.image_4_alt` | 308.00 × 410.66 | 0.7500:1 | [Section](screenshots/feed-kumo-9411624c--commerce-product-lineup.jpg) |
| Kumo | `editorial-gallery-grid` | `home.editorial_gallery_grid.image_1_alt` | 416.00 × 554.66 | 0.7500:1 | [Section](screenshots/feed-kumo-9411624c--editorial-gallery-grid.jpg) |
| Kumo | `editorial-gallery-grid` | `home.editorial_gallery_grid.image_2_alt` | 416.00 × 554.66 | 0.7500:1 | [Section](screenshots/feed-kumo-9411624c--editorial-gallery-grid.jpg) |
| Kumo | `editorial-gallery-grid` | `home.editorial_gallery_grid.image_3_alt` | 416.00 × 554.66 | 0.7500:1 | [Section](screenshots/feed-kumo-9411624c--editorial-gallery-grid.jpg) |
| Lacé | `product-ready-to-wear` | `home.product_ready_to_wear.image_1_alt` | 415.98 × 623.97 | 0.6667:1 | [Section](screenshots/feed-lace-c6c3cf61--product-ready-to-wear.jpg) |
| Lacé | `product-ready-to-wear` | `home.product_ready_to_wear.image_2_alt` | 415.98 × 623.97 | 0.6667:1 | [Section](screenshots/feed-lace-c6c3cf61--product-ready-to-wear.jpg) |
| Lacé | `product-ready-to-wear` | `home.product_ready_to_wear.image_3_alt` | 415.98 × 623.97 | 0.6667:1 | [Section](screenshots/feed-lace-c6c3cf61--product-ready-to-wear.jpg) |
| Lacé | `product-ready-to-wear` | `home.product_ready_to_wear.image_4_alt` | 415.98 × 623.97 | 0.6667:1 | [Section](screenshots/feed-lace-c6c3cf61--product-ready-to-wear.jpg) |
| Lacé | `product-ready-to-wear` | `home.product_ready_to_wear.image_5_alt` | 415.98 × 623.97 | 0.6667:1 | [Section](screenshots/feed-lace-c6c3cf61--product-ready-to-wear.jpg) |
| Light as Art | `editorial-carousel` | `home.editorial_carousel.image_1_alt` | 358.66 × 537.98 | 0.6667:1 | [Section](screenshots/feed-light-as-art-d46a8a34--editorial-carousel.jpg) |
| Light as Art | `editorial-carousel` | `home.editorial_carousel.image_2_alt` | 358.67 × 538.00 | 0.6667:1 | [Section](screenshots/feed-light-as-art-d46a8a34--editorial-carousel.jpg) |
| Light as Art | `editorial-carousel` | `home.editorial_carousel.image_3_alt` | 358.66 × 537.98 | 0.6667:1 | [Section](screenshots/feed-light-as-art-d46a8a34--editorial-carousel.jpg) |
| Lived-In Glow | `editorial-gallery-grid` | `home.editorial_gallery_grid.image_1_alt` | 458.66 × 687.98 | 0.6667:1 | [Section](screenshots/feed-lived-in-glow-adf847a3--editorial-gallery-grid.jpg) |
| Lived-In Glow | `editorial-gallery-grid` | `home.editorial_gallery_grid.image_2_alt` | 458.67 × 688.00 | 0.6667:1 | [Section](screenshots/feed-lived-in-glow-adf847a3--editorial-gallery-grid.jpg) |
| Lived-In Glow | `editorial-gallery-grid` | `home.editorial_gallery_grid.image_3_alt` | 458.66 × 687.98 | 0.6667:1 | [Section](screenshots/feed-lived-in-glow-adf847a3--editorial-gallery-grid.jpg) |
| Lived-In Glow | `product-split-1` | `home.product_split_1.image_2_alt` | 720.00 × 900.00 | 0.8000:1 | [Section](screenshots/feed-lived-in-glow-adf847a3--product-split-1.jpg) |
| Lumen Club | `commerce-overlap-card` | `home.commerce_overlap_card.image_2_alt` | 56.00 × 56.00 | 1.0000:1 | [Section](screenshots/feed-lumen-club-f6014c3f--commerce-overlap-card.jpg) |
| Lumen Club | `cta-split-icon` | `home.cta_split_icon.image_1_alt` | 72.00 × 72.00 | 1.0000:1 | [Section](screenshots/feed-lumen-club-f6014c3f--cta-split-icon.jpg) |
| Lumen Club | `cta-split-icon` | `home.cta_split_icon.image_2_alt` | 72.00 × 72.00 | 1.0000:1 | [Section](screenshots/feed-lumen-club-f6014c3f--cta-split-icon.jpg) |
| Lumen Club | `cta-split-icon` | `home.cta_split_icon.image_3_alt` | 72.00 × 72.00 | 1.0000:1 | [Section](screenshots/feed-lumen-club-f6014c3f--cta-split-icon.jpg) |
| Lumen Club | `cta-split-icon` | `home.cta_split_icon.image_4_alt` | 72.00 × 72.00 | 1.0000:1 | [Section](screenshots/feed-lumen-club-f6014c3f--cta-split-icon.jpg) |
| Lumina Botanica | `commerce-grid` | `home.commerce_grid.image_1_alt` | 305.00 × 381.25 | 0.8000:1 | [Section](screenshots/feed-lumina-botanica-fee51738--commerce-grid.jpg) |
| Lumina Botanica | `commerce-grid` | `home.commerce_grid.image_2_alt` | 305.00 × 381.25 | 0.8000:1 | [Section](screenshots/feed-lumina-botanica-fee51738--commerce-grid.jpg) |
| Lumina Botanica | `commerce-grid` | `home.commerce_grid.image_3_alt` | 305.00 × 381.25 | 0.8000:1 | [Section](screenshots/feed-lumina-botanica-fee51738--commerce-grid.jpg) |
| Lumina Botanica | `commerce-grid` | `home.commerce_grid.image_4_alt` | 305.00 × 381.25 | 0.8000:1 | [Section](screenshots/feed-lumina-botanica-fee51738--commerce-grid.jpg) |
| Lumina Grain | `commerce-product-row` | `home.commerce_product_row.image_1_alt` | 351.00 × 438.75 | 0.8000:1 | [Section](screenshots/feed-lumina-grain-94e00c53--commerce-product-row.jpg) |
| Lumina Grain | `commerce-product-row` | `home.commerce_product_row.image_2_alt` | 351.00 × 438.75 | 0.8000:1 | [Section](screenshots/feed-lumina-grain-94e00c53--commerce-product-row.jpg) |
| Lumina Grain | `commerce-product-row` | `home.commerce_product_row.image_3_alt` | 352.00 × 440.00 | 0.8000:1 | [Section](screenshots/feed-lumina-grain-94e00c53--commerce-product-row.jpg) |
| Lumina Grain | `product-ready-to-wear` | `home.product_ready_to_wear.image_1_alt` | 426.00 × 568.00 | 0.7500:1 | [Section](screenshots/feed-lumina-grain-94e00c53--product-ready-to-wear.jpg) |
| Lumina Grain | `product-ready-to-wear` | `home.product_ready_to_wear.image_2_alt` | 426.00 × 568.00 | 0.7500:1 | [Section](screenshots/feed-lumina-grain-94e00c53--product-ready-to-wear.jpg) |
| Lumina Grain | `product-ready-to-wear` | `home.product_ready_to_wear.image_3_alt` | 426.00 × 568.00 | 0.7500:1 | [Section](screenshots/feed-lumina-grain-94e00c53--product-ready-to-wear.jpg) |
| Luminous Minimalism | `product-finish-variants` | `home.product_finish_variants.image_1_alt` | 288.00 × 360.00 | 0.8000:1 | [Section](screenshots/feed-luminous-minimalism-07f12a93--product-finish-variants.jpg) |
| Luminous Minimalism | `product-finish-variants` | `home.product_finish_variants.image_2_alt` | 288.00 × 360.00 | 0.8000:1 | [Section](screenshots/feed-luminous-minimalism-07f12a93--product-finish-variants.jpg) |
| Luminous Minimalism | `product-finish-variants` | `home.product_finish_variants.image_3_alt` | 288.00 × 360.00 | 0.8000:1 | [Section](screenshots/feed-luminous-minimalism-07f12a93--product-finish-variants.jpg) |
| Luminous Minimalism | `product-finish-variants` | `home.product_finish_variants.image_4_alt` | 288.00 × 360.00 | 0.8000:1 | [Section](screenshots/feed-luminous-minimalism-07f12a93--product-finish-variants.jpg) |
| Marée | `product-carousel` | `home.product_carousel.image_1_alt` | 477.33 × 596.66 | 0.8000:1 | [Section](screenshots/feed-maree-fb912b0d--product-carousel.jpg) |
| Marée | `product-carousel` | `home.product_carousel.image_2_alt` | 477.33 × 596.66 | 0.8000:1 | [Section](screenshots/feed-maree-fb912b0d--product-carousel.jpg) |
| Marée | `product-carousel` | `home.product_carousel.image_3_alt` | 477.34 × 596.67 | 0.8000:1 | [Section](screenshots/feed-maree-fb912b0d--product-carousel.jpg) |
| Marée | `product-collection-pair` | `home.product_collection_pair.image_1_alt` | 718.00 × 897.50 | 0.8000:1 | [Section](screenshots/feed-maree-fb912b0d--product-collection-pair.jpg) |
| Marée | `product-collection-pair` | `home.product_collection_pair.image_2_alt` | 718.00 × 897.50 | 0.8000:1 | [Section](screenshots/feed-maree-fb912b0d--product-collection-pair.jpg) |
| Modern Earth | `commerce-product-lineup` | `home.commerce_product_lineup.image_1_alt` | 338.00 × 507.00 | 0.6667:1 | [Section](screenshots/feed-modern-earth-6969d979--commerce-product-lineup.jpg) |
| Modern Earth | `commerce-product-lineup` | `home.commerce_product_lineup.image_2_alt` | 338.00 × 507.00 | 0.6667:1 | [Section](screenshots/feed-modern-earth-6969d979--commerce-product-lineup.jpg) |
| Modern Earth | `commerce-product-lineup` | `home.commerce_product_lineup.image_3_alt` | 338.00 × 507.00 | 0.6667:1 | [Section](screenshots/feed-modern-earth-6969d979--commerce-product-lineup.jpg) |
| Modern Earth | `commerce-product-lineup` | `home.commerce_product_lineup.image_4_alt` | 338.00 × 507.00 | 0.6667:1 | [Section](screenshots/feed-modern-earth-6969d979--commerce-product-lineup.jpg) |
| Modern Earth | `content-asymmetric-resource` | `home.content_asymmetric_resource.image_2_alt` | 456.00 × 684.00 | 0.6667:1 | [Section](screenshots/feed-modern-earth-6969d979--content-asymmetric-resource.jpg) |
| Modern Earth | `cta-asymmetric` | `home.cta_asymmetric.image_2_alt` | 456.00 × 684.00 | 0.6667:1 | [Section](screenshots/feed-modern-earth-6969d979--cta-asymmetric.jpg) |
| Modern Expedition | `content-grid-articles` | `home.content_grid_articles.image_1_alt` | 378.66 × 504.88 | 0.7500:1 | [Section](screenshots/feed-modern-expedition-27be91a3--content-grid-articles.jpg) |
| Modern Expedition | `content-grid-articles` | `home.content_grid_articles.image_2_alt` | 378.67 × 504.89 | 0.7500:1 | [Section](screenshots/feed-modern-expedition-27be91a3--content-grid-articles.jpg) |
| Modern Expedition | `content-grid-articles` | `home.content_grid_articles.image_3_alt` | 378.66 × 504.88 | 0.7500:1 | [Section](screenshots/feed-modern-expedition-27be91a3--content-grid-articles.jpg) |
| Modern Muse | `commerce-product-row` | `home.commerce_product_row.image_1_alt` | 416.00 × 745.33 | 0.5581:1 | [Section](screenshots/feed-modern-muse-22d857ed--commerce-product-row.jpg) |
| Modern Muse | `commerce-product-row` | `home.commerce_product_row.image_2_alt` | 416.00 × 745.33 | 0.5581:1 | [Section](screenshots/feed-modern-muse-22d857ed--commerce-product-row.jpg) |
| Modern Muse | `commerce-product-row` | `home.commerce_product_row.image_3_alt` | 416.00 × 745.33 | 0.5581:1 | [Section](screenshots/feed-modern-muse-22d857ed--commerce-product-row.jpg) |
| Modern Nest | `commerce-bundle-columns` | `home.commerce_bundle_columns.image_1_alt` | 418.66 × 523.31 | 0.8000:1 | [Section](screenshots/feed-modern-nest-5d62c811--commerce-bundle-columns.jpg) |
| Modern Nest | `commerce-bundle-columns` | `home.commerce_bundle_columns.image_2_alt` | 418.67 × 523.33 | 0.8000:1 | [Section](screenshots/feed-modern-nest-5d62c811--commerce-bundle-columns.jpg) |
| Modern Nest | `commerce-bundle-columns` | `home.commerce_bundle_columns.image_3_alt` | 418.66 × 523.31 | 0.8000:1 | [Section](screenshots/feed-modern-nest-5d62c811--commerce-bundle-columns.jpg) |
| Modern Nest | `cta-split` | `home.cta_split.image_1_alt` | 634.00 × 792.50 | 0.8000:1 | [Section](screenshots/feed-modern-nest-5d62c811--cta-split.jpg) |
| Modern Sanctuary | `editorial-caption-tiles` | `home.editorial_caption_tiles.image_1_alt` | 359.25 × 538.88 | 0.6667:1 | [Section](screenshots/feed-modern-sanctuary-cdd9004a--editorial-caption-tiles.jpg) |
| Modern Sanctuary | `editorial-caption-tiles` | `home.editorial_caption_tiles.image_2_alt` | 359.25 × 538.88 | 0.6667:1 | [Section](screenshots/feed-modern-sanctuary-cdd9004a--editorial-caption-tiles.jpg) |
| Modern Sanctuary | `editorial-caption-tiles` | `home.editorial_caption_tiles.image_3_alt` | 359.25 × 538.88 | 0.6667:1 | [Section](screenshots/feed-modern-sanctuary-cdd9004a--editorial-caption-tiles.jpg) |
| Modern Sanctuary | `editorial-caption-tiles` | `home.editorial_caption_tiles.image_4_alt` | 359.25 × 538.88 | 0.6667:1 | [Section](screenshots/feed-modern-sanctuary-cdd9004a--editorial-caption-tiles.jpg) |
| Monochrome Statement | `product-grid-1` | `home.product_grid_1.image_2_alt` | 354.00 × 531.00 | 0.6667:1 | [Section](screenshots/feed-monochrome-statement-664fa55c--product-grid-1.jpg) |
| Monochrome Statement | `product-grid-1` | `home.product_grid_1.image_3_alt` | 354.00 × 531.00 | 0.6667:1 | [Section](screenshots/feed-monochrome-statement-664fa55c--product-grid-1.jpg) |
| Monochrome Statement | `product-grid-1` | `home.product_grid_1.image_4_alt` | 354.00 × 531.00 | 0.6667:1 | [Section](screenshots/feed-monochrome-statement-664fa55c--product-grid-1.jpg) |
| Monochrome Statement | `product-grid-1` | `home.product_grid_1.image_5_alt` | 354.00 × 531.00 | 0.6667:1 | [Section](screenshots/feed-monochrome-statement-664fa55c--product-grid-1.jpg) |
| Monochrome Statement | `product-spotlight` | `home.product_spotlight.image_1_alt` | 960.00 × 720.00 | 1.3333:1 | [Section](screenshots/feed-monochrome-statement-664fa55c--product-spotlight.jpg) |
| murmure | `product-grid-1` | `home.product_grid_1.image_2_alt` | 480.00 × 600.00 | 0.8000:1 | [Section](screenshots/feed-murmure-6f516ba3--product-grid-1.jpg) |
| murmure | `product-grid-1` | `home.product_grid_1.image_3_alt` | 480.00 × 600.00 | 0.8000:1 | [Section](screenshots/feed-murmure-6f516ba3--product-grid-1.jpg) |
| murmure | `product-grid-1` | `home.product_grid_1.image_4_alt` | 480.00 × 600.00 | 0.8000:1 | [Section](screenshots/feed-murmure-6f516ba3--product-grid-1.jpg) |
| murmure | `product-grid-1` | `home.product_grid_1.image_5_alt` | 480.00 × 600.00 | 0.8000:1 | [Section](screenshots/feed-murmure-6f516ba3--product-grid-1.jpg) |
| Neo-Japan Everyday | `features-asymmetric` | `home.features_asymmetric.image_1_alt` | 577.33 × 721.66 | 0.8000:1 | [Section](screenshots/feed-neo-japan-everyday-1beada46--features-asymmetric.jpg) |
| Odile Grey | `cta-columns-image` | `home.cta_columns_image.image_1_alt` | 720.00 × 1000.00 | 0.7200:1 | [Section](screenshots/feed-odile-grey-5db868a6--cta-columns-image.jpg) |
| Odile Grey | `cta-columns-image` | `home.cta_columns_image.image_2_alt` | 720.00 × 1000.00 | 0.7200:1 | [Section](screenshots/feed-odile-grey-5db868a6--cta-columns-image.jpg) |
| Odile Grey | `product-collection-pair` | `home.product_collection_pair.image_1_alt` | 480.00 × 600.00 | 0.8000:1 | [Section](screenshots/feed-odile-grey-5db868a6--product-collection-pair.jpg) |
| Odile Grey | `product-collection-pair` | `home.product_collection_pair.image_2_alt` | 480.00 × 600.00 | 0.8000:1 | [Section](screenshots/feed-odile-grey-5db868a6--product-collection-pair.jpg) |
| Odile Grey | `product-collection-pair` | `home.product_collection_pair.image_3_alt` | 480.00 × 600.00 | 0.8000:1 | [Section](screenshots/feed-odile-grey-5db868a6--product-collection-pair.jpg) |
| ORVENORIA | `commerce-grid` | `home.commerce_grid.image_1_alt` | 308.00 × 410.66 | 0.7500:1 | [Section](screenshots/feed-orvenoria-64caa630--commerce-grid.jpg) |
| ORVENORIA | `commerce-grid` | `home.commerce_grid.image_2_alt` | 308.00 × 410.66 | 0.7500:1 | [Section](screenshots/feed-orvenoria-64caa630--commerce-grid.jpg) |
| ORVENORIA | `commerce-grid` | `home.commerce_grid.image_3_alt` | 308.00 × 410.66 | 0.7500:1 | [Section](screenshots/feed-orvenoria-64caa630--commerce-grid.jpg) |
| ORVENORIA | `commerce-grid` | `home.commerce_grid.image_4_alt` | 308.00 × 410.66 | 0.7500:1 | [Section](screenshots/feed-orvenoria-64caa630--commerce-grid.jpg) |
| ORVENORIA | `commerce-grid` | `home.commerce_grid.image_1_alt` | 302.00 × 377.50 | 0.8000:1 | [Section](screenshots/feed-orvenoria-af7d9e27--commerce-grid.jpg) |
| ORVENORIA | `commerce-grid` | `home.commerce_grid.image_2_alt` | 302.00 × 377.50 | 0.8000:1 | [Section](screenshots/feed-orvenoria-af7d9e27--commerce-grid.jpg) |
| ORVENORIA | `commerce-grid` | `home.commerce_grid.image_3_alt` | 302.00 × 377.50 | 0.8000:1 | [Section](screenshots/feed-orvenoria-af7d9e27--commerce-grid.jpg) |
| ORVENORIA | `commerce-grid` | `home.commerce_grid.image_4_alt` | 302.00 × 377.50 | 0.8000:1 | [Section](screenshots/feed-orvenoria-af7d9e27--commerce-grid.jpg) |
| ORVENORIA | `product-carousel` | `home.product_carousel.image_1_alt` | 305.00 × 381.25 | 0.8000:1 | [Section](screenshots/feed-orvenoria-af7d9e27--product-carousel.jpg) |
| ORVENORIA | `product-carousel` | `home.product_carousel.image_2_alt` | 305.00 × 381.25 | 0.8000:1 | [Section](screenshots/feed-orvenoria-af7d9e27--product-carousel.jpg) |
| ORVENORIA | `product-carousel` | `home.product_carousel.image_3_alt` | 305.00 × 381.25 | 0.8000:1 | [Section](screenshots/feed-orvenoria-af7d9e27--product-carousel.jpg) |
| Parallax | `product-grid-1` | `home.product_grid_1.image_2_alt` | 311.00 × 388.75 | 0.8000:1 | [Section](screenshots/feed-parallax-32540ff0--product-grid-1.jpg) |
| Parallax | `product-grid-1` | `home.product_grid_1.image_3_alt` | 311.00 × 388.75 | 0.8000:1 | [Section](screenshots/feed-parallax-32540ff0--product-grid-1.jpg) |
| Parallax | `product-grid-1` | `home.product_grid_1.image_4_alt` | 311.00 × 388.75 | 0.8000:1 | [Section](screenshots/feed-parallax-32540ff0--product-grid-1.jpg) |
| Parallax | `product-grid-1` | `home.product_grid_1.image_5_alt` | 311.00 × 388.75 | 0.8000:1 | [Section](screenshots/feed-parallax-32540ff0--product-grid-1.jpg) |
| pipkin | `commerce-bundle-columns` | `home.commerce_bundle_columns.image_1_alt` | 280.00 × 350.00 | 0.8000:1 | [Section](screenshots/feed-pipkin-9a94d0f0--commerce-bundle-columns.jpg) |
| pipkin | `commerce-bundle-columns` | `home.commerce_bundle_columns.image_2_alt` | 280.00 × 350.00 | 0.8000:1 | [Section](screenshots/feed-pipkin-9a94d0f0--commerce-bundle-columns.jpg) |
| pipkin | `commerce-bundle-columns` | `home.commerce_bundle_columns.image_3_alt` | 280.00 × 350.00 | 0.8000:1 | [Section](screenshots/feed-pipkin-9a94d0f0--commerce-bundle-columns.jpg) |
| pipkin | `commerce-bundle-columns` | `home.commerce_bundle_columns.image_4_alt` | 280.00 × 350.00 | 0.8000:1 | [Section](screenshots/feed-pipkin-9a94d0f0--commerce-bundle-columns.jpg) |
| pipkin | `content-split-howto` | `home.content_split_howto.image_1_alt` | 526.00 × 657.50 | 0.8000:1 | [Section](screenshots/feed-pipkin-9a94d0f0--content-split-howto.jpg) |
| Plain Stock | `product-carousel` | `home.product_carousel.image_1_alt` | 240.00 × 320.00 | 0.7500:1 | [Section](screenshots/feed-plain-stock-401de08f--product-carousel.jpg) |
| Plain Stock | `product-carousel` | `home.product_carousel.image_2_alt` | 240.00 × 320.00 | 0.7500:1 | [Section](screenshots/feed-plain-stock-401de08f--product-carousel.jpg) |
| Plain Stock | `product-carousel` | `home.product_carousel.image_3_alt` | 240.00 × 320.00 | 0.7500:1 | [Section](screenshots/feed-plain-stock-401de08f--product-carousel.jpg) |
| Plain Stock | `product-carousel` | `home.product_carousel.image_4_alt` | 240.00 × 320.00 | 0.7500:1 | [Section](screenshots/feed-plain-stock-401de08f--product-carousel.jpg) |
| Plain Stock | `product-carousel` | `home.product_carousel.image_5_alt` | 240.00 × 320.00 | 0.7500:1 | [Section](screenshots/feed-plain-stock-401de08f--product-carousel.jpg) |
| Playful Function Atelier | `commerce-bundle-columns` | `home.commerce_bundle_columns.image_1_alt` | 690.00 × 576.00 | 1.1979:1 | [Section](screenshots/feed-playful-function-atelier-121b8a99--commerce-bundle-columns.jpg) |
| Playful Function Atelier | `commerce-bundle-columns` | `home.commerce_bundle_columns.image_2_alt` | 335.00 × 576.00 | 0.5816:1 | [Section](screenshots/feed-playful-function-atelier-121b8a99--commerce-bundle-columns.jpg) |
| Playful Function Atelier | `commerce-bundle-columns` | `home.commerce_bundle_columns.image_3_alt` | 335.00 × 576.00 | 0.5816:1 | [Section](screenshots/feed-playful-function-atelier-121b8a99--commerce-bundle-columns.jpg) |
| Playful Green Utility | `hero-mixed-type-strip` | `home.hero_mixed_type_strip.image_1_alt` | 311.00 × 388.75 | 0.8000:1 | [Section](screenshots/feed-playful-green-utility-ca58e492--hero-mixed-type-strip.jpg) |
| Playful Green Utility | `hero-mixed-type-strip` | `home.hero_mixed_type_strip.image_2_alt` | 311.00 × 388.75 | 0.8000:1 | [Section](screenshots/feed-playful-green-utility-ca58e492--hero-mixed-type-strip.jpg) |
| Playful Green Utility | `hero-mixed-type-strip` | `home.hero_mixed_type_strip.image_3_alt` | 311.00 × 388.75 | 0.8000:1 | [Section](screenshots/feed-playful-green-utility-ca58e492--hero-mixed-type-strip.jpg) |
| Playful Green Utility | `hero-mixed-type-strip` | `home.hero_mixed_type_strip.image_4_alt` | 311.00 × 388.75 | 0.8000:1 | [Section](screenshots/feed-playful-green-utility-ca58e492--hero-mixed-type-strip.jpg) |
| Precision in Detail | `cta-asymmetric` | `home.cta_asymmetric.image_3_alt` | 238.00 × 396.66 | 0.6000:1 | [Section](screenshots/feed-precision-in-detail-b51839a8--cta-asymmetric.jpg) |
| Precision in Detail | `editorial-sidebar` | `home.editorial_sidebar.image_1_alt` | 378.00 × 630.00 | 0.6000:1 | [Section](screenshots/feed-precision-in-detail-b51839a8--editorial-sidebar.jpg) |
| Precision in Detail | `editorial-sidebar` | `home.editorial_sidebar.image_2_alt` | 294.00 × 490.00 | 0.6000:1 | [Section](screenshots/feed-precision-in-detail-b51839a8--editorial-sidebar.jpg) |
| Precision in Detail | `editorial-sidebar` | `home.editorial_sidebar.image_3_alt` | 294.00 × 490.00 | 0.6000:1 | [Section](screenshots/feed-precision-in-detail-b51839a8--editorial-sidebar.jpg) |
| Precision in Detail | `editorial-sidebar` | `home.editorial_sidebar.image_4_alt` | 378.00 × 630.00 | 0.6000:1 | [Section](screenshots/feed-precision-in-detail-b51839a8--editorial-sidebar.jpg) |
| Quiet Precision | `commerce-product-lineup` | `home.commerce_product_lineup.image_1_alt` | 296.00 × 370.00 | 0.8000:1 | [Section](screenshots/feed-quiet-precision-cfbde3ce--commerce-product-lineup.jpg) |
| Quiet Precision | `commerce-product-lineup` | `home.commerce_product_lineup.image_2_alt` | 296.00 × 370.00 | 0.8000:1 | [Section](screenshots/feed-quiet-precision-cfbde3ce--commerce-product-lineup.jpg) |
| Quiet Precision | `commerce-product-lineup` | `home.commerce_product_lineup.image_3_alt` | 296.00 × 370.00 | 0.8000:1 | [Section](screenshots/feed-quiet-precision-cfbde3ce--commerce-product-lineup.jpg) |
| Quiet Precision | `commerce-product-lineup` | `home.commerce_product_lineup.image_4_alt` | 296.00 × 370.00 | 0.8000:1 | [Section](screenshots/feed-quiet-precision-cfbde3ce--commerce-product-lineup.jpg) |
| Quiet Precision | `product-color-panel` | `home.product_color_panel.image_1_alt` | 853.33 × 600.00 | 1.4222:1 | [Section](screenshots/feed-quiet-precision-cfbde3ce--product-color-panel.jpg) |
| RadiantCurve Collective | `commerce-grid` | `home.commerce_grid.image_1_alt` | 305.00 × 381.25 | 0.8000:1 | [Section](screenshots/feed-radiantcurve-collective-2f845859--commerce-grid.jpg) |
| RadiantCurve Collective | `commerce-grid` | `home.commerce_grid.image_2_alt` | 305.00 × 381.25 | 0.8000:1 | [Section](screenshots/feed-radiantcurve-collective-2f845859--commerce-grid.jpg) |
| RadiantCurve Collective | `commerce-grid` | `home.commerce_grid.image_3_alt` | 305.00 × 381.25 | 0.8000:1 | [Section](screenshots/feed-radiantcurve-collective-2f845859--commerce-grid.jpg) |
| RadiantCurve Collective | `commerce-grid` | `home.commerce_grid.image_4_alt` | 305.00 × 381.25 | 0.8000:1 | [Section](screenshots/feed-radiantcurve-collective-2f845859--commerce-grid.jpg) |
| Rally Club | `commerce-bundle-columns` | `home.commerce_bundle_columns.image_1_alt` | 320.00 × 426.66 | 0.7500:1 | [Section](screenshots/feed-rally-club-0f8d8efd--commerce-bundle-columns.jpg) |
| Rally Club | `commerce-bundle-columns` | `home.commerce_bundle_columns.image_2_alt` | 320.00 × 426.66 | 0.7500:1 | [Section](screenshots/feed-rally-club-0f8d8efd--commerce-bundle-columns.jpg) |
| Rally Club | `commerce-bundle-columns` | `home.commerce_bundle_columns.image_3_alt` | 320.00 × 426.66 | 0.7500:1 | [Section](screenshots/feed-rally-club-0f8d8efd--commerce-bundle-columns.jpg) |
| Rally Club | `commerce-bundle-columns` | `home.commerce_bundle_columns.image_4_alt` | 320.00 × 426.66 | 0.7500:1 | [Section](screenshots/feed-rally-club-0f8d8efd--commerce-bundle-columns.jpg) |
| Ricrac | `product-carousel` | `home.product_carousel.image_1_alt` | 277.69 × 370.25 | 0.7500:1 | [Section](screenshots/feed-ricrac-4ecc6a74--product-carousel.jpg) |
| Ricrac | `product-carousel` | `home.product_carousel.image_2_alt` | 277.69 × 370.25 | 0.7500:1 | [Section](screenshots/feed-ricrac-4ecc6a74--product-carousel.jpg) |
| Ricrac | `product-carousel` | `home.product_carousel.image_3_alt` | 277.69 × 370.25 | 0.7500:1 | [Section](screenshots/feed-ricrac-4ecc6a74--product-carousel.jpg) |
| Ricrac | `product-carousel` | `home.product_carousel.image_4_alt` | 277.69 × 370.25 | 0.7500:1 | [Section](screenshots/feed-ricrac-4ecc6a74--product-carousel.jpg) |
| Ricrac | `product-carousel` | `home.product_carousel.image_5_alt` | 277.69 × 370.25 | 0.7500:1 | [Section](screenshots/feed-ricrac-4ecc6a74--product-carousel.jpg) |
| Ricrac | `product-carousel` | `home.product_carousel.image_6_alt` | 277.69 × 370.25 | 0.7500:1 | [Section](screenshots/feed-ricrac-4ecc6a74--product-carousel.jpg) |
| rillen.berlin | `commerce-product-row` | `home.commerce_product_row.image_1_alt` | 474.66 × 569.58 | 0.8333:1 | [Section](screenshots/feed-rillen-berlin-e3fea2a2--commerce-product-row.jpg) |
| rillen.berlin | `commerce-product-row` | `home.commerce_product_row.image_2_alt` | 474.67 × 569.59 | 0.8334:1 | [Section](screenshots/feed-rillen-berlin-e3fea2a2--commerce-product-row.jpg) |
| rillen.berlin | `commerce-product-row` | `home.commerce_product_row.image_3_alt` | 474.66 × 569.58 | 0.8333:1 | [Section](screenshots/feed-rillen-berlin-e3fea2a2--commerce-product-row.jpg) |
| rillen.berlin | `commerce-split` | `home.commerce_split.image_1_alt` | 1008.00 × 700.00 | 1.4400:1 | [Section](screenshots/feed-rillen-berlin-e3fea2a2--commerce-split.jpg) |
| Ruelle | `product-tile-grid` | `home.product_tile_grid.image_1_alt` | 359.00 × 480.00 | 0.7479:1 | [Section](screenshots/feed-ruelle-38248a43--product-tile-grid.jpg) |
| Ruelle | `product-tile-grid` | `home.product_tile_grid.image_2_alt` | 359.00 × 480.00 | 0.7479:1 | [Section](screenshots/feed-ruelle-38248a43--product-tile-grid.jpg) |
| Ruelle | `product-tile-grid` | `home.product_tile_grid.image_3_alt` | 359.00 × 480.00 | 0.7479:1 | [Section](screenshots/feed-ruelle-38248a43--product-tile-grid.jpg) |
| Ruelle | `product-tile-grid` | `home.product_tile_grid.image_4_alt` | 360.00 × 480.00 | 0.7500:1 | [Section](screenshots/feed-ruelle-38248a43--product-tile-grid.jpg) |
| Sable Sanctuary | `features-grid-mixed` | `home.features_grid_mixed.image_1_alt` | 256.00 × 256.00 | 1.0000:1 | [Section](screenshots/feed-sable-sanctuary-cbcb73c3--features-grid-mixed.jpg) |
| Sable Sanctuary | `features-grid-mixed` | `home.features_grid_mixed.image_2_alt` | 256.00 × 256.00 | 1.0000:1 | [Section](screenshots/feed-sable-sanctuary-cbcb73c3--features-grid-mixed.jpg) |
| Sable Sanctuary | `features-grid-mixed` | `home.features_grid_mixed.image_3_alt` | 256.00 × 256.00 | 1.0000:1 | [Section](screenshots/feed-sable-sanctuary-cbcb73c3--features-grid-mixed.jpg) |
| Sable Sanctuary | `product-offer-pair` | `home.product_offer_pair.image_1_alt` | 676.00 × 811.19 | 0.8333:1 | [Section](screenshots/feed-sable-sanctuary-cbcb73c3--product-offer-pair.jpg) |
| Sable Sanctuary | `product-offer-pair` | `home.product_offer_pair.image_2_alt` | 676.00 × 811.19 | 0.8333:1 | [Section](screenshots/feed-sable-sanctuary-cbcb73c3--product-offer-pair.jpg) |
| Sable Sanctuary | `product-split-1` | `home.product_split_1.image_1_alt` | 300.00 × 375.00 | 0.8000:1 | [Section](screenshots/feed-sable-sanctuary-cbcb73c3--product-split-1.jpg) |
| Saikhu | `product-collection-pair` | `home.product_collection_pair.image_1_alt` | 534.00 × 640.80 | 0.8333:1 | [Section](screenshots/feed-saikhu-f3c811df--product-collection-pair.jpg) |
| Saikhu | `product-collection-pair` | `home.product_collection_pair.image_2_alt` | 534.00 × 640.80 | 0.8333:1 | [Section](screenshots/feed-saikhu-f3c811df--product-collection-pair.jpg) |
| Saikhu | `product-stacked-1` | `home.product_stacked_1.image_1_alt` | 896.00 × 597.33 | 1.5000:1 | [Section](screenshots/feed-saikhu-f3c811df--product-stacked-1.jpg) |
| Second Pour | `commerce-bundle-columns` | `home.commerce_bundle_columns.image_1_alt` | 76.72 × 102.28 | 0.7501:1 | [Section](screenshots/feed-second-pour-fed58ee8--commerce-bundle-columns.jpg) |
| Second Pour | `commerce-bundle-columns` | `home.commerce_bundle_columns.image_2_alt` | 76.72 × 102.28 | 0.7501:1 | [Section](screenshots/feed-second-pour-fed58ee8--commerce-bundle-columns.jpg) |
| Second Pour | `commerce-bundle-columns` | `home.commerce_bundle_columns.image_3_alt` | 76.72 × 102.28 | 0.7501:1 | [Section](screenshots/feed-second-pour-fed58ee8--commerce-bundle-columns.jpg) |
| Second Pour | `commerce-bundle-columns` | `home.commerce_bundle_columns.image_4_alt` | 76.72 × 102.28 | 0.7501:1 | [Section](screenshots/feed-second-pour-fed58ee8--commerce-bundle-columns.jpg) |
| Serene Sculpted Minimalism | `commerce-product-lineup` | `home.commerce_product_lineup.image_1_alt` | 305.00 × 508.33 | 0.6000:1 | [Section](screenshots/feed-serene-sculpted-minimalism-a78d0625--commerce-product-lineup.jpg) |
| Serene Sculpted Minimalism | `commerce-product-lineup` | `home.commerce_product_lineup.image_2_alt` | 305.00 × 508.33 | 0.6000:1 | [Section](screenshots/feed-serene-sculpted-minimalism-a78d0625--commerce-product-lineup.jpg) |
| Serene Sculpted Minimalism | `commerce-product-lineup` | `home.commerce_product_lineup.image_3_alt` | 305.00 × 508.33 | 0.6000:1 | [Section](screenshots/feed-serene-sculpted-minimalism-a78d0625--commerce-product-lineup.jpg) |
| Serene Sculpted Minimalism | `commerce-product-lineup` | `home.commerce_product_lineup.image_4_alt` | 305.00 × 508.33 | 0.6000:1 | [Section](screenshots/feed-serene-sculpted-minimalism-a78d0625--commerce-product-lineup.jpg) |
| Serene Sculpted Minimalism | `commerce-lookbook` | `home.commerce_lookbook.image_1_alt` | 360.00 × 600.00 | 0.6000:1 | [Section](screenshots/feed-serene-sculpted-minimalism-dd6e696a--commerce-lookbook.jpg) |
| Serene Sculpted Minimalism | `commerce-lookbook` | `home.commerce_lookbook.image_2_alt` | 360.00 × 600.00 | 0.6000:1 | [Section](screenshots/feed-serene-sculpted-minimalism-dd6e696a--commerce-lookbook.jpg) |
| Serene Sculpted Minimalism | `commerce-lookbook` | `home.commerce_lookbook.image_3_alt` | 360.00 × 600.00 | 0.6000:1 | [Section](screenshots/feed-serene-sculpted-minimalism-dd6e696a--commerce-lookbook.jpg) |
| Serene Sculpted Minimalism | `commerce-lookbook` | `home.commerce_lookbook.image_4_alt` | 360.00 × 600.00 | 0.6000:1 | [Section](screenshots/feed-serene-sculpted-minimalism-dd6e696a--commerce-lookbook.jpg) |
| Serene Sculpted Minimalism | `editorial-news-index` | `home.editorial_news_index.image_1_alt` | 64.00 × 64.00 | 1.0000:1 | [Section](screenshots/feed-serene-sculpted-minimalism-dd6e696a--editorial-news-index.jpg) |
| Serene Sculpted Minimalism | `editorial-news-index` | `home.editorial_news_index.image_2_alt` | 64.00 × 64.00 | 1.0000:1 | [Section](screenshots/feed-serene-sculpted-minimalism-dd6e696a--editorial-news-index.jpg) |
| Serene Sculpted Minimalism | `editorial-news-index` | `home.editorial_news_index.image_3_alt` | 64.00 × 64.00 | 1.0000:1 | [Section](screenshots/feed-serene-sculpted-minimalism-dd6e696a--editorial-news-index.jpg) |
| Serene Sculpted Minimalism | `editorial-news-index` | `home.editorial_news_index.image_4_alt` | 64.00 × 64.00 | 1.0000:1 | [Section](screenshots/feed-serene-sculpted-minimalism-dd6e696a--editorial-news-index.jpg) |
| Situ | `product-campaign-banner` | `home.product_campaign_banner.image_1_alt` | 1440.00 × 680.00 | 2.1176:1 | [Section](screenshots/feed-situ-9827b0dc--product-campaign-banner.jpg) |
| Situ | `product-collection-pair` | `home.product_collection_pair.image_1_alt` | 600.00 × 480.00 | 1.2500:1 | [Section](screenshots/feed-situ-9827b0dc--product-collection-pair.jpg) |
| Situ | `product-featured-trio` | `home.product_featured_trio.image_1_alt` | 308.00 × 410.66 | 0.7500:1 | [Section](screenshots/feed-situ-9827b0dc--product-featured-trio.jpg) |
| Situ | `product-featured-trio` | `home.product_featured_trio.image_2_alt` | 308.00 × 410.66 | 0.7500:1 | [Section](screenshots/feed-situ-9827b0dc--product-featured-trio.jpg) |
| Situ | `product-featured-trio` | `home.product_featured_trio.image_3_alt` | 308.00 × 410.66 | 0.7500:1 | [Section](screenshots/feed-situ-9827b0dc--product-featured-trio.jpg) |
| Solé Swim | `commerce-product-index` | `home.commerce_product_index.image_1_alt` | 422.39 × 760.00 | 0.5558:1 | [Section](screenshots/feed-sole-swim-a30204f5--commerce-product-index.jpg) |
| Solé Swim | `commerce-product-index` | `home.commerce_product_index.image_2_alt` | 422.39 × 760.00 | 0.5558:1 | [Section](screenshots/feed-sole-swim-a30204f5--commerce-product-index.jpg) |
| Solé Swim | `commerce-product-index` | `home.commerce_product_index.image_3_alt` | 422.39 × 760.00 | 0.5558:1 | [Section](screenshots/feed-sole-swim-a30204f5--commerce-product-index.jpg) |
| Solé Swim | `commerce-product-index` | `home.commerce_product_index.image_4_alt` | 422.39 × 760.00 | 0.5558:1 | [Section](screenshots/feed-sole-swim-a30204f5--commerce-product-index.jpg) |
| Solé Swim | `cta-overlap` | `home.cta_overlap.image_2_alt` | 402.55 × 503.17 | 0.8000:1 | [Section](screenshots/feed-sole-swim-a30204f5--cta-overlap.jpg) |
| Solé Swim | `product-split-2` | `home.product_split_2.image_1_alt` | 384.00 × 512.00 | 0.7500:1 | [Section](screenshots/feed-sole-swim-a30204f5--product-split-2.jpg) |
| Sonic Haven | `commerce-gallery-carousel` | `home.commerce_gallery_carousel.image_1_alt` | 420.00 × 525.00 | 0.8000:1 | [Section](screenshots/feed-sonic-haven-823fbd22--commerce-gallery-carousel.jpg) |
| Sonic Haven | `commerce-gallery-carousel` | `home.commerce_gallery_carousel.image_2_alt` | 420.00 × 525.00 | 0.8000:1 | [Section](screenshots/feed-sonic-haven-823fbd22--commerce-gallery-carousel.jpg) |
| Sonic Haven | `commerce-gallery-carousel` | `home.commerce_gallery_carousel.image_3_alt` | 420.00 × 525.00 | 0.8000:1 | [Section](screenshots/feed-sonic-haven-823fbd22--commerce-gallery-carousel.jpg) |
| Sonic Haven | `product-color-panel` | `home.product_color_panel.image_1_alt` | 853.33 × 440.00 | 1.9394:1 | [Section](screenshots/feed-sonic-haven-823fbd22--product-color-panel.jpg) |
| Sonic Haven | `commerce-gallery-carousel` | `home.commerce_gallery_carousel.image_1_alt` | 420.00 × 525.00 | 0.8000:1 | [Section](screenshots/feed-sonic-haven-bdf1cbb5--commerce-gallery-carousel.jpg) |
| Sonic Haven | `commerce-gallery-carousel` | `home.commerce_gallery_carousel.image_2_alt` | 420.00 × 525.00 | 0.8000:1 | [Section](screenshots/feed-sonic-haven-bdf1cbb5--commerce-gallery-carousel.jpg) |
| Sonic Haven | `commerce-gallery-carousel` | `home.commerce_gallery_carousel.image_3_alt` | 420.00 × 525.00 | 0.8000:1 | [Section](screenshots/feed-sonic-haven-bdf1cbb5--commerce-gallery-carousel.jpg) |
| Sonic Haven | `product-color-panel` | `home.product_color_panel.image_1_alt` | 853.33 × 440.00 | 1.9394:1 | [Section](screenshots/feed-sonic-haven-bdf1cbb5--product-color-panel.jpg) |
| Sotto | `commerce-product-index` | `home.commerce_product_index.image_1_alt` | 605.44 × 760.00 | 0.7966:1 | [Section](screenshots/feed-sotto-7453b325--commerce-product-index.jpg) |
| Sotto | `commerce-product-index` | `home.commerce_product_index.image_2_alt` | 605.44 × 760.00 | 0.7966:1 | [Section](screenshots/feed-sotto-7453b325--commerce-product-index.jpg) |
| Sotto | `commerce-product-index` | `home.commerce_product_index.image_3_alt` | 605.44 × 760.00 | 0.7966:1 | [Section](screenshots/feed-sotto-7453b325--commerce-product-index.jpg) |
| Sotto | `commerce-product-index` | `home.commerce_product_index.image_4_alt` | 605.44 × 760.00 | 0.7966:1 | [Section](screenshots/feed-sotto-7453b325--commerce-product-index.jpg) |
| Sotto | `commerce-product-index` | `home.commerce_product_index.image_5_alt` | 605.44 × 760.00 | 0.7966:1 | [Section](screenshots/feed-sotto-7453b325--commerce-product-index.jpg) |
| Sotto | `product-split-1` | `home.product_split_1.image_2_alt` | 262.39 × 349.84 | 0.7500:1 | [Section](screenshots/feed-sotto-7453b325--product-split-1.jpg) |
| Sourdine | `commerce-product-row` | `home.commerce_product_row.image_1_alt` | 432.00 × 540.00 | 0.8000:1 | [Section](screenshots/feed-sourdine-485bbec8--commerce-product-row.jpg) |
| Sourdine | `commerce-product-row` | `home.commerce_product_row.image_2_alt` | 432.00 × 540.00 | 0.8000:1 | [Section](screenshots/feed-sourdine-485bbec8--commerce-product-row.jpg) |
| Sourdine | `commerce-product-row` | `home.commerce_product_row.image_3_alt` | 432.00 × 540.00 | 0.8000:1 | [Section](screenshots/feed-sourdine-485bbec8--commerce-product-row.jpg) |
| Studio Stillness | `features-overlap` | `home.features_overlap.image_1_alt` | 1440.00 × 860.00 | 1.6744:1 | [Section](screenshots/feed-studio-stillness-36ce88e0--features-overlap.jpg) |
| Studio Stillness | `product-packshot-pair` | `home.product_packshot_pair.image_1_alt` | 250.55 × 334.06 | 0.7500:1 | [Section](screenshots/feed-studio-stillness-36ce88e0--product-packshot-pair.jpg) |
| Studio Stillness | `product-packshot-pair` | `home.product_packshot_pair.image_2_alt` | 250.55 × 334.06 | 0.7500:1 | [Section](screenshots/feed-studio-stillness-36ce88e0--product-packshot-pair.jpg) |
| Studio Stillness | `product-ready-to-wear` | `home.product_ready_to_wear.image_1_alt` | 437.33 × 583.09 | 0.7500:1 | [Section](screenshots/feed-studio-stillness-36ce88e0--product-ready-to-wear.jpg) |
| Studio Stillness | `product-ready-to-wear` | `home.product_ready_to_wear.image_2_alt` | 437.33 × 583.09 | 0.7500:1 | [Section](screenshots/feed-studio-stillness-36ce88e0--product-ready-to-wear.jpg) |
| Studio Stillness | `product-ready-to-wear` | `home.product_ready_to_wear.image_3_alt` | 437.34 × 583.12 | 0.7500:1 | [Section](screenshots/feed-studio-stillness-36ce88e0--product-ready-to-wear.jpg) |
| Sunlit Craft | `hero-staggered-serif` | `home.hero_staggered_serif.image_1_alt` | 1440.00 × 708.44 | 2.0326:1 | [Section](screenshots/feed-sunlit-craft-013f7a6e--hero-staggered-serif.jpg) |
| Sunlit Craft | `product-finish-variants` | `home.product_finish_variants.image_1_alt` | 215.62 × 269.53 | 0.8000:1 | [Section](screenshots/feed-sunlit-craft-013f7a6e--product-finish-variants.jpg) |
| Sunlit Craft | `product-finish-variants` | `home.product_finish_variants.image_2_alt` | 215.62 × 269.53 | 0.8000:1 | [Section](screenshots/feed-sunlit-craft-013f7a6e--product-finish-variants.jpg) |
| Sunlit Craft | `product-finish-variants` | `home.product_finish_variants.image_3_alt` | 215.62 × 269.53 | 0.8000:1 | [Section](screenshots/feed-sunlit-craft-013f7a6e--product-finish-variants.jpg) |
| Sunlit Craft | `product-finish-variants` | `home.product_finish_variants.image_4_alt` | 215.62 × 269.53 | 0.8000:1 | [Section](screenshots/feed-sunlit-craft-013f7a6e--product-finish-variants.jpg) |
| The Archivist’s Atelier | `product-featured-trio` | `home.product_featured_trio.image_1_alt` | 350.66 × 438.31 | 0.8000:1 | [Section](screenshots/feed-the-archivist-s-atelier-3c245f74--product-featured-trio.jpg) |
| The Archivist’s Atelier | `product-featured-trio` | `home.product_featured_trio.image_2_alt` | 350.67 × 438.33 | 0.8000:1 | [Section](screenshots/feed-the-archivist-s-atelier-3c245f74--product-featured-trio.jpg) |
| The Archivist’s Atelier | `product-featured-trio` | `home.product_featured_trio.image_3_alt` | 350.66 × 438.31 | 0.8000:1 | [Section](screenshots/feed-the-archivist-s-atelier-3c245f74--product-featured-trio.jpg) |
| The Rehearsal Room | `commerce-product-row` | `home.commerce_product_row.image_1_alt` | 479.33 × 599.17 | 0.8000:1 | [Section](screenshots/feed-the-rehearsal-room-ac54d970--commerce-product-row.jpg) |
| The Rehearsal Room | `commerce-product-row` | `home.commerce_product_row.image_2_alt` | 479.33 × 599.17 | 0.8000:1 | [Section](screenshots/feed-the-rehearsal-room-ac54d970--commerce-product-row.jpg) |
| The Rehearsal Room | `commerce-product-row` | `home.commerce_product_row.image_3_alt` | 479.34 × 599.17 | 0.8000:1 | [Section](screenshots/feed-the-rehearsal-room-ac54d970--commerce-product-row.jpg) |
| The Rehearsal Room | `content-stacked-statement` | `home.content_stacked_statement.image_1_alt` | 1440.00 × 900.00 | 1.6000:1 | [Section](screenshots/feed-the-rehearsal-room-ac54d970--content-stacked-statement.jpg) |
| The Scented Atelier | `commerce-split` | `home.commerce_split.image_1_alt` | 720.00 × 704.00 | 1.0227:1 | [Section](screenshots/feed-the-scented-atelier-a895c870--commerce-split.jpg) |
| The Scented Atelier | `product-featured-trio` | `home.product_featured_trio.image_1_alt` | 416.00 × 624.00 | 0.6667:1 | [Section](screenshots/feed-the-scented-atelier-a895c870--product-featured-trio.jpg) |
| The Scented Atelier | `product-featured-trio` | `home.product_featured_trio.image_2_alt` | 416.00 × 624.00 | 0.6667:1 | [Section](screenshots/feed-the-scented-atelier-a895c870--product-featured-trio.jpg) |
| The Scented Atelier | `product-featured-trio` | `home.product_featured_trio.image_3_alt` | 416.00 × 624.00 | 0.6667:1 | [Section](screenshots/feed-the-scented-atelier-a895c870--product-featured-trio.jpg) |
| Trail Stories: In Motion | `product-tile-grid` | `home.product_tile_grid.image_1_alt` | 329.00 × 438.66 | 0.7500:1 | [Section](screenshots/feed-trail-stories-in-motion-90190a52--product-tile-grid.jpg) |
| Trail Stories: In Motion | `product-tile-grid` | `home.product_tile_grid.image_2_alt` | 329.00 × 438.66 | 0.7500:1 | [Section](screenshots/feed-trail-stories-in-motion-90190a52--product-tile-grid.jpg) |
| Trail Stories: In Motion | `product-tile-grid` | `home.product_tile_grid.image_3_alt` | 329.00 × 438.66 | 0.7500:1 | [Section](screenshots/feed-trail-stories-in-motion-90190a52--product-tile-grid.jpg) |
| Trail Stories: In Motion | `product-tile-grid` | `home.product_tile_grid.image_4_alt` | 329.00 × 438.66 | 0.7500:1 | [Section](screenshots/feed-trail-stories-in-motion-90190a52--product-tile-grid.jpg) |
| Urban Phantom | `content-grid-articles` | `home.content_grid_articles.image_1_alt` | 361.33 × 451.66 | 0.8000:1 | [Section](screenshots/feed-urban-phantom-709c8612--content-grid-articles.jpg) |
| Urban Phantom | `content-grid-articles` | `home.content_grid_articles.image_2_alt` | 361.33 × 451.66 | 0.8000:1 | [Section](screenshots/feed-urban-phantom-709c8612--content-grid-articles.jpg) |
| Urban Phantom | `content-grid-articles` | `home.content_grid_articles.image_3_alt` | 361.34 × 451.67 | 0.8000:1 | [Section](screenshots/feed-urban-phantom-709c8612--content-grid-articles.jpg) |
| Urban Phantom | `product-split-2` | `home.product_split_2.image_1_alt` | 608.00 × 760.00 | 0.8000:1 | [Section](screenshots/feed-urban-phantom-709c8612--product-split-2.jpg) |
| Vintage Birdy | `product-carousel` | `home.product_carousel.image_1_alt` | 413.33 × 516.66 | 0.8000:1 | [Section](screenshots/feed-vintage-birdy-e5914231--product-carousel.jpg) |
| Vintage Birdy | `product-carousel` | `home.product_carousel.image_2_alt` | 413.33 × 516.66 | 0.8000:1 | [Section](screenshots/feed-vintage-birdy-e5914231--product-carousel.jpg) |
| Vintage Birdy | `product-carousel` | `home.product_carousel.image_3_alt` | 413.34 × 516.67 | 0.8000:1 | [Section](screenshots/feed-vintage-birdy-e5914231--product-carousel.jpg) |
| Vintage Birdy | `product-stacked-1` | `home.product_stacked_1.image_1_alt` | 768.00 × 576.00 | 1.3333:1 | [Section](screenshots/feed-vintage-birdy-e5914231--product-stacked-1.jpg) |
| Waveform | `content-split-howto` | `home.content_split_howto.image_1_alt` | 555.00 × 693.75 | 0.8000:1 | [Section](screenshots/feed-waveform-3d17fa10--content-split-howto.jpg) |
| Waveform | `hero-mixed-type-strip` | `home.hero_mixed_type_strip.image_1_alt` | 332.50 × 595.72 | 0.5581:1 | [Section](screenshots/feed-waveform-3d17fa10--hero-mixed-type-strip.jpg) |
| Waveform | `hero-mixed-type-strip` | `home.hero_mixed_type_strip.image_2_alt` | 332.50 × 595.72 | 0.5581:1 | [Section](screenshots/feed-waveform-3d17fa10--hero-mixed-type-strip.jpg) |
| Waveform | `hero-mixed-type-strip` | `home.hero_mixed_type_strip.image_3_alt` | 332.50 × 595.72 | 0.5581:1 | [Section](screenshots/feed-waveform-3d17fa10--hero-mixed-type-strip.jpg) |
| Waveform | `hero-mixed-type-strip` | `home.hero_mixed_type_strip.image_4_alt` | 332.50 × 595.72 | 0.5581:1 | [Section](screenshots/feed-waveform-3d17fa10--hero-mixed-type-strip.jpg) |
| Waymark Supply Co. | `commerce-grid` | `home.commerce_grid.image_1_alt` | 305.00 × 381.25 | 0.8000:1 | [Section](screenshots/feed-waymark-supply-co-20f6199d--commerce-grid.jpg) |
| Waymark Supply Co. | `commerce-grid` | `home.commerce_grid.image_2_alt` | 305.00 × 381.25 | 0.8000:1 | [Section](screenshots/feed-waymark-supply-co-20f6199d--commerce-grid.jpg) |
| Waymark Supply Co. | `commerce-grid` | `home.commerce_grid.image_3_alt` | 305.00 × 381.25 | 0.8000:1 | [Section](screenshots/feed-waymark-supply-co-20f6199d--commerce-grid.jpg) |
| Waymark Supply Co. | `commerce-grid` | `home.commerce_grid.image_4_alt` | 305.00 × 381.25 | 0.8000:1 | [Section](screenshots/feed-waymark-supply-co-20f6199d--commerce-grid.jpg) |
| Waymark Supply Co. | `product-carousel` | `home.product_carousel.image_1_alt` | 305.00 × 381.25 | 0.8000:1 | [Section](screenshots/feed-waymark-supply-co-20f6199d--product-carousel.jpg) |
| Waymark Supply Co. | `product-carousel` | `home.product_carousel.image_2_alt` | 305.00 × 381.25 | 0.8000:1 | [Section](screenshots/feed-waymark-supply-co-20f6199d--product-carousel.jpg) |
| Waymark Supply Co. | `product-carousel` | `home.product_carousel.image_3_alt` | 305.00 × 381.25 | 0.8000:1 | [Section](screenshots/feed-waymark-supply-co-20f6199d--product-carousel.jpg) |
| Waymark Supply Co. | `product-split-2` | `home.product_split_2.image_1_alt` | 700.00 × 333.22 | 2.1007:1 | [Section](screenshots/feed-waymark-supply-co-20f6199d--product-split-2.jpg) |
| Wingtip Coffee Co. | `editorial-sidebar` | `home.editorial_sidebar.image_1_alt` | 458.66 × 573.31 | 0.8000:1 | [Section](screenshots/feed-wingtip-coffee-co-5fd54365--editorial-sidebar.jpg) |
| Wingtip Coffee Co. | `editorial-sidebar` | `home.editorial_sidebar.image_2_alt` | 458.66 × 573.31 | 0.8000:1 | [Section](screenshots/feed-wingtip-coffee-co-5fd54365--editorial-sidebar.jpg) |
| Wingtip Coffee Co. | `product-featured-trio` | `home.product_featured_trio.image_1_alt` | 696.00 × 870.00 | 0.8000:1 | [Section](screenshots/feed-wingtip-coffee-co-5fd54365--product-featured-trio.jpg) |
| Wingtip Coffee Co. | `product-featured-trio` | `home.product_featured_trio.image_2_alt` | 340.00 × 453.33 | 0.7500:1 | [Section](screenshots/feed-wingtip-coffee-co-5fd54365--product-featured-trio.jpg) |
| Wingtip Coffee Co. | `product-featured-trio` | `home.product_featured_trio.image_3_alt` | 340.00 × 453.33 | 0.7500:1 | [Section](screenshots/feed-wingtip-coffee-co-5fd54365--product-featured-trio.jpg) |
| Wonderworks Studio | `commerce-product-lineup` | `home.commerce_product_lineup.image_1_alt` | 329.00 × 411.25 | 0.8000:1 | [Section](screenshots/feed-wonderworks-studio-ad24704d--commerce-product-lineup.jpg) |
| Wonderworks Studio | `commerce-product-lineup` | `home.commerce_product_lineup.image_2_alt` | 329.00 × 411.25 | 0.8000:1 | [Section](screenshots/feed-wonderworks-studio-ad24704d--commerce-product-lineup.jpg) |
| Wonderworks Studio | `commerce-product-lineup` | `home.commerce_product_lineup.image_3_alt` | 329.00 × 411.25 | 0.8000:1 | [Section](screenshots/feed-wonderworks-studio-ad24704d--commerce-product-lineup.jpg) |
| Wonderworks Studio | `commerce-product-lineup` | `home.commerce_product_lineup.image_4_alt` | 329.00 × 411.25 | 0.8000:1 | [Section](screenshots/feed-wonderworks-studio-ad24704d--commerce-product-lineup.jpg) |
| Work/Life Curated | `commerce-grid` | `home.commerce_grid.image_1_alt` | 311.00 × 388.75 | 0.8000:1 | [Section](screenshots/feed-work-life-curated-d6bf2fc9--commerce-grid.jpg) |
| Work/Life Curated | `commerce-grid` | `home.commerce_grid.image_2_alt` | 311.00 × 388.75 | 0.8000:1 | [Section](screenshots/feed-work-life-curated-d6bf2fc9--commerce-grid.jpg) |
| Work/Life Curated | `commerce-grid` | `home.commerce_grid.image_3_alt` | 311.00 × 388.75 | 0.8000:1 | [Section](screenshots/feed-work-life-curated-d6bf2fc9--commerce-grid.jpg) |
| Work/Life Curated | `commerce-grid` | `home.commerce_grid.image_4_alt` | 311.00 × 388.75 | 0.8000:1 | [Section](screenshots/feed-work-life-curated-d6bf2fc9--commerce-grid.jpg) |
| Woven Journeys | `commerce-product-index` | `home.commerce_product_index.image_1_alt` | 336.00 × 504.00 | 0.6667:1 | [Section](screenshots/feed-woven-journeys-9bb09915--commerce-product-index.jpg) |
| Woven Journeys | `commerce-product-index` | `home.commerce_product_index.image_2_alt` | 336.00 × 504.00 | 0.6667:1 | [Section](screenshots/feed-woven-journeys-9bb09915--commerce-product-index.jpg) |
| Woven Journeys | `commerce-product-index` | `home.commerce_product_index.image_3_alt` | 336.00 × 504.00 | 0.6667:1 | [Section](screenshots/feed-woven-journeys-9bb09915--commerce-product-index.jpg) |
| Woven Journeys | `commerce-product-index` | `home.commerce_product_index.image_4_alt` | 336.00 × 504.00 | 0.6667:1 | [Section](screenshots/feed-woven-journeys-9bb09915--commerce-product-index.jpg) |
| Woven Journeys | `commerce-product-index` | `home.commerce_product_index.image_5_alt` | 336.00 × 504.00 | 0.6667:1 | [Section](screenshots/feed-woven-journeys-9bb09915--commerce-product-index.jpg) |
| Zenith Motion | `product-carousel` | `home.product_carousel.image_1_alt` | 305.00 × 381.25 | 0.8000:1 | [Section](screenshots/feed-zenith-motion-bb81c54d--product-carousel.jpg) |
| Zenith Motion | `product-carousel` | `home.product_carousel.image_2_alt` | 305.00 × 381.25 | 0.8000:1 | [Section](screenshots/feed-zenith-motion-bb81c54d--product-carousel.jpg) |
| Zenith Motion | `product-carousel` | `home.product_carousel.image_3_alt` | 305.00 × 381.25 | 0.8000:1 | [Section](screenshots/feed-zenith-motion-bb81c54d--product-carousel.jpg) |
