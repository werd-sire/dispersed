# Dispersed Camping Finder

Interactive map applications for finding free dispersed camping sites on public lands in the United States.

## Available Maps

- **[Minnesota](mn.html)** - 24 known + 10 risky dispersed camping sites
- **[Utah](ut.html)** - 46 known + 25 risky dispersed camping sites

## Features

### Interactive Layers
- **Federal & State Lands**: National Forests, BLM land, State Forests, National Parks, Wilderness Areas
- **Roads & Trails**: Forest roads, 4WD tracks, and hiking trails from OpenStreetMap
- **Camping Sites**:
  - ⛺ **Known Sites**: Well-documented, frequently used locations with verified access
  - ⚠️ **Risky Sites**: Limited information - verify before visiting
- **Dark Sky Areas**: Locations with minimal light pollution for stargazing
- **3-Day Weather Forecast**: Click anywhere on the map to get local weather

### Base Maps
- Topographic
- Street Map
- Satellite Imagery

## Usage

Simply open the HTML file for your desired state in a web browser. No installation or server required - everything runs client-side.

### Controls
- Use checkboxes in the right panel to toggle map layers
- Click on markers, roads, or land areas for detailed information
- Toggle weather forecast and click the map to get 3-day forecasts
- Switch between base map types using the control in the bottom-right

## Data Sources

- **Land boundaries**: Manually researched and defined polygons
- **Camping sites**: Research-verified locations from USFS, BLM, state agencies, and camping communities (TheDyrt, Campendium, iOverlander, etc.)
- **Roads & trails**: Real-time data from OpenStreetMap via Overpass API
- **Weather**: Open-Meteo API

## Site Classifications

### Known Sites (⛺)
Well-documented dispersed camping locations with:
- Confirmed access and directions
- Multiple source verification
- Detailed amenity information
- Access requirements (2WD, 4WD, HC, etc.)

### Risky Sites (⚠️)
Potential dispersed camping areas with limited information:
- Uncertain legal status
- Conflicting reports
- Limited documentation
- Access challenges

**Always scout risky sites in daylight and have a backup plan.**

## Important Notes

- Dispersed camping regulations vary by location - check current rules before camping
- Practice Leave No Trace principles
- Many sites have 14-day limits
- Road conditions can change with weather
- Cell service is limited in remote areas

## Technology Stack

- [Leaflet.js](https://leafletjs.com/) - Interactive mapping
- [OpenStreetMap](https://www.openstreetmap.org/) - Road and trail data
- [Overpass API](https://overpass-api.de/) - OSM data queries
- [Open-Meteo](https://open-meteo.com/) - Weather forecasts
- Vanilla JavaScript, HTML, CSS - No build process required

## License

This project is open source. Camping site data compiled from public sources.
