# GeoJSON Web Map Lab — Starter

This repo contains two pages:

- `earthquake.html`: example that loads **earthquakes (points)** and **Japan counties (polygons)** with a sortable table by **magnitude**.
- `index.html`: your **deliverable**. Replace the sample datasets with two GeoJSON layers of your choice and pick a **different** Mapbox style than the earthquake page.

## Quick Start

1. **Add your Mapbox token**: open both HTML files and replace `YOUR_MAPBOX_ACCESS_TOKEN`.
2. **Add your data**: put GeoJSON files into `/assets/` (keep each file under **2 MB**).
3. **Test locally**: open `index.html` and `earthquake.html` using a local HTTP server.
4. **Publish** (GitHub Pages): push to GitHub → **Settings → Pages** → Source: `main`, folder: `/root`.

## URLs to check (after publishing)
- Deliverable: `https://<username>.github.io/<repo>/index.html`
- Earthquake example: `https://<username>.github.io/<repo>/earthquake.html`

## Notes
- The right side panel **hovers over** the map and **hides on widths < 1024px**.
- Use [mapshaper.org] to simplify heavy polygons and keep below the 2 MB limit.
- If your `japan.json` is TopoJSON, convert to GeoJSON (e.g., with mapshaper).