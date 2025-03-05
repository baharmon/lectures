+++
title = "Temporal GIS for Drone Data"
outputs = ["Reveal"]
+++

# Temporal GIS

### for Drone Data

Brendan Harmon

<img height="50px" src="../images/lsu-coad-logo.png" alt="lsu college of art and design logo">

---

# Temporal Framework for GIS

* Database for time series of spatial data
* Temporal datasets, processing, visualization, and conversion
* Implemented in [GRASS GIS](https://grass.osgeo.org/)

![GRASS GIS Logo](../images/grass-logo-s.jpg)

---

# Space Time Datasets

* A collection of maps representing spatial data at different instances in time
* Maps are assigned timestamps and registered in a database with temporal metadata
* Support for vector, raster, 3D vector, & 3D raster maps

---

# Temporal Processing

* Gap filling
* Aggregation
* Accumulation
* Algebra
* Queries
* Statistics
* Animation
* etc...

---

# Case Study

### Hilltop Arboretum Time Series

---

{{< slide background-image="../images/hilltop-arboretum.jpg" >}}
## Hilltop Arboretum

---

{{< slide background-image="../images/hilltop-wildflowers-3.jpg" >}}
## Cajun Prairie Wildflower Meadow

---

{{< slide background-image="../images/hilltop-2.jpg" >}}
## Monthly Drone Surveys

---

{{< slide background-image="../images/drone-data-analytics-1.png" >}}

---

{{< slide background-image="../images/grass-python-scripting.png" >}}
## Time Series Analysis

---

## Spatiotemporal Data & Functions
* Space time raster dataset
* Temporal aggregation
* Temporal algebra

---

{{< slide background-image="../images/statistics-with-python.png" >}}
## Monthly Changes in Biomass

---

# Point Cloud Visualization

[xyz.cct.lsu.edu](https://xyz.cct.lsu.edu/data/hilltop/arboretum.html)

---

{{< slide background-video="https://xyz.cct.lsu.edu/data/hilltop/hilltop-2020.mp4" data-background-video-loop="loop" >}}

---

{{< slide background-image="../images/transect-biomass-2020.jpg" background-size="contain" >}}
## Net Annual Biomass

---

# References

* Gebbert, S. & Pebesma, E. 2014. *TGRASS: A temporal GIS for field based environmental modeling*. Environmental Modelling & Software 53, 1-12
* Gebbert, S. & Pebesma, E. 2017. *The GRASS GIS temporal framework*. International Journal of Geographical Information Science 31, 1273-1292
* Gebbert, S., Leppelt, T., & Pebesma, E., 2019. *A topology based spatio-temporal map algebra for big data analysis*. Data 4, 86.

---

# Tutorials

* **GRASS GIS Manual,** [Temporal data processing in GRASS GIS](https://grass.osgeo.org/grass82/manuals/temporalintro.html)
* **NCSU Geo For All Lab,** [Spatio-temporal data handling and visualization in GRASS GIS](https://ncsu-geoforall-lab.github.io/grass-temporal-workshop/)
* **NCSU Geo For All Lab,** [Brief introduction to GRASS GIS Temporal Framework](http://fatra.cnr.ncsu.edu/temporal-grass-workshop/TGRASS_intro.pdf)
* **Martin Landa,** [Jena GRASS GIS Workshop](https://training.gismentors.eu/grass-gis-workshop-jena/units/21.html)
