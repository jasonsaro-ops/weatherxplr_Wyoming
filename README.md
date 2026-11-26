# WEATHERXPLR · Tie Siding 82084

Local WeatherXplr board for Tie Siding / ZIP 82084 (Albany County, WY — CYS CWA).

## Layout
- **Left rail** — sample point, current conditions, gauges, AQI
- **Center** — dual Windy maps (radar + wind); secondary column bottom = **NWS alerts** (82084 point + SE Wyoming / Laramie area)
- **Right rail** — 10-day forecast, temp / PoP / wind sparklines, tides (none local), Laramie River hydro

## Features
- Dual Windy embeds (layer selectors)
- NWS alerts for **82084 + Tie Siding / Laramie / Albany County** (CYS CWA)
- Current conditions (Open-Meteo) + 48h sparklines
- Air quality (Open-Meteo) + 48h AQI / PM2.5 sparklines
- Hydro — USGS Laramie / SE Wyoming gauges:
  - Laramie River at Laramie `06660000`
  - Laramie River near Fort Laramie `06670500`
  - Medicine Bow River near Hanna `06635000`
  - N. Platte River near Sinclair `06630000`
  - N. Platte River at Orin `06652000`
- Tides: none (inland high plains)
- Click **WEATHERXPLR** (top left) to refresh data and recenter Windy maps on 82084

## Deploy
Static site — GitHub Pages. No worker required.

## Files
| Path | Role |
|------|------|
| `index.html` | Board UI |
| `app.js` | Feeds + dual Windy + alerts + sparks + tides + hydro |
