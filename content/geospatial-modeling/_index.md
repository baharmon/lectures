+++
title = "Geospatial Modeling"
outputs = ["Reveal"]
+++

{{< slide background-image="manhattan.png" >}}
# Geospatial Modeling

Brendan Harmon

<img height="50px" src="lsu-coad-logo.png">

---

# Paradigms of Science
* Empirical
* Theoretical
* Computational
* Data

---

# Geospatial Modeling & Analysis
* Geomorphometry
* Ecology
* Etc...

---

# Geospatial Simulation
* Urbanization
* Hydrology
* Ecological corridors
* Etc...

---

# Geomorphometry

Quantitative analysis of the earth's surface

---

## Lidar

**Location:** New Orleans, Louisiana

**Dataset:** [U.S. Army Corps of Engineers 2012 Lidar Survey of New Orleans](https://coast.noaa.gov/htdata/lidar2_z/geoid12b/data/6350/)

**Software:** GRASS GIS, Rhino, RhinoTerrain, & Thea Render

---

{{< slide background-image="new-orleans.png" >}}

---

{{< slide background-iframe="https://sketchfab.com/models/beafaa4e67874401a20e6a9356764702/embed?autostart=1&amp;ui_controls=1&amp;ui_infos=1&amp;ui_inspector=1&amp;ui_stop=1&amp;ui_watermark=1&amp;ui_watermark_link=1" >}}

---

## Laser Scanning

**Location:** [LSU Art & Design Quad](https://skfb.ly/6VW7w), Baton Rouge, LA

**Author:** [Brendan Harmon](https://baharmon.github.io/) et al.

**System:** Faro Focus Laser Scanner

**Software:** CloudCompare

---

{{< slide background-iframe="https://sketchfab.com/models/18e50ba68fc647fea58134bdff26c19a/embed?autostart=1&amp;ui_controls=1&amp;ui_infos=1&amp;ui_inspector=1&amp;ui_stop=1&amp;ui_watermark=1&amp;ui_watermark_link=1" >}}

---

## Drone Photogrammetry

**Location:** Lake Wheeler, Raleigh, NC

**Author:** Justyna Jeziorska, [NCSU GeoForAll Lab](https://geospatial.ncsu.edu/geoforall/)

**System:** UX5 Drone

**Software:** Metashape

---

{{< slide background-iframe="https://sketchfab.com/models/75a5bbc788304607ab25c368e5a6f2ec/embed?autostart=1" >}}

---

{{< slide background-image="elevation.png" background-size="contain" background-repeat="no-repeat" >}}
## Digital Elevation Model

---

{{< slide background-image="slope.png" background-size="contain" background-repeat="no-repeat" >}}
## Slope

---

{{< slide background-image="geomorphons-legend.png" background-size="contain" background-repeat="no-repeat" >}}
## [**Geomorphons**](https://doi.org/10.1016/j.geomorph.2012.11.005)

---

{{< slide background-image="geomorphons.png" background-size="contain" background-repeat="no-repeat" >}}
## Geomorphons

---

{{< slide background-image="ridges.png" background-size="contain" background-repeat="no-repeat" >}}
## Geomorphons: Ridges

---

{{< slide background-image="convergence.png" background-size="contain" background-repeat="no-repeat" >}}
## Topographic Convergence

---

{{< slide background-image="ridgelines.png" background-size="contain" background-repeat="no-repeat" >}}
## Topographic Convergence: Ridges

---

# Ecological Analytics

---

## Multispectral Drone Photogrammetry

**Location:** Hilltop Arboretum, Baton Rouge, LA

**Author:** Brendan Harmon

**System:** FireFLY Pro with Micasense RedEdge

**Software:** Metashape, GRASS GIS, Python

---

{{< slide background-image="hilltop-wildflowers.jpg" >}}
## Coastal Tallgrass Prairie Ecosystem

---

{{< slide background-image="firefly-takeoff.jpg" >}}
## Aerial Survey

---

{{< slide background-image="drone-data-analytics.png" >}}

---

{{< slide background-image="hilltop-point-cloud.jpg" >}}

---

{{< slide background-image="multispectral_2020_03_19.png" >}}
## 2020-03-19

---

{{< slide background-image="multispectral_2020_04_25.png" >}}
## 2020-04-25

---

{{< slide background-image="multispectral_2020_06_01.png" >}}
## 2020-06-01

---

{{< slide background-image="multispectral_2020_06_30.png" >}}
## 2020-06-30

---

{{< slide background-image="multispectral_2020_08_03.png" >}}
## 2020-08-03

---

{{< slide background-image="multispectral_2020_08_29.png" >}}
## 2020-08-29

---

{{< slide background-image="multispectral_2020_09_27.png" >}}
## 2020-09-27

---

{{< slide background-image="multispectral_2020_10_25.png" >}}
## 2020-10-25

---

{{< slide background-image="multispectral_2021_01_24.png" >}}
## 2021-01-24

---

{{< slide background-image="biomass-2020.png" >}}
## Biomass 2020

---

## Volume 2020-2021
![Volume Plot 2020-2021](volume-plot-2020.png)

---

## Carbon 2020
* Aboveground carbon stock: 2,900 $kgC$
* Belowground carbon stock: 29,820 $kgC$
* Carbon stock: 32,721 $kgC$
* Carbon pool: 7,047 $gC/m^{2}$

---

## Research Questions
* What is the carbon pool of the meadow?
* How will the carbon pool change as the meadow matures?
* Can designed meadows be effective stores of carbon?
* How can drone data analytics inform management?

---

# Urban Growth Simulation

---

## [FUTURES](https://cnr.ncsu.edu/geospatial/research/futures/)

<img height="50px" src="ncsu-logo.png">
<img height="50px" src="ncsu-cga-logo.png">

The **[FUTure Urban-Regional Environment Simulation (FUTURES)](https://cnr.ncsu.edu/geospatial/research/futures/)**
is regional scale model for simulating the conversion of rural to urban land
based on a potential submodel, per capita demand submodel,
and a patch growing algorithm.

---

## FUTURES
| Submodel | Predictors |
|---|---|
| Development pressure | Protected areas |
|  | Slope |
|  | Roads |
|  | Water |
|  | Forest |
|  | City center |
| Demand | Population statistics |
| Patch growing algorithm | Historic urbanization |

---

{{< slide background-image="futures-baseline.png" background-size="contain" background-repeat="no-repeat" >}}

---


{{< slide background-image="futures-sprawl.png" background-size="contain" background-repeat="no-repeat" >}}

---

{{< slide background-image="futures-infill.png" background-size="contain" background-repeat="no-repeat" >}}

---

{{< slide background-image="baseline-2017-2042.gif" background-size="contain" background-repeat="no-repeat" >}}

---

## FUTURES
* Where is growth happening?
* Where is growth predicted?
* How should we rethink development?

---

# Hydrological Simulation

---

## [SIMWE](https://grass.osgeo.org/grass78/manuals/r.sim.water.html)
The Simulation of Water Erosion **(SIMWE)**
simulates shallow flows of water and sediment over landscapes.

---

{{< slide background-image="discharge.gif" >}}
## Shallow Water Flow Discharge
## $$(m^3/s)$$

---

{{< slide background-image="ndvi.png" >}}
## Normalized Difference Vegetation Index (NDVI)

---

{{< slide background-image="discharge-with-ndvi.png" >}}
## Shallow Water Flow Discharge with Landcover from NDVI
## $$(m^3/s)$$

---

# Ecological Corridor Simulation

---

## [LSCorridors](https://github.com/LEEClab/LS_CORRIDORS)

**Spatial Ecology and Conservation Lab (LEEC), Sao Paulo State University**

LandScape Corridors (LSCorridors)
simulates multiple functional ecological corridors
based on species movement and landscape connectivity.
*https://doi.org/10.1111/2041-210X.12750*

---

# Giant Panda Habitat Corridors

**Location:** Sichuan, China

**Team:** Andrew Wright, Tanvi Shah, & Brendan Harmon

**Software:** GRASS GIS & LSCorridors

**Research Question:** What land needs to be protected to ensure the long-term survival of Giant Pandas?

---

{{< slide background-image="gpnp-1.jpg" background-size="contain" background-repeat="no-repeat" >}}

---

{{< slide background-image="gpnp-2.jpg" >}}

---

# Software

| Program | Applications | Open Source |
|---|---|---|
| [QGIS](https://qgis.org/) | GIS | ✔ |
| [GRASS GIS](https://grass.osgeo.org/)| GIS & remote sensing | ✔ |
| [SAGA GIS](http://www.saga-gis.org/) | GIS | ✔ |
| [ArcGIS](https://www.esri.com/) | GIS | |
| [TerrSet](https://clarklabs.org/) | GIS & remote sensing | |
| [ERDAS Imagine](https://www.hexagongeospatial.com/products/power-portfolio/erdas-imagine) | remote sensing | |
| [Metashape](https://www.agisoft.com/) | photogrammetry | |
| [Pix4D](https://www.pix4d.com/) | photogrammetry | |
| [Google Earth](https://www.google.com/earth/) | virtual globe | |
| [Leaflet](https://leafletjs.com/) | web mapping | ✔ |
| [Mapbox](mapbox.com) | web mapping | |

---

# Generative Design

Integrate geospatial modeling into the design process with Grasshopper

* Terrain modeling & grading with [Docofossor](https://www.food4rhino.com/app/docofossor)
* Terrain modeling with [Bison](https://www.food4rhino.com/app/bison)
* Terrain modeling with [RhinoTerrain](https://www.rhinoterrain.com/)
* Vector mapping with [Mosquito](http://www.synthetic.space/synthetic/2443/)

---

{{< slide background-image="docofossor.png" >}}
## Docofossor

---

{{< slide background-image="rhinoterrain.png" >}}
## RhinoTerrain

---

# Learn More

* [**Geospatial Modeling and Analysis**](https://ncsu-geoforall-lab.github.io/geospatial-modeling-course/), Helena Mitasova, NCSU
* [**GIS for Designers**](https://baharmon.github.io/gis-for-designers), Brendan Harmon, LSU
* [**QGIS for Hydrological Applications**](https://www.youtube.com/c/HansvanderKwast/), Hans van der Kwast, IHE Delft
