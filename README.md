# lass Project

## SHP -> GeoJSON

Installation:
```sh
sudo add-apt-repository ppa:ubuntugis/ppa
sudo apt-get update
sudo apt-get install gdal
```

Command:
```sh
ogr2ogr -f "GeoJSON" output.json source.shp
```

## GeoJSON -> TopoJSON

Installation:
```sh
sudo npm install -g topojson
```

Command:
```sh
geo2topo -o output.json source.json
```

