# Shopify product import

Use `products.csv` with Shopify Admin's native product CSV import.

## What it creates

- `Book A - NSW Font` as an active product at `22.95`
- `Book B - NSW Font` as an active product at `22.95`
- `Book A - Vic Font` as an active product at `22.95`
- `Book B - Vic Font` as an active product at `22.95`
- `Book A - Tas Font` as a draft product with price `0.00`
- `Book B - Tas Font` as a draft product with price `0.00`
- `Book C - Tas Font` as a draft product with price `0.00`

The Tas products are drafts because the source site did not show confirmed prices or product cover art for those books.

## After import

1. Review the imported products in Shopify Admin.
2. Confirm physical weights, inventory tracking, tax settings, and shipping rules.
3. Add Tas cover images and pricing before publishing Tas products.
4. The theme's default product template now includes the book-specific conversion sections, so imported products do not need a custom template assignment to get the new product-page layout.
5. The alternate `product.book` template is still available if you want to assign it manually later.

## Note about product templates

Shopify's native product CSV import does not assign custom product template suffixes. That is why the default product template has been updated to include the book-specific details, benefits, and FAQ sections.
