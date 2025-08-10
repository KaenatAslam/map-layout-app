# Map Layout App (React + Leaflet)

This is a lightweight React + Vite project with Leaflet map, search box (leaflet-geosearch), custom markers, sidebar, and polylines (paths).
Replace `src/config.js` to change locations and paths easily.

## Quick start

1. Install dependencies
```bash
npm install
# or
yarn
```

2. Run dev server
```bash
npm run dev
```

3. Open http://localhost:5173

## Notes
- Icons: Add your icons to `public/icons/` (office.png, warehouse.png, client.png). Also add Leaflet marker files if needed (marker-icon.png, marker-icon-2x.png, marker-shadow.png).
- To deploy on Vercel, push this repo to GitHub and import on Vercel (automatic for Vite apps).

## Replace locations and paths
Edit `src/config.js` and change the LOCATIONS and PATHS arrays. Each location needs `lat`, `lng`, `name`, `desc` and optional `icon` (path under /public).