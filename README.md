# con.fyi

Static, public-facing legal and product-information pages for Open Growth Group products.

## Structure

```text
assets/
  brand/
    confyi-post-lockup.png
  site.css
con-fyi-post/
  index.html
  terms-of-service/
    index.html
```

Product pages live at `/<product>/`. Legal pages live below the product, so each social-provider application can use a stable, product-specific URL such as:

- `https://con.fyi/con-fyi-post/`
- `https://con.fyi/con-fyi-post/terms-of-service/`

Add future products and legal documents using the same structure. Pages are intentionally dependency-free static HTML so they can be served by any static web container. Product brand assets belong in `assets/brand/`; shared layout assets belong directly under `assets/`.
