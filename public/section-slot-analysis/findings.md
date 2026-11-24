# Rendered other image slots at 1440px

Measured 278/278 eligible image slots in 162/162 image sections; 97/97 themes processed. Local revision `7aef0b0db4024e9b69b8643c3a35d7b2164113d0`.

Live local Storefront Renderer, latest local theme rebuilt before capture. Fresh browser context per theme. CSS viewport 1440×1000, device scale factor 1, reduced motion. Untransformed outer wrapper CSS border box; when no separate wrapper defines the slot, untransformed in-flow CSS layout box. Decorative card rotations do not change the reported slot aspect ratio. No intrinsic image sizes or image transforms used. Ratios are width/height. Distribution groups to two decimal places; exact fractional CSS pixels retained.

This audit excludes hero sections and product-selling sections. Editorial, brand, category, lifestyle, and image-bearing footer sections remain included. Repeated slots count individually; theme counts distinguish broad reuse from repetition within one theme.

## Most common measured outer-slot ratios

| Measured W:H, rounded to 0.01 | Slots | Themes | Sections |
|---|---:|---:|---:|
| 0.80:1 | 70 | 26 | 30 |
| 1.00:1 | 32 | 15 | 15 |
| 1.33:1 | 22 | 13 | 14 |
| 0.75:1 | 21 | 8 | 10 |
| 1.78:1 | 13 | 13 | 13 |
| 0.83:1 | 10 | 7 | 7 |
| 1.50:1 | 9 | 4 | 4 |
| 1.60:1 | 9 | 5 | 6 |
| 2.00:1 | 8 | 8 | 8 |
| 2.33:1 | 7 | 7 | 7 |
| 0.86:1 | 7 | 5 | 5 |
| 1.67:1 | 6 | 4 | 6 |
| 0.71:1 | 4 | 2 | 2 |
| 1.29:1 | 3 | 3 | 3 |
| 0.67:1 | 3 | 1 | 1 |
| 0.87:1 | 3 | 3 | 3 |
| 0.63:1 | 3 | 1 | 1 |
| 1.45:1 | 3 | 3 | 3 |
| 1.85:1 | 2 | 2 | 2 |
| 1.52:1 | 2 | 1 | 1 |
| 2.40:1 | 2 | 2 | 2 |
| 1.76:1 | 2 | 2 | 2 |
| 0.37:1 | 2 | 1 | 1 |
| 2.57:1 | 2 | 2 | 2 |
| 1.14:1 | 2 | 1 | 1 |
| 1.18:1 | 2 | 2 | 2 |
| 1.22:1 | 1 | 1 | 1 |
| 2.28:1 | 1 | 1 | 1 |
| 1.07:1 | 1 | 1 | 1 |
| 1.12:1 | 1 | 1 | 1 |
| 0.65:1 | 1 | 1 | 1 |
| 0.92:1 | 1 | 1 | 1 |
| 0.98:1 | 1 | 1 | 1 |
| 1.40:1 | 1 | 1 | 1 |
| 1.41:1 | 1 | 1 | 1 |
| 1.06:1 | 1 | 1 | 1 |
| 1.11:1 | 1 | 1 | 1 |
| 1.24:1 | 1 | 1 | 1 |
| 1.56:1 | 1 | 1 | 1 |
| 2.06:1 | 1 | 1 | 1 |
| 3.00:1 | 1 | 1 | 1 |
| 1.38:1 | 1 | 1 | 1 |
| 1.47:1 | 1 | 1 | 1 |
| 2.12:1 | 1 | 1 | 1 |
| 2.77:1 | 1 | 1 | 1 |
| 0.90:1 | 1 | 1 | 1 |
| 2.38:1 | 1 | 1 | 1 |
| 1.23:1 | 1 | 1 | 1 |
| 4.57:1 | 1 | 1 | 1 |
| 2.32:1 | 1 | 1 | 1 |
| 1.79:1 | 1 | 1 | 1 |
| 1.25:1 | 1 | 1 | 1 |

Measured range: 0.375:1 (Golden Interval / content-stacked-statement) to 4.571:1 (Vintage Birdy / footer-overlap-media). Width-to-height spread: 12.19×.

## Shape families

- Near square: 33 slots (12.0%).
- Portrait: 126 slots (45.8%).
- Landscape: 89 slots (32.4%).
- Wide landscape: 27 slots (9.8%).

Families use W/H thresholds: portrait <0.95; near square 0.95–1.05; landscape >1.05 and <1.90; wide landscape ≥1.90. These are report categories, not theme conventions.

## Image fit and placement

Current browser-computed fit modes are tagged for every measured image. Per-slot tags distinguish absolute image layers from in-flow images, show the active focal position at 1440px, and flag masks, scale/transform rules, and image boxes that differ from the outer slot. Fit and focal position come from browser-computed CSS; positioning and special-effect flags also reference the source rules. The measured outer sizes remain separate.

The element tag (img versus a decorative CSS background) does not itself make a crop safe. Cover fills its own image box and may crop. Contain preserves the entire image in that box and may leave spare space. A shared slot component should expose fit mode and per-image focal point. Keep masks and deliberate zoom as explicit variants.

## Measurement details

Each row identifies the selected outer wrapper and its exact source classes. Browser-computed dimensions resolve the former layout-dependent slots at 1440px. They describe this content/font state at a 1000px-tall viewport; content changes or viewport-height sizing can change the result. Screenshots are fresh section captures, with slot outlines added only by the report viewer. Original saved screenshots are unchanged.

When an in-flow image directly occupies a grid slot with no separate clipping/sizing wrapper, its untransformed CSS layout box defines that slot. This is distinct from intrinsic asset dimensions.

All 97 themes are included in the count table, including themes with zero eligible slots. Product-selling sections are excluded using section identifiers, product metadata, and explicit prices/purchase actions; the complete exclusion inventory is saved in section-slots-1440.json.

## Every measured slot

