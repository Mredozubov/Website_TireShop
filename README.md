# Galaxy Tire Shop

Simple static website. No dependencies or build step required.

## GitHub Pages

Live site: https://mredozubov.github.io/Website_TireShop/

The repository's Pages source is **GitHub Actions**. `.github/workflows/static.yml` publishes only `dist/` whenever changes are pushed to `main`, and also supports a manual run from the Actions tab. All asset paths are relative so the site works under the repository URL. The site needs no server, API keys, or Sites account on GitHub Pages.

For local preview, run `python3 -m http.server 8765 --directory dist` and visit http://localhost:8765/.

The workshop image is cropped and zoomed with CSS for the hero. About Us uses large nighttime storefront, tire-motorcycle, and thumbs-up photographs. Original assets remain intact. Contact links use `tel:` and Google Maps; no contact form backend is needed.

Reference structure: https://manhattanautoinc.com/
Business address and phone verified against https://thelocavore.com/directory/galaxy-tire-shop and https://maps.roadtrippers.com/us/new-york-ny/services/galaxy-tire-shop-24-7 . Hours and listed services also appear on the supplied storefront signs. No invented reviews, certifications, experience claims, or warranties.
