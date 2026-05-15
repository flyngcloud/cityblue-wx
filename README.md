# wx.cityblue.com

Live weather, radar, wind, and alerts for Wichita and the central plains. A community service from City Blue Print, Inc. — no ads, no tracking, no data collection.

## Stack
- Single-file static site (`index.html`)
- Cloudflare Pages
- Custom domain: wx.cityblue.com

## Data sources
- National Weather Service (`api.weather.gov`) — forecast, alerts, surface observations, Area Forecast Discussion
- Iowa Environmental Mesonet — NEXRAD radar tiles (CONUS mosaic, 12 frames over 55 minutes)
- CartoDB Dark Matter — dark basemap
- Sunrise/sunset computed client-side (NOAA algorithm)

## Local preview
Open `index.html` in any browser. No build step.

## Deploy
Push to `main` → Cloudflare Pages picks up automatically.
