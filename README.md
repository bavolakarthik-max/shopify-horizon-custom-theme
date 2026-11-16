# Shopify Horizon Custom Theme

Custom development on Shopify's Horizon theme for a demo clothing store.

## Custom work
- **Trust badges section** (`sections/trust-badges.liquid`): custom section with
  configurable heading, background color, columns, and repeatable badge blocks.
  Responsive grid (4 per row on desktop, 2 on mobile).
- **Product specs block** (`blocks/product-specs.liquid`): Horizon theme block that
  renders product metafields (fabric, fit, care) and a size chart that only
  appears on products with a Size option.

## Store setup
- 10 products / 60+ variants, bulk-imported via product CSV
- Smart collections (tag and price conditions), multi-level navigation
- Market-based shipping rules, discount codes, tested checkout

## Tech
Liquid · HTML · CSS · JSON schema · Shopify CLI · Git