+++
title = "A Very Short Introduction to Geodesy"
outputs = ["Reveal"]
+++

# A Very Short Introduction to Geodesy

### The science of the shape of the Earth

Brendan Harmon

<img height="50px" src="lsu-coad-logo.png">

---

# Datum

A geodetic datum is a coordinate system and a reference surface.
Important examples include:
* World Geodetic System 1984 (WGS84)
* North American Datum of 1983 (NAD83)
* North American Vertical Datum 1988 (NAVD88)

---

{{< slide background-image="emg-shaded-relief.png" >}}
# Geoid

A model of mean global sea level based on gravitational potential.
The geoid represents mean sea level without winds, currents, and tides
through both oceans and continents.
The geoid is used as a vertical datum for measuring
orthometric height above sea level.

---

{{< slide background-video="geoid.mp4" >}}
# [Geoid](https://svs.gsfc.nasa.gov/3655)

[NASA Scientific Visualization Studio]((https://svs.gsfc.nasa.gov/3655))

---

{{< slide background-image="emg-shaded-relief.png" >}}
# GRASS Commands

To map the geoid in [GRASS GIS](https://grass.osgeo.org/),
download
[EGM08_25.prj](http://schorsch.efi.fh-nuernberg.de/data/terrain/EGM/EGM08_25.prj)
and
[EGM08_25.tif](http://schorsch.efi.fh-nuernberg.de/data/terrain/EGM/EGM08_25.tif).
Then create a new GRASS location from
[EGM08_25.prj](http://schorsch.efi.fh-nuernberg.de/data/terrain/EGM/EGM08_25.prj).
```
g.region n=90:00:00N s=90:00:00S e=360:00:00E w=00:00:00W
r.in.gdal -r input=EGM08_25.tif output=emg
r.colors map=emg color=viridis
r.relief input=emg output=relief zscale=500
r.shade shade=relief color=emg output=shade brighten=50
d.legend raster=emg at=5,35,2,3 font=Lato-Regular fontsize=16
```

---

# Ellipsoid
The World Geodetic System 1984 (WGS84)
uses the Earth Gravitational Model 1996 (EMG96)
as its geoid reference.
the Global Positioning System (GPS) uses WGS84
as its coordinate reference system (CRS)

---

# Map Projections

A map projection transforms a globe into a planar map that can be measured.

---

{{< slide background-iframe="https://earth.nullschool.net/#current/wind/surface/level/orthographic" >}}

---

{{< slide background-iframe="https://earth.nullschool.net/#current/wind/surface/level/equirectangular" >}}

---

{{< slide background-iframe="https://earth.nullschool.net/#current/wind/surface/level/waterman" >}}

---

{{< slide background-iframe="https://xkcd.com/977/" >}}

---

{{< slide background-iframe="https://www.jasondavies.com/maps/transition/" >}}

---

# Universal Transverse Mercator

The Universal Transverse Mercator (UTM)
coordinate system divides the world into
60 longitudinal zones and 20 latitudinal zones,
6 degrees wide and 12 degrees tall.

---

{{< slide background-image="universal-transverse-mercator.jpg" >}}
# Universal Transverse Mercator

---

# State Plane Coordinate System
The State Plane Coordinate System of 1983
is based on the North American Datum of 1983 (NAD 83).
Each state in the US has at least one zone
in either the Transverse Mercator,
Lambert Conformal Conic, or
Oblique Mercator projection.
To reduce distortion, many states have multiple zones.

---

{{< slide background-image="noaa-geodesy-state-plane.png" >}}

---

# Course Datasets

* [Natural Earth Dataset](https://doi.org/10.5281/zenodo.3762808): WGS84
* [Governor's Island Dataset](http://doi.org/10.5281/zenodo.3940780): NAD 83, NY Long Island State Plane Feet

---

{{< slide background-image="world-rivers.png" >}}

# Natural Earth
### WGS84

---

{{< slide background-image="governors-island-landcover.png" >}}

# Governor's Island
### NY Long Island State Plane Feet
