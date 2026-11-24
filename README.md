# Image requirements

Interactive analysis of image-slot requirements across 97 Liquid themes at a 1440px viewport.

## Website

https://theme-image-requirements.quick.shopify.io

Quick requires Shopify authentication. This is a static snapshot; no source Liquid templates or credentials are included.

## Run locally

```sh
python3 -m http.server 8080 --directory public
```

Open http://localhost:8080. No install or build step is needed.

## Pages

- Recommendations: balanced and global non-product image pools, current production comparison, and utilization.
- General analysis: 421 non-product slots.
- Heroes: 146 slots.
- Other sections: 275 visible slots.
- Products: 420 product-linked slots, orientation filters and tall-slot flags.
- Placement lab: five asset collections, source-format assignments and interactive cover previews.

## Deploy to Quick

```sh
quick deploy public theme-image-requirements
```

## Data and limitations

Measurements describe current rendered content at 1440 × 1000 CSS pixels. Products are identified by explicit template metadata links. Non-product pool recommendations exclude products. See the Markdown findings and JSON/CSV evidence in `public/` for scope, thresholds, and assumptions. The optional 21:9 top-up strategy is described in this conversation but the recommendation document still reflects the original four-format pool.

This repository contains generated static outputs. Rebuilding the original measurements requires the separate local Liquid renderer and source audit workspace; those machine-specific tools are intentionally excluded.
