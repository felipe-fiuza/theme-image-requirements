# Product image slots — findings and recommendation

## Recommendation

Use **4:5 as the default portrait product-image format**. Leave space around the product so narrower slots can hide image edges without cutting off the item. Review the 33 flagged tall slots before deciding whether they need a dedicated taller source.

This is separate from the editorial/hero pipeline recommendation: product image counts are not included in the balanced or global non-product pools.

## Scope and coverage

- Viewport: 1440 × 1000 CSS pixels.
- All 97 themes checked; 94 contain explicitly product-linked slots.
- 420 visible product-linked image slots across 149 sections; no hidden slots or image-loading failures.
- 29 ratio groups, rounded to two decimal places.
- Outer image-slot proportions are measured in the live local Liquid renderer; intrinsic asset sizes are not used.
- Only slots explicitly linked to product records in template metadata are included. Images in commerce sections without that link are outside this audit.
- Counts are slot instances, including repeated cards; they are not unique products or generated-image requirements.

## Orientation

| Orientation | Slots | Share |
|---|---:|---:|
| Portrait | 369 | 87.9% |
| Square | 27 | 6.4% |
| Landscape | 24 | 5.7% |

Orientation uses the rounded ratio group: below 1.00 is portrait, 1.00 is square, above 1.00 is landscape.

## All measured product ratios

| Slot W:H | Slots | Themes |
|---|---:|---:|
| 0.80:1 | 184 | 49 |
| 0.75:1 | 97 | 26 |
| 0.67:1 | 42 | 11 |
| 1.00:1 | 27 | 6 |
| 0.60:1 | 20 | 5 |
| 0.56:1 | 11 | 3 |
| 0.83:1 | 7 | 3 |
| 1.06:1 | 4 | 1 |
| 1.33:1 | 3 | 3 |
| 0.78:1 | 2 | 1 |
| 1.25:1 | 2 | 2 |
| 0.72:1 | 2 | 1 |
| 0.58:1 | 2 | 1 |
| 1.94:1 | 2 | 2 |
| 0.94:1 | 1 | 1 |
| 1.83:1 | 1 | 1 |
| 1.80:1 | 1 | 1 |
| 1.78:1 | 1 | 1 |
| 0.70:1 | 1 | 1 |
| 1.20:1 | 1 | 1 |
| 1.42:1 | 1 | 1 |
| 1.44:1 | 1 | 1 |
| 1.50:1 | 1 | 1 |
| 2.12:1 | 1 | 1 |
| 1.67:1 | 1 | 1 |
| 2.03:1 | 1 | 1 |
| 1.60:1 | 1 | 1 |
| 1.02:1 | 1 | 1 |
| 2.10:1 | 1 | 1 |

## Does 4:5 fit better than 9:16?

Across the 369 portrait product slots:

| Measure | 4:5 source | 9:16 source |
|---|---:|---:|
| Average image area hidden | 6.2% | 24.6% |
| Slots hiding no more than 10% | 292 (79.1%) | 33 (8.9%) |

Each slot has equal weight in these averages. Cropping means area hidden by `object-fit: cover`; the original file is unchanged. Focal position changes which part is hidden, not how much. The calculations do not establish whether a particular product remains fully visible.

## Tall slots requiring review

**33 slots across 9 themes** are flagged: W/H below 0.64, meaning a 4:5 source hides more than 20% of its area with cover. This is an explicit review threshold, not a claim that every flagged placement fails.