| Theme | Image section | Slot | Outer size (CSS px) | Measured W:H | Screenshot |
|---|---|---|---|---|---|
| Aero Minimalism | `content-story-tiles` | `home.content_story_tiles.image_1_alt` | 612.00 × 612.00 | 1.0000:1 | [Section](screenshots/feed-aero-minimalism-34e6d992--content-story-tiles.jpg) |
| Aero Minimalism | `content-story-tiles` | `home.content_story_tiles.image_2_alt` | 612.00 × 612.00 | 1.0000:1 | [Section](screenshots/feed-aero-minimalism-34e6d992--content-story-tiles.jpg) |
| Aero Minimalism | `editorial-gallery-grid` | `home.editorial_gallery_grid.image_1_alt` | 329.27 × 411.58 | 0.8000:1 | [Section](screenshots/feed-aero-minimalism-34e6d992--editorial-gallery-grid.jpg) |
| Aero Minimalism | `editorial-gallery-grid` | `home.editorial_gallery_grid.image_2_alt` | 329.28 × 411.59 | 0.8000:1 | [Section](screenshots/feed-aero-minimalism-34e6d992--editorial-gallery-grid.jpg) |
| Aero Minimalism | `editorial-gallery-grid` | `home.editorial_gallery_grid.image_3_alt` | 477.45 × 596.81 | 0.8000:1 | [Section](screenshots/feed-aero-minimalism-34e6d992--editorial-gallery-grid.jpg) |
| Aero Minimalism | `editorial-split` | `home.editorial_split.image_1_alt` | 720.00 × 592.23 | 1.2157:1 | [Section](screenshots/feed-aero-minimalism-34e6d992--editorial-split.jpg) |
| Aero Minimalism | `footer-asymmetric-display` | `layout_footer.image_1_alt` | 294.00 × 392.00 | 0.7500:1 | [Section](screenshots/feed-aero-minimalism-34e6d992--footer-asymmetric-display.jpg) |
| Aero Minimalism | `media-banner` | `home.media_banner.image_1_alt` | 1440.00 × 632.00 | 2.2785:1 | [Section](screenshots/feed-aero-minimalism-34e6d992--media-banner.jpg) |
| Runout | `content-grid-glossary` | `home.content_grid_glossary.image_1_alt` | 584.00 × 438.00 | 1.3333:1 | [Section](screenshots/feed-analog-obsession-d2fc1b43--content-grid-glossary.jpg) |
| Runout | `cta-split-icon` | `home.cta_split_icon.image_1_alt` | 600.00 × 560.00 | 1.0714:1 | [Section](screenshots/feed-analog-obsession-d2fc1b43--cta-split-icon.jpg) |
| Runout | `quote-overlap-image` | `home.quote_overlap_image.image_1_alt` | 1440.00 × 617.14 | 2.3333:1 | [Section](screenshots/feed-analog-obsession-d2fc1b43--quote-overlap-image.jpg) |
| Après Refresh | `cta-split-icon` | `home.cta_split_icon.image_1_alt` | 720.00 × 640.00 | 1.1250:1 | [Section](screenshots/feed-apres-refresh-58387694--cta-split-icon.jpg) |
| Après Refresh | `editorial-cover` | `home.editorial_cover.image_1_alt` | 1440.00 × 617.14 | 2.3333:1 | [Section](screenshots/feed-apres-refresh-58387694--editorial-cover.jpg) |
| Atelier Alegre | `editorial-mosaic` | `home.editorial_mosaic.image_1_alt` | 400.00 × 612.00 | 0.6536:1 | [Section](screenshots/feed-atelier-alegre-b54494bc--editorial-mosaic.jpg) |
| Atelier Alegre | `editorial-mosaic` | `home.editorial_mosaic.image_2_alt` | 294.00 × 294.00 | 1.0000:1 | [Section](screenshots/feed-atelier-alegre-b54494bc--editorial-mosaic.jpg) |
| Atelier Alegre | `editorial-mosaic` | `home.editorial_mosaic.image_3_alt` | 294.00 × 294.00 | 1.0000:1 | [Section](screenshots/feed-atelier-alegre-b54494bc--editorial-mosaic.jpg) |
| Bake Central Pop Studio | `content-stacked-statement` | `home.content_stacked_statement.image_1_alt` | 1440.00 × 617.14 | 2.3333:1 | [Section](screenshots/feed-bake-central-pop-studio-c09d7458--content-stacked-statement.jpg) |
| Bake Central Pop Studio | `cta-columns-image` | `home.cta_columns_image.image_1_alt` | 628.00 × 785.00 | 0.8000:1 | [Section](screenshots/feed-bake-central-pop-studio-c09d7458--cta-columns-image.jpg) |
| Bake Central Pop Studio | `cta-columns-image` | `home.cta_columns_image.image_2_alt` | 628.00 × 785.00 | 0.8000:1 | [Section](screenshots/feed-bake-central-pop-studio-c09d7458--cta-columns-image.jpg) |
| Bake Central Pop Studio | `editorial-caption-banner` | `home.editorial_caption_banner.image_1_alt` | 1440.00 × 780.00 | 1.8462:1 | [Section](screenshots/feed-bake-central-pop-studio-c09d7458--editorial-caption-banner.jpg) |
| Bake Central Pop Studio | `editorial-caption-tiles` | `home.editorial_caption_tiles.image_1_alt` | 311.00 × 388.75 | 0.8000:1 | [Section](screenshots/feed-bake-central-pop-studio-c09d7458--editorial-caption-tiles.jpg) |
| Bake Central Pop Studio | `editorial-caption-tiles` | `home.editorial_caption_tiles.image_2_alt` | 311.00 × 388.75 | 0.8000:1 | [Section](screenshots/feed-bake-central-pop-studio-c09d7458--editorial-caption-tiles.jpg) |
| Bake Central Pop Studio | `editorial-caption-tiles` | `home.editorial_caption_tiles.image_3_alt` | 311.00 × 388.75 | 0.8000:1 | [Section](screenshots/feed-bake-central-pop-studio-c09d7458--editorial-caption-tiles.jpg) |
| Bake Central Pop Studio | `editorial-caption-tiles` | `home.editorial_caption_tiles.image_4_alt` | 311.00 × 388.75 | 0.8000:1 | [Section](screenshots/feed-bake-central-pop-studio-c09d7458--editorial-caption-tiles.jpg) |
| Bold on Every Table | `content-grid-articles` | `home.content_grid_articles.image_1_alt` | 410.66 × 273.77 | 1.5000:1 | [Section](screenshots/feed-bold-on-every-table-4b87b962--content-grid-articles.jpg) |
| Bold on Every Table | `content-grid-articles` | `home.content_grid_articles.image_2_alt` | 410.67 × 273.78 | 1.5000:1 | [Section](screenshots/feed-bold-on-every-table-4b87b962--content-grid-articles.jpg) |
| Bold on Every Table | `content-grid-articles` | `home.content_grid_articles.image_3_alt` | 410.66 × 273.77 | 1.5000:1 | [Section](screenshots/feed-bold-on-every-table-4b87b962--content-grid-articles.jpg) |
| Canvas Bloom Studio | `content-portrait-story` | `home.content_portrait_story.image_1_alt` | 689.38 × 827.25 | 0.8333:1 | [Section](screenshots/feed-canvas-bloom-studio-58769c9d--content-portrait-story.jpg) |
| Canvas Bloom Studio | `features-asymmetric` | `home.features_asymmetric.image_1_alt` | 813.89 × 610.42 | 1.3333:1 | [Section](screenshots/feed-canvas-bloom-studio-58769c9d--features-asymmetric.jpg) |
| Cheerful Pop | `content-split-video` | `home.content_split_video.image_1_alt` | 720.00 × 560.00 | 1.2857:1 | [Section](screenshots/feed-cheerful-pop-ba54b077--content-split-video.jpg) |
| Cheerful Pop | `editorial-magazine-grid` | `home.editorial_magazine_grid.image_1_alt` | 326.66 × 326.66 | 1.0000:1 | [Section](screenshots/feed-cheerful-pop-ba54b077--editorial-magazine-grid.jpg) |
| Cheerful Pop | `editorial-magazine-grid` | `home.editorial_magazine_grid.image_2_alt` | 326.67 × 326.67 | 1.0000:1 | [Section](screenshots/feed-cheerful-pop-ba54b077--editorial-magazine-grid.jpg) |
| Cheerful Pop | `editorial-magazine-grid` | `home.editorial_magazine_grid.image_3_alt` | 326.66 × 326.66 | 1.0000:1 | [Section](screenshots/feed-cheerful-pop-ba54b077--editorial-magazine-grid.jpg) |
| City Sanctuary | `editorial-standfirst-banner` | `home.editorial_standfirst_banner.image_1_alt` | 1420.00 × 608.56 | 2.3334:1 | [Section](screenshots/feed-city-sanctuary-a3408300--editorial-standfirst-banner.jpg) |
| City Sanctuary | `features-stacked` | `home.features_stacked.image_1_alt` | 824.16 × 640.00 | 1.2877:1 | [Section](screenshots/feed-city-sanctuary-a3408300--features-stacked.jpg) |
| City Sanctuary | `features-stacked` | `home.features_stacked.image_2_alt` | 585.83 × 640.00 | 0.9154:1 | [Section](screenshots/feed-city-sanctuary-a3408300--features-stacked.jpg) |
| Common Iron | `content-columns-steps` | `home.content_columns_steps.image_1_alt` | 410.66 × 513.31 | 0.8000:1 | [Section](screenshots/feed-common-iron-c99e3f8d--content-columns-steps.jpg) |
| Common Iron | `content-columns-steps` | `home.content_columns_steps.image_2_alt` | 410.67 × 513.33 | 0.8000:1 | [Section](screenshots/feed-common-iron-c99e3f8d--content-columns-steps.jpg) |
| Common Iron | `content-columns-steps` | `home.content_columns_steps.image_3_alt` | 410.66 × 513.31 | 0.8000:1 | [Section](screenshots/feed-common-iron-c99e3f8d--content-columns-steps.jpg) |
| Common Iron | `cta-columns-image` | `home.cta_columns_image.image_1_alt` | 624.00 × 780.00 | 0.8000:1 | [Section](screenshots/feed-common-iron-c99e3f8d--cta-columns-image.jpg) |
| Common Iron | `cta-columns-image` | `home.cta_columns_image.image_2_alt` | 624.00 × 780.00 | 0.8000:1 | [Section](screenshots/feed-common-iron-c99e3f8d--cta-columns-image.jpg) |
| Common Iron | `editorial-mosaic` | `home.editorial_mosaic.image_1_alt` | 520.00 × 624.00 | 0.8333:1 | [Section](screenshots/feed-common-iron-c99e3f8d--editorial-mosaic.jpg) |
| Common Iron | `editorial-mosaic` | `home.editorial_mosaic.image_2_alt` | 312.00 × 312.00 | 1.0000:1 | [Section](screenshots/feed-common-iron-c99e3f8d--editorial-mosaic.jpg) |
| Common Iron | `editorial-mosaic` | `home.editorial_mosaic.image_3_alt` | 312.00 × 312.00 | 1.0000:1 | [Section](screenshots/feed-common-iron-c99e3f8d--editorial-mosaic.jpg) |
| Common Iron | `editorial-standfirst-banner` | `home.editorial_standfirst_banner.image_1_alt` | 1440.00 × 780.00 | 1.8462:1 | [Section](screenshots/feed-common-iron-c99e3f8d--editorial-standfirst-banner.jpg) |
| Concrete Pulse | `editorial-profile-cards` | `home.editorial_profile_cards.image_1_alt` | 394.66 × 591.98 | 0.6667:1 | [Section](screenshots/feed-concrete-pulse-ca531534--editorial-profile-cards.jpg) |
| Concrete Pulse | `editorial-profile-cards` | `home.editorial_profile_cards.image_2_alt` | 394.67 × 592.00 | 0.6667:1 | [Section](screenshots/feed-concrete-pulse-ca531534--editorial-profile-cards.jpg) |
| Concrete Pulse | `editorial-profile-cards` | `home.editorial_profile_cards.image_3_alt` | 394.66 × 591.98 | 0.6667:1 | [Section](screenshots/feed-concrete-pulse-ca531534--editorial-profile-cards.jpg) |
| Concrete Pulse | `editorial-quote-portrait` | `home.editorial_quote_portrait.image_1_alt` | 720.00 × 832.00 | 0.8654:1 | [Section](screenshots/feed-concrete-pulse-ca531534--editorial-quote-portrait.jpg) |
| Contemporary Heirlooms | `content-columns-steps` | `home.content_columns_steps.image_1_alt` | 635.00 × 635.00 | 1.0000:1 | [Section](screenshots/feed-contemporary-heirlooms-464aae1b--content-columns-steps.jpg) |
| Contemporary Heirlooms | `content-columns-steps` | `home.content_columns_steps.image_2_alt` | 312.50 × 416.66 | 0.7500:1 | [Section](screenshots/feed-contemporary-heirlooms-464aae1b--content-columns-steps.jpg) |
| Contemporary Heirlooms | `content-columns-steps` | `home.content_columns_steps.image_3_alt` | 312.50 × 416.66 | 0.7500:1 | [Section](screenshots/feed-contemporary-heirlooms-464aae1b--content-columns-steps.jpg) |
| Contemporary Heirlooms | `editorial-caption-banner` | `home.editorial_caption_banner.image_1_alt` | 1440.00 × 720.00 | 2.0000:1 | [Section](screenshots/feed-contemporary-heirlooms-464aae1b--editorial-caption-banner.jpg) |
| Court Culture | `content-grid-glossary` | `home.content_grid_glossary.image_1_alt` | 308.00 × 385.00 | 0.8000:1 | [Section](screenshots/feed-court-culture-cbcc330d--content-grid-glossary.jpg) |
| Court Culture | `content-grid-glossary` | `home.content_grid_glossary.image_2_alt` | 308.00 × 385.00 | 0.8000:1 | [Section](screenshots/feed-court-culture-cbcc330d--content-grid-glossary.jpg) |
| Court Culture | `content-grid-glossary` | `home.content_grid_glossary.image_3_alt` | 308.00 × 385.00 | 0.8000:1 | [Section](screenshots/feed-court-culture-cbcc330d--content-grid-glossary.jpg) |
| Court Culture | `content-grid-glossary` | `home.content_grid_glossary.image_4_alt` | 308.00 × 385.00 | 0.8000:1 | [Section](screenshots/feed-court-culture-cbcc330d--content-grid-glossary.jpg) |
| Creative Playground | `cta-mosaic-promo` | `home.cta_mosaic_promo.image_1_alt` | 812.56 × 609.42 | 1.3333:1 | [Section](screenshots/feed-creative-playground-2a7e4846--cta-mosaic-promo.jpg) |
| Creative Playground | `cta-mosaic-promo` | `home.cta_mosaic_promo.image_2_alt` | 451.44 × 296.70 | 1.5215:1 | [Section](screenshots/feed-creative-playground-2a7e4846--cta-mosaic-promo.jpg) |
| Creative Playground | `cta-mosaic-promo` | `home.cta_mosaic_promo.image_3_alt` | 451.44 × 296.72 | 1.5214:1 | [Section](screenshots/feed-creative-playground-2a7e4846--cta-mosaic-promo.jpg) |
| Creative Playground | `features-overlap-statement` | `home.features_overlap_statement.image_1_alt` | 1024.00 × 576.00 | 1.7778:1 | [Section](screenshots/feed-creative-playground-2a7e4846--features-overlap-statement.jpg) |
| Desk Objects in Motion | `content-split-howto` | `home.content_split_howto.image_1_alt` | 546.00 × 682.50 | 0.8000:1 | [Section](screenshots/feed-desk-objects-in-motion-5a7b5319--content-split-howto.jpg) |
| Desk Objects in Motion | `cta-asymmetric` | `home.cta_asymmetric.image_1_alt` | 780.66 × 585.48 | 1.3334:1 | [Section](screenshots/feed-desk-objects-in-motion-5a7b5319--cta-asymmetric.jpg) |
| Desk Objects in Motion | `cta-asymmetric` | `home.cta_asymmetric.image_2_alt` | 330.00 × 412.50 | 0.8000:1 | [Section](screenshots/feed-desk-objects-in-motion-5a7b5319--cta-asymmetric.jpg) |
| Desk Objects in Motion | `cta-asymmetric` | `home.cta_asymmetric.image_3_alt` | 330.00 × 412.50 | 0.8000:1 | [Section](screenshots/feed-desk-objects-in-motion-5a7b5319--cta-asymmetric.jpg) |
| Desk to Drinks | `editorial-profile-cards` | `home.editorial_profile_cards.image_1_alt` | 479.00 × 319.33 | 1.5000:1 | [Section](screenshots/feed-desk-to-drinks-3492b0dc--editorial-profile-cards.jpg) |
| Desk to Drinks | `editorial-profile-cards` | `home.editorial_profile_cards.image_2_alt` | 479.00 × 319.33 | 1.5000:1 | [Section](screenshots/feed-desk-to-drinks-3492b0dc--editorial-profile-cards.jpg) |
| Desk to Drinks | `editorial-profile-cards` | `home.editorial_profile_cards.image_3_alt` | 480.00 × 320.00 | 1.5000:1 | [Section](screenshots/feed-desk-to-drinks-3492b0dc--editorial-profile-cards.jpg) |
| Desk to Drinks | `cta-split` | `home.cta_split.image_1_alt` | 721.33 × 824.38 | 0.8750:1 | [Section](screenshots/feed-desk-to-drinks-605d453a--cta-split.jpg) |
| Desk to Drinks | `editorial-split` | `home.editorial_split.image_1_alt` | 510.66 × 638.31 | 0.8000:1 | [Section](screenshots/feed-desk-to-drinks-605d453a--editorial-split.jpg) |
| Driftline | `features-columns-product` | `home.features_columns_product.image_1_alt` | 459.86 × 574.81 | 0.8000:1 | [Section](screenshots/feed-driftline-aac4d214--features-columns-product.jpg) |
| Effortless Rituals | `footer-overlap-media` | `layout_footer.image_1_alt` | 1440.00 × 600.00 | 2.4000:1 | [Section](screenshots/feed-effortless-rituals-3899a311--footer-overlap-media.jpg) |
| Electric Ember | `editorial-gallery-grid` | `home.editorial_gallery_grid.image_1_alt` | 410.66 × 307.98 | 1.3334:1 | [Section](screenshots/feed-electric-ember-0489b72f--editorial-gallery-grid.jpg) |
| Electric Ember | `editorial-gallery-grid` | `home.editorial_gallery_grid.image_2_alt` | 410.67 × 308.00 | 1.3334:1 | [Section](screenshots/feed-electric-ember-0489b72f--editorial-gallery-grid.jpg) |
| Electric Ember | `editorial-gallery-grid` | `home.editorial_gallery_grid.image_3_alt` | 410.66 × 307.98 | 1.3334:1 | [Section](screenshots/feed-electric-ember-0489b72f--editorial-gallery-grid.jpg) |
| Electric Ember | `editorial-split` | `home.editorial_split.image_1_alt` | 260.16 × 312.84 | 0.8316:1 | [Section](screenshots/feed-electric-ember-0489b72f--editorial-split.jpg) |
| Electric Ember | `editorial-split` | `home.editorial_split.image_2_alt` | 260.16 × 312.84 | 0.8316:1 | [Section](screenshots/feed-electric-ember-0489b72f--editorial-split.jpg) |
| Electric Ember | `editorial-split` | `home.editorial_split.image_3_alt` | 260.16 × 312.84 | 0.8316:1 | [Section](screenshots/feed-electric-ember-0489b72f--editorial-split.jpg) |
| Electric Ember | `editorial-split` | `home.editorial_split.image_4_alt` | 260.16 × 312.84 | 0.8316:1 | [Section](screenshots/feed-electric-ember-0489b72f--editorial-split.jpg) |
| ERESU | `editorial-overlap` | `home.editorial_overlap.image_1_alt` | 1440.00 × 810.00 | 1.7778:1 | [Section](screenshots/feed-eresu-6b7e93b2--editorial-overlap.jpg) |
| ERESU | `media-banner` | `home.media_banner.image_1_alt` | 1440.00 × 600.00 | 2.4000:1 | [Section](screenshots/feed-eresu-6b7e93b2--media-banner.jpg) |
| Everyday Elevated | `cta-mosaic-promo` | `home.cta_mosaic_promo.image_1_alt` | 840.00 × 860.00 | 0.9767:1 | [Section](screenshots/feed-everyday-elevated-3acc8cc4--cta-mosaic-promo.jpg) |
| Everyday Elevated | `cta-mosaic-promo` | `home.cta_mosaic_promo.image_2_alt` | 600.00 × 430.00 | 1.3953:1 | [Section](screenshots/feed-everyday-elevated-3acc8cc4--cta-mosaic-promo.jpg) |
| Everyday Elevated | `features-overlap` | `home.features_overlap.image_1_alt` | 960.00 × 680.00 | 1.4118:1 | [Section](screenshots/feed-everyday-elevated-3acc8cc4--features-overlap.jpg) |
| Feel-Good Fuel | `content-split-howto` | `home.content_split_howto.image_1_alt` | 720.00 × 680.00 | 1.0588:1 | [Section](screenshots/feed-feel-good-fuel-e35eff31--content-split-howto.jpg) |
| Festive Table Stories | `cta-split-steps` | `home.cta_split_steps.image_1_alt` | 840.00 × 760.00 | 1.1053:1 | [Section](screenshots/feed-festive-table-stories-9d092267--cta-split-steps.jpg) |
| Festive Table Stories | `features-overlap` | `home.features_overlap.image_1_alt` | 1440.00 × 820.00 | 1.7561:1 | [Section](screenshots/feed-festive-table-stories-9d092267--features-overlap.jpg) |
| Frame Club | `content-asymmetric-resource` | `home.content_asymmetric_resource.image_1_alt` | 318.00 × 397.50 | 0.8000:1 | [Section](screenshots/feed-frame-club-b76f7d53--content-asymmetric-resource.jpg) |
| Frame Club | `content-asymmetric-resource` | `home.content_asymmetric_resource.image_2_alt` | 318.00 × 397.50 | 0.8000:1 | [Section](screenshots/feed-frame-club-b76f7d53--content-asymmetric-resource.jpg) |
| Gathered at the Table | `editorial-standfirst-banner` | `home.editorial_standfirst_banner.image_1_alt` | 1440.00 × 720.00 | 2.0000:1 | [Section](screenshots/feed-gathered-at-the-table-0f227565--editorial-standfirst-banner.jpg) |
| Gold Accent Vitality | `cta-split` | `home.cta_split.image_1_alt` | 692.00 × 560.00 | 1.2357:1 | [Section](screenshots/feed-gold-accent-vitality-b6c45efa--cta-split.jpg) |
| Gold Accent Vitality | `editorial-sidebar` | `home.editorial_sidebar.image_4_alt` | 680.00 × 510.00 | 1.3333:1 | [Section](screenshots/feed-gold-accent-vitality-b6c45efa--editorial-sidebar.jpg) |
| Gold Accent Vitality | `editorial-sidebar` | `home.editorial_sidebar.image_5_alt` | 680.00 × 510.00 | 1.3333:1 | [Section](screenshots/feed-gold-accent-vitality-b6c45efa--editorial-sidebar.jpg) |
| Gold Accent Vitality | `editorial-sidebar` | `home.editorial_sidebar.image_6_alt` | 680.00 × 510.00 | 1.3333:1 | [Section](screenshots/feed-gold-accent-vitality-b6c45efa--editorial-sidebar.jpg) |
| Gold Accent Vitality | `features-carousel` | `home.features_carousel.image_1_alt` | 801.34 × 601.00 | 1.3334:1 | [Section](screenshots/feed-gold-accent-vitality-b6c45efa--features-carousel.jpg) |
| Gold Accent Vitality | `features-carousel` | `home.features_carousel.image_2_alt` | 801.34 × 601.00 | 1.3334:1 | [Section](screenshots/feed-gold-accent-vitality-b6c45efa--features-carousel.jpg) |
| Gold Accent Vitality | `features-carousel` | `home.features_carousel.image_3_alt` | 801.34 × 601.00 | 1.3334:1 | [Section](screenshots/feed-gold-accent-vitality-b6c45efa--features-carousel.jpg) |
| Gold Accent Vitality | `features-carousel` | `home.features_carousel.image_4_alt` | 801.34 × 601.00 | 1.3334:1 | [Section](screenshots/feed-gold-accent-vitality-b6c45efa--features-carousel.jpg) |
| Gold Accent Vitality | `features-carousel` | `home.features_carousel.image_5_alt` | 801.34 × 601.00 | 1.3334:1 | [Section](screenshots/feed-gold-accent-vitality-b6c45efa--features-carousel.jpg) |
| Golden Interval | `content-stacked-statement` | `home.content_stacked_statement.image_1_alt` | 203.42 × 542.47 | 0.3750:1 | [Section](screenshots/feed-golden-interval-616ba7c1--content-stacked-statement.jpg) |
| Golden Interval | `content-stacked-statement` | `home.content_stacked_statement.image_2_alt` | 339.05 × 542.47 | 0.6250:1 | [Section](screenshots/feed-golden-interval-616ba7c1--content-stacked-statement.jpg) |
| Golden Interval | `content-stacked-statement` | `home.content_stacked_statement.image_3_alt` | 339.05 × 542.47 | 0.6250:1 | [Section](screenshots/feed-golden-interval-616ba7c1--content-stacked-statement.jpg) |
| Golden Interval | `content-stacked-statement` | `home.content_stacked_statement.image_4_alt` | 339.05 × 542.47 | 0.6250:1 | [Section](screenshots/feed-golden-interval-616ba7c1--content-stacked-statement.jpg) |
| Golden Interval | `content-stacked-statement` | `home.content_stacked_statement.image_5_alt` | 203.42 × 542.47 | 0.3750:1 | [Section](screenshots/feed-golden-interval-616ba7c1--content-stacked-statement.jpg) |
| Saltglass Swim | `editorial-caption-banner` | `home.editorial_caption_banner.image_1_alt` | 1440.00 × 560.00 | 2.5714:1 | [Section](screenshots/feed-golden-tide-collective-cbe226a1--editorial-caption-banner.jpg) |
| Haunted Hearth | `content-split-howto` | `home.content_split_howto.image_1_alt` | 559.33 × 372.88 | 1.5000:1 | [Section](screenshots/feed-haunted-hearth-74841fa7--content-split-howto.jpg) |
| Haunted Hearth | `editorial-sidebar` | `home.editorial_sidebar.image_1_alt` | 692.00 × 865.00 | 0.8000:1 | [Section](screenshots/feed-haunted-hearth-74841fa7--editorial-sidebar.jpg) |
| Haven & Hearth | `content-grid-articles` | `home.content_grid_articles.image_1_alt` | 413.33 × 516.66 | 0.8000:1 | [Section](screenshots/feed-haven-hearth-02c64983--content-grid-articles.jpg) |
| Haven & Hearth | `content-grid-articles` | `home.content_grid_articles.image_2_alt` | 413.33 × 516.66 | 0.8000:1 | [Section](screenshots/feed-haven-hearth-02c64983--content-grid-articles.jpg) |
| Haven & Hearth | `content-grid-articles` | `home.content_grid_articles.image_3_alt` | 413.34 × 516.67 | 0.8000:1 | [Section](screenshots/feed-haven-hearth-02c64983--content-grid-articles.jpg) |
| Haven & Hearth | `editorial-split` | `home.editorial_split.image_1_alt` | 746.66 × 559.98 | 1.3334:1 | [Section](screenshots/feed-haven-hearth-02c64983--editorial-split.jpg) |
| Haze & Co. | `cta-overlap` | `home.cta_overlap.image_1_alt` | 1280.00 × 720.00 | 1.7778:1 | [Section](screenshots/feed-haze-co-ddebc1c9--cta-overlap.jpg) |
| Haze & Co. | `media-banner` | `home.media_banner.image_1_alt` | 1440.00 × 925.42 | 1.5560:1 | [Section](screenshots/feed-haze-co-ddebc1c9--media-banner.jpg) |
| Kumo | `cta-columns-image` | `home.cta_columns_image.image_1_alt` | 720.00 × 630.00 | 1.1429:1 | [Section](screenshots/feed-kumo-9411624c--cta-columns-image.jpg) |
| Kumo | `cta-columns-image` | `home.cta_columns_image.image_2_alt` | 720.00 × 630.00 | 1.1429:1 | [Section](screenshots/feed-kumo-9411624c--cta-columns-image.jpg) |
| Kumo | `editorial-cover` | `home.editorial_cover.image_1_alt` | 1440.00 × 810.00 | 1.7778:1 | [Section](screenshots/feed-kumo-9411624c--editorial-cover.jpg) |
| Lacé | `content-portrait-story` | `home.content_portrait_story.image_1_alt` | 700.00 × 481.25 | 1.4545:1 | [Section](screenshots/feed-lace-c6c3cf61--content-portrait-story.jpg) |
| Lacé | `content-stacked-statement` | `home.content_stacked_statement.image_1_alt` | 1440.00 × 700.00 | 2.0571:1 | [Section](screenshots/feed-lace-c6c3cf61--content-stacked-statement.jpg) |
| Light as Art | `content-overlap-video` | `home.content_overlap_video.image_1_alt` | 1376.00 × 688.00 | 2.0000:1 | [Section](screenshots/feed-light-as-art-d46a8a34--content-overlap-video.jpg) |
| Light as Art | `content-portrait-story` | `home.content_portrait_story.image_1_alt` | 720.00 × 840.00 | 0.8571:1 | [Section](screenshots/feed-light-as-art-d46a8a34--content-portrait-story.jpg) |
| Light as Art | `cta-carousel` | `home.cta_carousel.image_1_alt` | 358.66 × 502.11 | 0.7143:1 | [Section](screenshots/feed-light-as-art-d46a8a34--cta-carousel.jpg) |
| Light as Art | `cta-carousel` | `home.cta_carousel.image_2_alt` | 358.67 × 502.14 | 0.7143:1 | [Section](screenshots/feed-light-as-art-d46a8a34--cta-carousel.jpg) |
| Light as Art | `cta-carousel` | `home.cta_carousel.image_3_alt` | 358.66 × 502.11 | 0.7143:1 | [Section](screenshots/feed-light-as-art-d46a8a34--cta-carousel.jpg) |
| Lived-In Glow | `footer-asymmetric-display` | `layout_footer.image_1_alt` | 930.67 × 310.22 | 3.0000:1 | [Section](screenshots/feed-lived-in-glow-adf847a3--footer-asymmetric-display.jpg) |
| Lumen Club | `editorial-carousel` | `home.editorial_carousel.image_1_alt` | 225.33 × 281.66 | 0.8000:1 | [Section](screenshots/feed-lumen-club-f6014c3f--editorial-carousel.jpg) |
| Lumen Club | `editorial-carousel` | `home.editorial_carousel.image_2_alt` | 225.33 × 281.66 | 0.8000:1 | [Section](screenshots/feed-lumen-club-f6014c3f--editorial-carousel.jpg) |
| Lumen Club | `editorial-carousel` | `home.editorial_carousel.image_3_alt` | 225.33 × 281.66 | 0.8000:1 | [Section](screenshots/feed-lumen-club-f6014c3f--editorial-carousel.jpg) |
| Lumen Club | `editorial-carousel` | `home.editorial_carousel.image_4_alt` | 225.34 × 281.67 | 0.8000:1 | [Section](screenshots/feed-lumen-club-f6014c3f--editorial-carousel.jpg) |
| Lumina Botanica | `content-columns-steps` | `home.content_columns_steps.image_1_alt` | 160.00 × 160.00 | 1.0000:1 | [Section](screenshots/feed-lumina-botanica-fee51738--content-columns-steps.jpg) |
| Lumina Botanica | `content-columns-steps` | `home.content_columns_steps.image_2_alt` | 160.00 × 160.00 | 1.0000:1 | [Section](screenshots/feed-lumina-botanica-fee51738--content-columns-steps.jpg) |
| Lumina Botanica | `content-columns-steps` | `home.content_columns_steps.image_3_alt` | 160.00 × 160.00 | 1.0000:1 | [Section](screenshots/feed-lumina-botanica-fee51738--content-columns-steps.jpg) |
| Lumina Botanica | `content-portrait-story` | `home.content_portrait_story.image_1_alt` | 689.38 × 827.25 | 0.8333:1 | [Section](screenshots/feed-lumina-botanica-fee51738--content-portrait-story.jpg) |
| Lumina Grain | `editorial-caption-banner` | `home.editorial_caption_banner.image_1_alt` | 1440.00 × 560.00 | 2.5714:1 | [Section](screenshots/feed-lumina-grain-94e00c53--editorial-caption-banner.jpg) |
| Lumina Grain | `editorial-split` | `home.editorial_split.image_1_alt` | 720.00 × 520.00 | 1.3846:1 | [Section](screenshots/feed-lumina-grain-94e00c53--editorial-split.jpg) |
| Luminous Minimalism | `cta-video-feature` | `home.cta_video_feature.image_1_alt` | 448.00 × 560.00 | 0.8000:1 | [Section](screenshots/feed-luminous-minimalism-07f12a93--cta-video-feature.jpg) |
| Marée | `content-stacked-statement` | `home.content_stacked_statement.image_1_alt` | 1440.00 × 810.00 | 1.7778:1 | [Section](screenshots/feed-maree-fb912b0d--content-stacked-statement.jpg) |
| Marée | `editorial-caption-banner` | `home.editorial_caption_banner.image_1_alt` | 1440.00 × 860.00 | 1.6744:1 | [Section](screenshots/feed-maree-fb912b0d--editorial-caption-banner.jpg) |
| Marée | `media-banner` | `home.media_banner.image_1_alt` | 1440.00 × 860.00 | 1.6744:1 | [Section](screenshots/feed-maree-fb912b0d--media-banner.jpg) |
| Modern Earth | `editorial-sidebar` | `home.editorial_sidebar.image_1_alt` | 948.00 × 533.25 | 1.7778:1 | [Section](screenshots/feed-modern-earth-6969d979--editorial-sidebar.jpg) |
| Modern Expedition | `content-split-video` | `home.content_split_video.image_1_alt` | 665.59 × 499.19 | 1.3334:1 | [Section](screenshots/feed-modern-expedition-27be91a3--content-split-video.jpg) |
| Modern Expedition | `editorial-split` | `home.editorial_split.image_1_alt` | 533.33 × 666.66 | 0.8000:1 | [Section](screenshots/feed-modern-expedition-27be91a3--editorial-split.jpg) |
| Modern Expedition | `features-asymmetric` | `home.features_asymmetric.image_1_alt` | 638.81 × 741.47 | 0.8615:1 | [Section](screenshots/feed-modern-expedition-27be91a3--features-asymmetric.jpg) |
| Modern Muse | `cta-split` | `home.cta_split.image_1_alt` | 660.00 × 792.00 | 0.8333:1 | [Section](screenshots/feed-modern-muse-22d857ed--cta-split.jpg) |
| Modern Muse | `editorial-caption-tiles` | `home.editorial_caption_tiles.image_1_alt` | 308.00 × 385.00 | 0.8000:1 | [Section](screenshots/feed-modern-muse-22d857ed--editorial-caption-tiles.jpg) |
| Modern Muse | `editorial-caption-tiles` | `home.editorial_caption_tiles.image_2_alt` | 308.00 × 385.00 | 0.8000:1 | [Section](screenshots/feed-modern-muse-22d857ed--editorial-caption-tiles.jpg) |
| Modern Muse | `editorial-caption-tiles` | `home.editorial_caption_tiles.image_3_alt` | 308.00 × 385.00 | 0.8000:1 | [Section](screenshots/feed-modern-muse-22d857ed--editorial-caption-tiles.jpg) |
| Modern Muse | `editorial-caption-tiles` | `home.editorial_caption_tiles.image_4_alt` | 308.00 × 385.00 | 0.8000:1 | [Section](screenshots/feed-modern-muse-22d857ed--editorial-caption-tiles.jpg) |
| Modern Muse | `editorial-essay` | `home.editorial_essay.image_1_alt` | 1440.00 × 617.14 | 2.3333:1 | [Section](screenshots/feed-modern-muse-22d857ed--editorial-essay.jpg) |
| Modern Nest | `content-columns-steps` | `home.content_columns_steps.image_1_alt` | 418.66 × 523.31 | 0.8000:1 | [Section](screenshots/feed-modern-nest-5d62c811--content-columns-steps.jpg) |
| Modern Nest | `content-columns-steps` | `home.content_columns_steps.image_2_alt` | 418.67 × 523.33 | 0.8000:1 | [Section](screenshots/feed-modern-nest-5d62c811--content-columns-steps.jpg) |
| Modern Nest | `content-columns-steps` | `home.content_columns_steps.image_3_alt` | 418.66 × 523.31 | 0.8000:1 | [Section](screenshots/feed-modern-nest-5d62c811--content-columns-steps.jpg) |
| Monochrome Statement | `content-story-tiles` | `home.content_story_tiles.image_1_alt` | 716.00 × 835.33 | 0.8571:1 | [Section](screenshots/feed-monochrome-statement-664fa55c--content-story-tiles.jpg) |
| Monochrome Statement | `content-story-tiles` | `home.content_story_tiles.image_2_alt` | 716.00 × 835.33 | 0.8571:1 | [Section](screenshots/feed-monochrome-statement-664fa55c--content-story-tiles.jpg) |
| murmure | `cta-split` | `home.cta_split.image_1_alt` | 960.00 × 720.00 | 1.3333:1 | [Section](screenshots/feed-murmure-6f516ba3--cta-split.jpg) |
| murmure | `editorial-caption-banner` | `home.editorial_caption_banner.image_1_alt` | 1440.00 × 860.00 | 1.6744:1 | [Section](screenshots/feed-murmure-6f516ba3--editorial-caption-banner.jpg) |
| murmure | `editorial-caption-tiles` | `home.editorial_caption_tiles.image_1_alt` | 480.00 × 600.00 | 0.8000:1 | [Section](screenshots/feed-murmure-6f516ba3--editorial-caption-tiles.jpg) |
| murmure | `editorial-caption-tiles` | `home.editorial_caption_tiles.image_2_alt` | 480.00 × 600.00 | 0.8000:1 | [Section](screenshots/feed-murmure-6f516ba3--editorial-caption-tiles.jpg) |
| murmure | `editorial-caption-tiles` | `home.editorial_caption_tiles.image_3_alt` | 480.00 × 600.00 | 0.8000:1 | [Section](screenshots/feed-murmure-6f516ba3--editorial-caption-tiles.jpg) |
| Neo-Japan Everyday | `commerce-category-tiles` | `home.commerce_category_tiles.image_1_alt` | 340.00 × 425.00 | 0.8000:1 | [Section](screenshots/feed-neo-japan-everyday-1beada46--commerce-category-tiles.jpg) |
| Neo-Japan Everyday | `commerce-category-tiles` | `home.commerce_category_tiles.image_2_alt` | 340.00 × 425.00 | 0.8000:1 | [Section](screenshots/feed-neo-japan-everyday-1beada46--commerce-category-tiles.jpg) |
| Neo-Japan Everyday | `commerce-category-tiles` | `home.commerce_category_tiles.image_3_alt` | 340.00 × 425.00 | 0.8000:1 | [Section](screenshots/feed-neo-japan-everyday-1beada46--commerce-category-tiles.jpg) |
| Neo-Japan Everyday | `commerce-category-tiles` | `home.commerce_category_tiles.image_4_alt` | 340.00 × 425.00 | 0.8000:1 | [Section](screenshots/feed-neo-japan-everyday-1beada46--commerce-category-tiles.jpg) |
| Neo-Japan Everyday | `cta-banner-mixed` | `home.cta_banner_mixed.image_1_alt` | 704.00 × 480.00 | 1.4667:1 | [Section](screenshots/feed-neo-japan-everyday-1beada46--cta-banner-mixed.jpg) |
| Odile Grey | `cta-columns` | `home.cta_columns.image_1_alt` | 500.00 × 500.00 | 1.0000:1 | [Section](screenshots/feed-odile-grey-5db868a6--cta-columns.jpg) |
| Odile Grey | `cta-columns` | `home.cta_columns.image_2_alt` | 500.00 × 500.00 | 1.0000:1 | [Section](screenshots/feed-odile-grey-5db868a6--cta-columns.jpg) |
| Odile Grey | `editorial-standfirst-banner` | `home.editorial_standfirst_banner.image_1_alt` | 1440.00 × 900.00 | 1.6000:1 | [Section](screenshots/feed-odile-grey-5db868a6--editorial-standfirst-banner.jpg) |
| ORVENORIA | `cta-split` | `home.cta_split.image_1_alt` | 721.33 × 824.38 | 0.8750:1 | [Section](screenshots/feed-orvenoria-64caa630--cta-split.jpg) |
| ORVENORIA | `editorial-split` | `home.editorial_split.image_1_alt` | 510.66 × 638.31 | 0.8000:1 | [Section](screenshots/feed-orvenoria-64caa630--editorial-split.jpg) |
| ORVENORIA | `content-grid-articles` | `home.content_grid_articles.image_1_alt` | 410.66 × 513.31 | 0.8000:1 | [Section](screenshots/feed-orvenoria-af7d9e27--content-grid-articles.jpg) |
| ORVENORIA | `content-grid-articles` | `home.content_grid_articles.image_2_alt` | 410.67 × 513.33 | 0.8000:1 | [Section](screenshots/feed-orvenoria-af7d9e27--content-grid-articles.jpg) |
| ORVENORIA | `content-grid-articles` | `home.content_grid_articles.image_3_alt` | 410.66 × 513.31 | 0.8000:1 | [Section](screenshots/feed-orvenoria-af7d9e27--content-grid-articles.jpg) |
| ORVENORIA | `editorial-caption-banner` | `home.editorial_caption_banner.image_1_alt` | 1440.00 × 680.00 | 2.1176:1 | [Section](screenshots/feed-orvenoria-af7d9e27--editorial-caption-banner.jpg) |
| ORVENORIA | `editorial-split` | `home.editorial_split.image_1_alt` | 746.66 × 559.98 | 1.3334:1 | [Section](screenshots/feed-orvenoria-af7d9e27--editorial-split.jpg) |
| ORVENORIA | `footer-asymmetric-display` | `layout_footer.image_1_alt` | 612.00 × 306.00 | 2.0000:1 | [Section](screenshots/feed-orvenoria-af7d9e27--footer-asymmetric-display.jpg) |
| Parallax | `content-stacked-statement` | `home.content_stacked_statement.image_1_alt` | 1440.00 × 810.00 | 1.7778:1 | [Section](screenshots/feed-parallax-32540ff0--content-stacked-statement.jpg) |
| Parallax | `editorial-gallery-grid` | `home.editorial_gallery_grid.image_1_alt` | 273.59 × 341.98 | 0.8000:1 | [Section](screenshots/feed-parallax-32540ff0--editorial-gallery-grid.jpg) |
| Parallax | `editorial-gallery-grid` | `home.editorial_gallery_grid.image_2_alt` | 331.19 × 441.58 | 0.7500:1 | [Section](screenshots/feed-parallax-32540ff0--editorial-gallery-grid.jpg) |
| Parallax | `editorial-gallery-grid` | `home.editorial_gallery_grid.image_3_alt` | 288.00 × 288.00 | 1.0000:1 | [Section](screenshots/feed-parallax-32540ff0--editorial-gallery-grid.jpg) |
| Parallax | `editorial-gallery-grid` | `home.editorial_gallery_grid.image_4_alt` | 360.00 × 420.00 | 0.8571:1 | [Section](screenshots/feed-parallax-32540ff0--editorial-gallery-grid.jpg) |
| Parallax | `editorial-gallery-grid` | `home.editorial_gallery_grid.image_5_alt` | 273.59 × 364.78 | 0.7500:1 | [Section](screenshots/feed-parallax-32540ff0--editorial-gallery-grid.jpg) |
| Parallax | `editorial-split` | `home.editorial_split.image_1_alt` | 628.00 × 471.00 | 1.3333:1 | [Section](screenshots/feed-parallax-32540ff0--editorial-split.jpg) |
| pipkin | `cta-asymmetric` | `home.cta_asymmetric.image_1_alt` | 564.39 × 705.48 | 0.8000:1 | [Section](screenshots/feed-pipkin-9a94d0f0--cta-asymmetric.jpg) |
| pipkin | `cta-asymmetric` | `home.cta_asymmetric.image_2_alt` | 217.28 × 271.59 | 0.8000:1 | [Section](screenshots/feed-pipkin-9a94d0f0--cta-asymmetric.jpg) |
| pipkin | `features-stacked` | `home.features_stacked.image_1_alt` | 720.00 × 720.00 | 1.0000:1 | [Section](screenshots/feed-pipkin-9a94d0f0--features-stacked.jpg) |
| Plain Stock | `content-grid-articles` | `home.content_grid_articles.image_1_alt` | 405.33 × 506.66 | 0.8000:1 | [Section](screenshots/feed-plain-stock-401de08f--content-grid-articles.jpg) |
| Plain Stock | `content-grid-articles` | `home.content_grid_articles.image_2_alt` | 405.33 × 506.66 | 0.8000:1 | [Section](screenshots/feed-plain-stock-401de08f--content-grid-articles.jpg) |
| Plain Stock | `content-grid-articles` | `home.content_grid_articles.image_3_alt` | 405.34 × 506.67 | 0.8000:1 | [Section](screenshots/feed-plain-stock-401de08f--content-grid-articles.jpg) |
| Plain Stock | `cta-video-feature` | `home.cta_video_feature.image_1_alt` | 1440.00 × 720.00 | 2.0000:1 | [Section](screenshots/feed-plain-stock-401de08f--cta-video-feature.jpg) |
| Plain Stock | `editorial-gallery-grid` | `home.editorial_gallery_grid.image_1_alt` | 405.33 × 506.66 | 0.8000:1 | [Section](screenshots/feed-plain-stock-401de08f--editorial-gallery-grid.jpg) |
| Plain Stock | `editorial-gallery-grid` | `home.editorial_gallery_grid.image_2_alt` | 405.33 × 506.66 | 0.8000:1 | [Section](screenshots/feed-plain-stock-401de08f--editorial-gallery-grid.jpg) |
| Plain Stock | `editorial-gallery-grid` | `home.editorial_gallery_grid.image_3_alt` | 405.34 × 506.67 | 0.8000:1 | [Section](screenshots/feed-plain-stock-401de08f--editorial-gallery-grid.jpg) |
| Playful Function Atelier | `content-split-howto` | `home.content_split_howto.image_1_alt` | 700.00 × 544.00 | 1.2868:1 | [Section](screenshots/feed-playful-function-atelier-121b8a99--content-split-howto.jpg) |
| Quiet Precision | `editorial-cover` | `home.editorial_cover.image_1_alt` | 1280.00 × 640.00 | 2.0000:1 | [Section](screenshots/feed-quiet-precision-cfbde3ce--editorial-cover.jpg) |
| RadiantCurve Collective | `media-banner` | `home.media_banner.image_1_alt` | 1440.00 × 520.00 | 2.7692:1 | [Section](screenshots/feed-radiantcurve-collective-2f845859--media-banner.jpg) |
| Rally Club | `editorial-quote-portrait` | `home.editorial_quote_portrait.image_1_alt` | 802.66 × 680.00 | 1.1804:1 | [Section](screenshots/feed-rally-club-0f8d8efd--editorial-quote-portrait.jpg) |
| Reckless Table | `content-split-video` | `home.content_split_video.image_1_alt` | 926.66 × 521.23 | 1.7778:1 | [Section](screenshots/feed-reckless-table-e9821c4f--content-split-video.jpg) |
| Reckless Table | `cta-columns` | `home.cta_columns.image_1_alt` | 571.66 × 571.66 | 1.0000:1 | [Section](screenshots/feed-reckless-table-e9821c4f--cta-columns.jpg) |
| Reckless Table | `cta-columns` | `home.cta_columns.image_2_alt` | 571.67 × 571.67 | 1.0000:1 | [Section](screenshots/feed-reckless-table-e9821c4f--cta-columns.jpg) |
| Ricrac | `editorial-overlap` | `home.editorial_overlap.image_1_alt` | 1440.00 × 617.14 | 2.3333:1 | [Section](screenshots/feed-ricrac-4ecc6a74--editorial-overlap.jpg) |
| Saikhu | `content-split-video` | `home.content_split_video.image_1_alt` | 906.66 × 509.98 | 1.7778:1 | [Section](screenshots/feed-saikhu-f3c811df--content-split-video.jpg) |
| Second Pour | `cta-split` | `home.cta_split.image_1_alt` | 588.00 × 735.00 | 0.8000:1 | [Section](screenshots/feed-second-pour-fed58ee8--cta-split.jpg) |
| Second Pour | `features-split` | `home.features_split.image_1_alt` | 762.67 × 524.33 | 1.4546:1 | [Section](screenshots/feed-second-pour-fed58ee8--features-split.jpg) |
| Serene Sculpted Minimalism | `editorial-cover` | `home.editorial_cover.image_1_alt` | 1280.00 × 720.00 | 1.7778:1 | [Section](screenshots/feed-serene-sculpted-minimalism-a78d0625--editorial-cover.jpg) |
| Serene Sculpted Minimalism | `cta-asymmetric` | `home.cta_asymmetric.image_1_alt` | 960.00 × 600.00 | 1.6000:1 | [Section](screenshots/feed-serene-sculpted-minimalism-dd6e696a--cta-asymmetric.jpg) |
| Serene Sculpted Minimalism | `cta-asymmetric` | `home.cta_asymmetric.image_2_alt` | 480.00 × 320.00 | 1.5000:1 | [Section](screenshots/feed-serene-sculpted-minimalism-dd6e696a--cta-asymmetric.jpg) |
| Serene Sculpted Minimalism | `cta-asymmetric` | `home.cta_asymmetric.image_3_alt` | 480.00 × 320.00 | 1.5000:1 | [Section](screenshots/feed-serene-sculpted-minimalism-dd6e696a--cta-asymmetric.jpg) |
| Serene Sculpted Minimalism | `features-overlap` | `home.features_overlap.image_1_alt` | 1440.00 × 810.00 | 1.7778:1 | [Section](screenshots/feed-serene-sculpted-minimalism-dd6e696a--features-overlap.jpg) |
| Signed & Amplified | `cta-split-steps` | `home.cta_split_steps.image_1_alt` | 720.00 × 799.72 | 0.9003:1 | [Section](screenshots/feed-signed-amplified-dfc34130--cta-split-steps.jpg) |
| Signed & Amplified | `editorial-caption-tiles` | `home.editorial_caption_tiles.image_1_alt` | 720.00 × 960.00 | 0.7500:1 | [Section](screenshots/feed-signed-amplified-dfc34130--editorial-caption-tiles.jpg) |
| Signed & Amplified | `editorial-caption-tiles` | `home.editorial_caption_tiles.image_2_alt` | 720.00 × 960.00 | 0.7500:1 | [Section](screenshots/feed-signed-amplified-dfc34130--editorial-caption-tiles.jpg) |
| Signed & Amplified | `editorial-caption-tiles` | `home.editorial_caption_tiles.image_3_alt` | 720.00 × 960.00 | 0.7500:1 | [Section](screenshots/feed-signed-amplified-dfc34130--editorial-caption-tiles.jpg) |
| Signed & Amplified | `editorial-caption-tiles` | `home.editorial_caption_tiles.image_4_alt` | 720.00 × 960.00 | 0.7500:1 | [Section](screenshots/feed-signed-amplified-dfc34130--editorial-caption-tiles.jpg) |
| Solé Swim | `features-overlap-statement` | `home.features_overlap_statement.image_1_alt` | 191.52 × 80.62 | 2.3754:1 | [Section](screenshots/feed-sole-swim-a30204f5--features-overlap-statement.jpg) |
| Sotto | `media-banner` | `home.media_banner.image_1_alt` | 1440.00 × 720.00 | 2.0000:1 | [Section](screenshots/feed-sotto-7453b325--media-banner.jpg) |
| Sourdine | `content-story-tiles` | `home.content_story_tiles.image_1_alt` | 720.00 × 840.00 | 0.8571:1 | [Section](screenshots/feed-sourdine-485bbec8--content-story-tiles.jpg) |
| Sourdine | `content-story-tiles` | `home.content_story_tiles.image_2_alt` | 720.00 × 840.00 | 0.8571:1 | [Section](screenshots/feed-sourdine-485bbec8--content-story-tiles.jpg) |
| Sourdine | `editorial-cover` | `home.editorial_cover.image_1_alt` | 1440.00 × 617.14 | 2.3333:1 | [Section](screenshots/feed-sourdine-485bbec8--editorial-cover.jpg) |
| Studio Stillness | `cta-video-feature` | `home.cta_video_feature.image_1_alt` | 1440.00 × 860.00 | 1.6744:1 | [Section](screenshots/feed-studio-stillness-36ce88e0--cta-video-feature.jpg) |
| Studio Stillness | `editorial-standfirst-banner` | `home.editorial_standfirst_banner.image_1_alt` | 1440.00 × 860.00 | 1.6744:1 | [Section](screenshots/feed-studio-stillness-36ce88e0--editorial-standfirst-banner.jpg) |
| Sunlit Craft | `cta-overlap` | `home.cta_overlap.image_1_alt` | 260.00 × 364.00 | 0.7143:1 | [Section](screenshots/feed-sunlit-craft-013f7a6e--cta-overlap.jpg) |
| Sunlit Craft | `features-stacked` | `home.features_stacked.image_1_alt` | 846.00 × 720.00 | 1.1750:1 | [Section](screenshots/feed-sunlit-craft-013f7a6e--features-stacked.jpg) |
| The Archivist’s Atelier | `cta-asymmetric` | `home.cta_asymmetric.image_1_alt` | 952.00 × 595.00 | 1.6000:1 | [Section](screenshots/feed-the-archivist-s-atelier-3c245f74--cta-asymmetric.jpg) |
| The Archivist’s Atelier | `editorial-standfirst-banner` | `home.editorial_standfirst_banner.image_1_alt` | 1440.00 × 810.00 | 1.7778:1 | [Section](screenshots/feed-the-archivist-s-atelier-3c245f74--editorial-standfirst-banner.jpg) |
| The Archivist’s Atelier | `footer-split-brand` | `layout_footer.image_1_alt` | 262.39 × 262.39 | 1.0000:1 | [Section](screenshots/feed-the-archivist-s-atelier-3c245f74--footer-split-brand.jpg) |
| The Archivist’s Atelier | `footer-split-brand` | `layout_footer.image_2_alt` | 262.41 × 262.41 | 1.0000:1 | [Section](screenshots/feed-the-archivist-s-atelier-3c245f74--footer-split-brand.jpg) |
| The Archivist’s Atelier | `footer-split-brand` | `layout_footer.image_3_alt` | 262.39 × 262.39 | 1.0000:1 | [Section](screenshots/feed-the-archivist-s-atelier-3c245f74--footer-split-brand.jpg) |
| The Archivist’s Atelier | `footer-split-brand` | `layout_footer.image_4_alt` | 262.41 × 262.41 | 1.0000:1 | [Section](screenshots/feed-the-archivist-s-atelier-3c245f74--footer-split-brand.jpg) |
| The Archivist’s Atelier | `footer-split-brand` | `layout_footer.image_5_alt` | 262.39 × 262.39 | 1.0000:1 | [Section](screenshots/feed-the-archivist-s-atelier-3c245f74--footer-split-brand.jpg) |
| The Rehearsal Room | `editorial-magazine-grid` | `home.editorial_magazine_grid.image_1_alt` | 326.00 × 407.50 | 0.8000:1 | [Section](screenshots/feed-the-rehearsal-room-ac54d970--editorial-magazine-grid.jpg) |
| The Rehearsal Room | `editorial-magazine-grid` | `home.editorial_magazine_grid.image_2_alt` | 326.00 × 407.50 | 0.8000:1 | [Section](screenshots/feed-the-rehearsal-room-ac54d970--editorial-magazine-grid.jpg) |
| The Rehearsal Room | `editorial-magazine-grid` | `home.editorial_magazine_grid.image_3_alt` | 326.00 × 407.50 | 0.8000:1 | [Section](screenshots/feed-the-rehearsal-room-ac54d970--editorial-magazine-grid.jpg) |
| The Scented Atelier | `commerce-category-tiles` | `home.commerce_category_tiles.image_1_alt` | 260.00 × 260.00 | 1.0000:1 | [Section](screenshots/feed-the-scented-atelier-a895c870--commerce-category-tiles.jpg) |
| The Scented Atelier | `commerce-category-tiles` | `home.commerce_category_tiles.image_2_alt` | 260.00 × 260.00 | 1.0000:1 | [Section](screenshots/feed-the-scented-atelier-a895c870--commerce-category-tiles.jpg) |
| The Scented Atelier | `commerce-category-tiles` | `home.commerce_category_tiles.image_3_alt` | 260.00 × 260.00 | 1.0000:1 | [Section](screenshots/feed-the-scented-atelier-a895c870--commerce-category-tiles.jpg) |
| The Scented Atelier | `editorial-magazine-grid` | `home.editorial_magazine_grid.image_1_alt` | 416.00 × 554.66 | 0.7500:1 | [Section](screenshots/feed-the-scented-atelier-a895c870--editorial-magazine-grid.jpg) |
| The Scented Atelier | `editorial-magazine-grid` | `home.editorial_magazine_grid.image_2_alt` | 416.00 × 554.66 | 0.7500:1 | [Section](screenshots/feed-the-scented-atelier-a895c870--editorial-magazine-grid.jpg) |
| The Scented Atelier | `editorial-magazine-grid` | `home.editorial_magazine_grid.image_3_alt` | 416.00 × 554.66 | 0.7500:1 | [Section](screenshots/feed-the-scented-atelier-a895c870--editorial-magazine-grid.jpg) |
| Trail Stories: In Motion | `content-story-tiles` | `home.content_story_tiles.image_1_alt` | 329.00 × 411.25 | 0.8000:1 | [Section](screenshots/feed-trail-stories-in-motion-90190a52--content-story-tiles.jpg) |
| Trail Stories: In Motion | `content-story-tiles` | `home.content_story_tiles.image_2_alt` | 678.00 × 904.00 | 0.7500:1 | [Section](screenshots/feed-trail-stories-in-motion-90190a52--content-story-tiles.jpg) |
| Trail Stories: In Motion | `editorial-caption-banner` | `home.editorial_caption_banner.image_1_alt` | 1440.00 × 720.00 | 2.0000:1 | [Section](screenshots/feed-trail-stories-in-motion-90190a52--editorial-caption-banner.jpg) |
| Trail Stories: In Motion | `editorial-sidebar` | `home.editorial_sidebar.image_1_alt` | 678.00 × 813.59 | 0.8333:1 | [Section](screenshots/feed-trail-stories-in-motion-90190a52--editorial-sidebar.jpg) |
| Trail Stories: In Motion | `newsletter` | `home.newsletter.image_1_alt` | 329.00 × 329.00 | 1.0000:1 | [Section](screenshots/feed-trail-stories-in-motion-90190a52--newsletter.jpg) |
| Urban Phantom | `features-grid-mixed` | `home.features_grid_mixed.image_1_alt` | 361.33 × 361.33 | 1.0000:1 | [Section](screenshots/feed-urban-phantom-709c8612--features-grid-mixed.jpg) |
| Urban Phantom | `features-grid-mixed` | `home.features_grid_mixed.image_2_alt` | 361.33 × 361.33 | 1.0000:1 | [Section](screenshots/feed-urban-phantom-709c8612--features-grid-mixed.jpg) |
| Urban Phantom | `features-grid-mixed` | `home.features_grid_mixed.image_3_alt` | 361.34 × 361.34 | 1.0000:1 | [Section](screenshots/feed-urban-phantom-709c8612--features-grid-mixed.jpg) |
| Urban Phantom | `media-banner` | `home.media_banner.image_1_alt` | 1440.00 × 860.00 | 1.6744:1 | [Section](screenshots/feed-urban-phantom-709c8612--media-banner.jpg) |
| Vintage Birdy | `cta-split` | `home.cta_split.image_1_alt` | 640.00 × 480.00 | 1.3333:1 | [Section](screenshots/feed-vintage-birdy-e5914231--cta-split.jpg) |
| Vintage Birdy | `editorial-split` | `home.editorial_split.image_1_alt` | 640.00 × 520.00 | 1.2308:1 | [Section](screenshots/feed-vintage-birdy-e5914231--editorial-split.jpg) |
| Vintage Birdy | `footer-overlap-media` | `layout_footer.image_1_alt` | 1280.00 × 280.00 | 4.5714:1 | [Section](screenshots/feed-vintage-birdy-e5914231--footer-overlap-media.jpg) |
| Waymark Supply Co. | `editorial-split` | `home.editorial_split.image_1_alt` | 746.66 × 559.98 | 1.3334:1 | [Section](screenshots/feed-waymark-supply-co-20f6199d--editorial-split.jpg) |
| Waymark Supply Co. | `footer-asymmetric-display` | `layout_footer.image_1_alt` | 188.00 × 250.66 | 0.7500:1 | [Section](screenshots/feed-waymark-supply-co-20f6199d--footer-asymmetric-display.jpg) |
| Waymark Supply Co. | `media-banner` | `home.media_banner.image_1_alt` | 1440.00 × 620.00 | 2.3226:1 | [Section](screenshots/feed-waymark-supply-co-20f6199d--media-banner.jpg) |
| Wingtip Coffee Co. | `editorial-standfirst-banner` | `home.editorial_standfirst_banner.image_1_alt` | 1440.00 × 803.72 | 1.7917:1 | [Section](screenshots/feed-wingtip-coffee-co-5fd54365--editorial-standfirst-banner.jpg) |
| Wonderworks Studio | `cta-banner-mixed` | `home.cta_banner_mixed.image_1_alt` | 437.34 × 437.34 | 1.0000:1 | [Section](screenshots/feed-wonderworks-studio-ad24704d--cta-banner-mixed.jpg) |
| Wonderworks Studio | `editorial-mosaic` | `home.editorial_mosaic.image_1_alt` | 906.67 × 566.66 | 1.6000:1 | [Section](screenshots/feed-wonderworks-studio-ad24704d--editorial-mosaic.jpg) |
| Wonderworks Studio | `editorial-mosaic` | `home.editorial_mosaic.image_2_alt` | 789.33 × 443.98 | 1.7778:1 | [Section](screenshots/feed-wonderworks-studio-ad24704d--editorial-mosaic.jpg) |
| Wonderworks Studio | `editorial-mosaic` | `home.editorial_mosaic.image_3_alt` | 554.67 × 443.98 | 1.2493:1 | [Section](screenshots/feed-wonderworks-studio-ad24704d--editorial-mosaic.jpg) |
| Wonderworks Studio | `features-overlap-statement` | `home.features_overlap_statement.image_1_alt` | 769.33 × 528.91 | 1.4546:1 | [Section](screenshots/feed-wonderworks-studio-ad24704d--features-overlap-statement.jpg) |
| Work/Life Curated | `content-portrait-story` | `home.content_portrait_story.image_1_alt` | 584.00 × 700.80 | 0.8333:1 | [Section](screenshots/feed-work-life-curated-d6bf2fc9--content-portrait-story.jpg) |
| Work/Life Curated | `cta-overlap` | `home.cta_overlap.image_1_alt` | 1440.00 × 820.00 | 1.7561:1 | [Section](screenshots/feed-work-life-curated-d6bf2fc9--cta-overlap.jpg) |
| Woven Journeys | `editorial-carousel` | `home.editorial_carousel.image_1_alt` | 372.00 × 232.50 | 1.6000:1 | [Section](screenshots/feed-woven-journeys-9bb09915--editorial-carousel.jpg) |
| Woven Journeys | `editorial-carousel` | `home.editorial_carousel.image_2_alt` | 372.00 × 232.50 | 1.6000:1 | [Section](screenshots/feed-woven-journeys-9bb09915--editorial-carousel.jpg) |
| Woven Journeys | `editorial-carousel` | `home.editorial_carousel.image_3_alt` | 372.00 × 232.50 | 1.6000:1 | [Section](screenshots/feed-woven-journeys-9bb09915--editorial-carousel.jpg) |
| Woven Journeys | `editorial-carousel` | `home.editorial_carousel.image_4_alt` | 372.00 × 232.50 | 1.6000:1 | [Section](screenshots/feed-woven-journeys-9bb09915--editorial-carousel.jpg) |
| Woven Journeys | `editorial-profile-cards` | `home.editorial_profile_cards.image_1_alt` | 373.33 × 466.66 | 0.8000:1 | [Section](screenshots/feed-woven-journeys-9bb09915--editorial-profile-cards.jpg) |
| Woven Journeys | `editorial-profile-cards` | `home.editorial_profile_cards.image_2_alt` | 373.33 × 466.66 | 0.8000:1 | [Section](screenshots/feed-woven-journeys-9bb09915--editorial-profile-cards.jpg) |
| Woven Journeys | `editorial-profile-cards` | `home.editorial_profile_cards.image_3_alt` | 373.34 × 466.67 | 0.8000:1 | [Section](screenshots/feed-woven-journeys-9bb09915--editorial-profile-cards.jpg) |
| Woven Journeys | `features-asymmetric` | `home.features_asymmetric.image_1_alt` | 576.00 × 360.00 | 1.6000:1 | [Section](screenshots/feed-woven-journeys-9bb09915--features-asymmetric.jpg) |
| Zenith Motion | `content-story-tiles` | `home.content_story_tiles.image_1_alt` | 640.00 × 853.33 | 0.7500:1 | [Section](screenshots/feed-zenith-motion-bb81c54d--content-story-tiles.jpg) |
| Zenith Motion | `content-story-tiles` | `home.content_story_tiles.image_2_alt` | 640.00 × 853.33 | 0.7500:1 | [Section](screenshots/feed-zenith-motion-bb81c54d--content-story-tiles.jpg) |
| Zenith Motion | `cta-columns-image` | `home.cta_columns_image.image_1_alt` | 640.00 × 853.33 | 0.7500:1 | [Section](screenshots/feed-zenith-motion-bb81c54d--cta-columns-image.jpg) |
| Zenith Motion | `cta-columns-image` | `home.cta_columns_image.image_2_alt` | 640.00 × 853.33 | 0.7500:1 | [Section](screenshots/feed-zenith-motion-bb81c54d--cta-columns-image.jpg) |
| Zenith Motion | `editorial-gallery-grid` | `home.editorial_gallery_grid.image_1_alt` | 426.66 × 568.88 | 0.7500:1 | [Section](screenshots/feed-zenith-motion-bb81c54d--editorial-gallery-grid.jpg) |
| Zenith Motion | `editorial-gallery-grid` | `home.editorial_gallery_grid.image_2_alt` | 426.67 × 568.89 | 0.7500:1 | [Section](screenshots/feed-zenith-motion-bb81c54d--editorial-gallery-grid.jpg) |
| Zenith Motion | `editorial-gallery-grid` | `home.editorial_gallery_grid.image_3_alt` | 426.66 × 568.88 | 0.7500:1 | [Section](screenshots/feed-zenith-motion-bb81c54d--editorial-gallery-grid.jpg) |

## Hidden at 1440px

These source slots are excluded from the visible desktop counts:

- Gold Accent Vitality / `editorial-sidebar` / `home.editorial_sidebar.image_1_alt`
- Gold Accent Vitality / `editorial-sidebar` / `home.editorial_sidebar.image_2_alt`
- Gold Accent Vitality / `editorial-sidebar` / `home.editorial_sidebar.image_3_alt`
