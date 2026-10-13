# Shopify Collection Bundles Section

A configurable Online Store 2.0 section for presenting curated product bundles or featured collections as responsive cards.

The original version was developed for the Aromatto coffee storefront. This repository contains a reusable version that can be configured entirely in Shopify's theme editor.

## Features

- Up to three collection cards
- Theme-editor collection selection
- Configurable badge, savings label and button text per card
- Collection-image and product-image fallback
- Shopify money formatting
- Section-level colors and spacing controls
- Responsive desktop and mobile layouts
- Empty editor placeholders for easier setup
- Block-level Shopify editor controls

## Installation

1. Add `homepage-bundles.liquid` to the theme's `sections` directory.
2. Open the Shopify theme editor.
3. Add **Collection bundles** to the desired template.
4. Add a block for each bundle and select its collection.
5. Configure the badge, savings label and button text.
6. Adjust the section heading, colors and spacing as needed.

## Implementation Notes

Each card uses the selected collection's image. If the collection has no image, the section falls back to the first product's featured image. Pricing is taken from the first product in the collection and formatted with Shopify's `money` filter.

The component is designed as a portable theme section. Final spacing and typography may still need small adjustments to match the target theme.

## Preview

<img width="1887" height="718" alt="Collection bundle cards on the Aromatto storefront" src="https://github.com/user-attachments/assets/d09e7b36-11f8-4880-a05c-ab1bb65f5cb0" />