| Theme | Section | Slot | Measured W:H | Area hidden with 4:5 |
|---|---|---|---:|---:|
| Court Culture | `product-ritual-trio` | `home.product_ritual_trio.image_1_alt` | 0.6000:1 | 25.0% |
| Court Culture | `product-ritual-trio` | `home.product_ritual_trio.image_2_alt` | 0.6000:1 | 25.0% |
| Court Culture | `product-ritual-trio` | `home.product_ritual_trio.image_3_alt` | 0.6000:1 | 25.0% |
| Glim | `commerce-product-lineup` | `home.commerce_product_lineup.image_1_alt` | 0.6000:1 | 25.0% |
| Glim | `commerce-product-lineup` | `home.commerce_product_lineup.image_2_alt` | 0.6000:1 | 25.0% |
| Glim | `commerce-product-lineup` | `home.commerce_product_lineup.image_3_alt` | 0.6000:1 | 25.0% |
| Glim | `commerce-product-lineup` | `home.commerce_product_lineup.image_4_alt` | 0.6000:1 | 25.0% |
| Modern Muse | `commerce-product-row` | `home.commerce_product_row.image_1_alt` | 0.5581:1 | 30.2% |
| Modern Muse | `commerce-product-row` | `home.commerce_product_row.image_2_alt` | 0.5581:1 | 30.2% |
| Modern Muse | `commerce-product-row` | `home.commerce_product_row.image_3_alt` | 0.5581:1 | 30.2% |
| Playful Function Atelier | `commerce-bundle-columns` | `home.commerce_bundle_columns.image_2_alt` | 0.5816:1 | 27.3% |
| Playful Function Atelier | `commerce-bundle-columns` | `home.commerce_bundle_columns.image_3_alt` | 0.5816:1 | 27.3% |
| Precision in Detail | `cta-asymmetric` | `home.cta_asymmetric.image_3_alt` | 0.6000:1 | 25.0% |
| Precision in Detail | `editorial-sidebar` | `home.editorial_sidebar.image_1_alt` | 0.6000:1 | 25.0% |
| Precision in Detail | `editorial-sidebar` | `home.editorial_sidebar.image_2_alt` | 0.6000:1 | 25.0% |
| Precision in Detail | `editorial-sidebar` | `home.editorial_sidebar.image_3_alt` | 0.6000:1 | 25.0% |
| Precision in Detail | `editorial-sidebar` | `home.editorial_sidebar.image_4_alt` | 0.6000:1 | 25.0% |
| Serene Sculpted Minimalism | `commerce-lookbook` | `home.commerce_lookbook.image_1_alt` | 0.6000:1 | 25.0% |
| Serene Sculpted Minimalism | `commerce-lookbook` | `home.commerce_lookbook.image_2_alt` | 0.6000:1 | 25.0% |
| Serene Sculpted Minimalism | `commerce-lookbook` | `home.commerce_lookbook.image_3_alt` | 0.6000:1 | 25.0% |
| Serene Sculpted Minimalism | `commerce-lookbook` | `home.commerce_lookbook.image_4_alt` | 0.6000:1 | 25.0% |
| Serene Sculpted Minimalism | `commerce-product-lineup` | `home.commerce_product_lineup.image_1_alt` | 0.6000:1 | 25.0% |
| Serene Sculpted Minimalism | `commerce-product-lineup` | `home.commerce_product_lineup.image_2_alt` | 0.6000:1 | 25.0% |
| Serene Sculpted Minimalism | `commerce-product-lineup` | `home.commerce_product_lineup.image_3_alt` | 0.6000:1 | 25.0% |
| Serene Sculpted Minimalism | `commerce-product-lineup` | `home.commerce_product_lineup.image_4_alt` | 0.6000:1 | 25.0% |
| Solé Swim | `commerce-product-index` | `home.commerce_product_index.image_1_alt` | 0.5558:1 | 30.5% |
| Solé Swim | `commerce-product-index` | `home.commerce_product_index.image_2_alt` | 0.5558:1 | 30.5% |
| Solé Swim | `commerce-product-index` | `home.commerce_product_index.image_3_alt` | 0.5558:1 | 30.5% |
| Solé Swim | `commerce-product-index` | `home.commerce_product_index.image_4_alt` | 0.5558:1 | 30.5% |
| Waveform | `hero-mixed-type-strip` | `home.hero_mixed_type_strip.image_1_alt` | 0.5581:1 | 30.2% |
| Waveform | `hero-mixed-type-strip` | `home.hero_mixed_type_strip.image_2_alt` | 0.5581:1 | 30.2% |
| Waveform | `hero-mixed-type-strip` | `home.hero_mixed_type_strip.image_3_alt` | 0.5581:1 | 30.2% |
| Waveform | `hero-mixed-type-strip` | `home.hero_mixed_type_strip.image_4_alt` | 0.5581:1 | 30.2% |

## Evidence

- [Products page — tall slots only](../products.html?view=table&tall=1)
- [Products page — all slots](../products.html)
- [Exact measured data](rendered-1440.json)
- [Measurements CSV](rendered-1440.csv)
- [Main non-product pipeline recommendations](../all-slot-analysis/pipeline-recommendation.md)
