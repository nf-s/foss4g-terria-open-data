# Rough Notes

##

- What am I actually trying to show?
  - [ ] Using our existing map to show user data?
  - [ ] Build a map with curated data?
  - [ ] Adding plugins/workflow functionality?

### Which open data portals does Terria “unlock”

What do you get when Terria connects to a portal?

Would it be better to use portal interface?

- CKAN, Socrata…
  - not really, as the official interface is much better
- STAC
  - Probably
- SDMX
  - Yes
- OpenDataSoft
  - Yes
- WPS/WMS
- Download drag and drop

### Using existing map

- Go to map.terria.io
- Add data portal
  - CKAN?
    - Maybe not
  - Socrata?
    - Maybe just navigate to download file and then drag-drop
  - OpenDataSoft
  - SDMX
  - STAC
    - Requires https://github.com/GeoTIFF/georaster-layer-for-leaflet
  - WMS - WCS?
  - WFS - export
  - WPS
- Search data
- Visualise
  - Edit region mapping?
  - Join with region geoJSON?
  - Edit styling
- Analyse
  - Qualitative
    - Compare imagery
    - Moment chart -
    - Expand two time-series
  - Quantitative
    - Add WPS
    - Aggregate point dataset over region?
      - Eg show sum of value across time - in region
    - Raster/vector intersection
- Share map!

### Limitations

CORS

Web-browser

search

data size…

API implementation may not be complete - or some assumptions

- CSW
- SDMX

Some of this is brand new

### Create your own map!

- Export user catalog?
- instructions to clone repo
- Add JSON catalog
- Styling!
  - CZML
- 3D data
- Search index
- Curate datasets

### Extend map functionality

- Line of sight plugin…
- Scene editor plugin
- Develop your own catalog groups/items!

### Technical stuff?

Talk about Terria model layer?

Table styling…

### What is coming next!

Talk about new SaaS?

Magda- server side
