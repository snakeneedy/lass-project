# lass Project

OS: Ubuntu 14.04 LTS

## SHP → GeoJSON

### Installation

Ubuntu packages:
(ref. http://packages.ubuntu.com/zh-tw/precise/gdal-bin)
```sh
sudo apt-get install gdal-bin
```

via PPA:
(ref. https://launchpad.net/~ubuntugis/+archive/ubuntu/ppa)
```sh
sudo add-apt-repository ppa:ubuntugis/ppa
sudo apt-get update
sudo apt-get install gdal
```

### Command

```sh
ogr2ogr -f "GeoJSON" output.json source.shp
```

## GeoJSON → TopoJSON

### Installation

```sh
sudo npm install -g topojson
```

### Command

```sh
geo2topo -o output.json source.json
```

