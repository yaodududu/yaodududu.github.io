# Yao Du academic homepage · GitHub Pages

Deploy: upload `index.html` to the root of the public `yaodududu.github.io` repository and enable Settings → Pages → Deploy from a branch → main → /(root).

## Travel map

The map uses Leaflet and CARTO/OSM tiles (no Google Maps API key or billing required). Internet access is necessary to load map tiles and the Leaflet CDN. Map points **are schematic approximations inferred from the screenshot, not verified personal travel records**. Do not treat these as actual visited locations.

To replace the data, edit `internationalPoints` and `provincePoints` in `index.html` (or replace their combined `points` array with your actual records). For any location with images, set type to `photo`, add `photos: ['images/your-photo.jpg']` in a point record, and upload images into an `images/` folder. The photo viewer shows a placeholder until real photos are added. Do not claim 46 verified locations / 28 provinces or 10 actual photos until source data have been recovered.
