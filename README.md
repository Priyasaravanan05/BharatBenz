# BharatBenz

## BharatBenz Certified & Exchange

Standalone pages in `certified/` (assets in `assets/certified/`):

- `certified/index.html` — Certified & Exchange landing page (banner, journey, Buy / Sell / Exchange enquiry with OTP steps, key features, latest 8 trucks; customer stories section hidden until content is ready)
- `certified/dealer-locator.html` — Certified & Exchange network map with state/city filters and dealer list
- `certified/truck-listing.html` — full truck listing with Location / Model filters, sorting and Load More

Notes: dealer locations are sample data; truck listings were taken from bharatbenz.com/buy-second-hand-trucks; the India map is an indicative illustration (use Survey of India–approved map data for production).

## Select My Truck

Self-contained page in `select-my-truck/` (assets in `select-my-truck/assets/`), deployed as its own Netlify project (`bharatbenz-select-my-truck`, base directory `select-my-truck`):

- `select-my-truck/index.html` — Select My Truck listing page (hero, 16 applications with search, Why BharatBenz, FAQ, Select My Truck application/sub-application search, quick actions, footer)
- `select-my-truck/agricultural-produce/index.html` — Agricultural Produce application page with final SEO content (meta, canonical, hreflang, breadcrumb + FAQ schema), Food Grains / Fruits and Vegetables sub-application cards, featured models with specs, Why BharatBenz, FAQ. Assets in `select-my-truck/assets/agricultural-produce/`. Linked from the listing card via `BUILT` in the listing script.

Notes: truck photos, hero and logos are cropped from the design screenshot — replace with originals (same file names). Sub-application options are filled per application in `SUBS` in the listing script (Agricultural Produce done). Body copy is placeholder text from the design.

Agricultural Produce notes: truck thumbnails (1617R, 2826R, 3526R, 3832R) load directly from bharatbenz.com (`uploads/truck_images/product_types/`); the 1415R has no thumbnail on bharatbenz.com, so it keeps the grey truck outline placeholder. Sub-application pages and the 3832R / 1415R model URLs are not built yet, so those links point to bharatbenz.com.
