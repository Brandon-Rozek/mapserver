# Mapserver

A map tile server written using Flask and LeafletJS.

## Prerequisites
First you need to have map tile data. The easiest way to obtain this is to use KDE Marble and use the download maps feature.

## To Run
```bash
servemaps \
  --tile-path=~/.local/share/marble/maps/earth/openstreetmap \
  --port=9001
```

## References
I mainly referenced: https://medium.com/@Nithanaroy/create-your-own-tile-server-and-map-client-5f7515fff28

Other Useful links:
- https://wiki.openstreetmap.org/wiki/Zoom_levels
- https://stackoverflow.com/questions/9356724/google-map-api-zoom-range
- https://github.com/freayd/marble-maps/blob/master/earth/google-maps-satellite/google-maps-satellite.dgml
