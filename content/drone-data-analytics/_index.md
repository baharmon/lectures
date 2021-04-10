+++
title = "Drone Data Analytics"
outputs = ["Reveal"]
+++

# Multispectral Drone Data Analytics
Estimating the Carbon Stock of a Designed Meadow \
Through Time Series Analysis

## [Brendan Harmon](https://baharmon.github.io/)

<img height="50px" src="lsu-coad-logo.png">

---

{{< slide background-image="drone-data-analytics-1.png" >}}

---

{{< slide background-image="firefly-takeoff.jpg" >}}
## Cajun Prairie Wildflower Meadow Surveys
### LSU Hilltop Arboretum

---

# Research Questions
* What is the carbon pool of the meadow?
* How will the carbon pool change as the meadow matures?
* Can designed meadows be effective stores of carbon?
* How can drone data analytics inform management?

---

{{< slide background-image="hilltop-wildflowers-3.jpg" >}}
## Coastal Tallgrass Prairie Ecosystem

---

{{< slide background-image="firefly.jpg" >}}
## Drone with Multispectral Sensor

---

{{< slide background-image="ground-control-station.jpg" >}}
## Ground Control Station

---

{{< slide background-image="gcp.jpg" >}}
## Ground Control Points

---

{{< slide background-image="quadrat-1.jpg" >}}
## Biomass Survey

---

{{< slide background-image="soil-core.jpg" >}}
## Soil Cores

---

{{< slide background-image="metashape.png" >}}
## Photogrammetry in Metashape

---

{{< slide background-image="grass-python-scripting.png" >}}
## Time Series Analysis in GRASS GIS

---

{{< slide background-image="statistics-with-python.png" >}}
## Data Science with Python

---

# Multispectral Imagery Time Series

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

# Volume Time Series

## $$ V = x y (z - z_0) $$

* $V$ = volume $(m^3)$
* $x$ = east-west resolution $(m)$
* $y$ = north-south resolution $(m)$
* $z$ = elevation $(m)$
* $z_0$ = bare ground elevation $(m)$


---

{{< slide background-image="volume_2020_03_19.png" >}}
## 2020-03-19

---

{{< slide background-image="volume_2020_04_25.png" >}}
## 2020-04-25

---

{{< slide background-image="volume_2020_06_01.png" >}}
## 2020-06-01

---

{{< slide background-image="volume_2020_06_30.png" >}}
## 2020-06-30

---

{{< slide background-image="volume_2020_08_03.png" >}}
## 2020-08-03

---

{{< slide background-image="volume_2020_08_29.png" >}}
## 2020-08-29

---

{{< slide background-image="volume_2020_09_27.png" >}}
## 2020-09-27

---

{{< slide background-image="volume_2020_10_25.png" >}}
## 2020-10-25

---

{{< slide background-image="volume_2021_01_24.png" >}}
## 2021-01-24

---

# Annual Statistics

---

{{< slide background-image="maximum_volume_2020.png" >}}
## Maximum Volume 2020

---

## Biomass

### $$ B = \frac{V \rho_s + V \rho_r}{x y} $$

* $B$ = biomass density $(kg / m^{2})$
* $V$ = volume $(m^3)$
* $\rho_s$ = shoot bulk density $(kg / m^{3})$
* $\rho_r$ = root bulk density $(kg / m^{3})$
* $x$ = east-west resolution $(m)$
* $y$ = north-south resolution $(m)$

---

{{< slide background-image="biomass_2020.png" >}}
## Biomass 2020

---

## Carbon

### $$ C = B C_f  x y $$

* $C$ = carbon $(kg C)$
* $B$ = biomass density $(kg / m^{2})$
* $Cf$ = carbon fraction $(C$\%$)$
* $x$ = east-west resolution $(m)$
* $y$ = north-south resolution $(m)$

---

{{< slide background-image="carbon_2020.png" >}}
## Carbon 2020

---

## Volume 2020-2021
![Volume Plot 2020-2021](volume-plot-2020.png)

---

## Maximum Volume 2020
* Maximum volume: 4,033 $m^3$

---

## Biomass 2020  <!-- add equation -->
* Biomass density: 15 $kg/m^{2}$
* Total biomass: 69,619 $kg$

---

## Carbon 2020  <!-- add equation -->
* Aboveground carbon stock: 2,900 $kgC$
* Belowground carbon stock: 29,820 $kgC$ <!-- soil organic carbon -->
* Carbon stock: 32,721 $kgC$
* Carbon pool: 7,047 $gC/m^{2}$

---

{{< slide background-image="matrice.jpg" >}}

# Future Work
* 5 years of drone surveys
* Maps for seeding & management
* Analysis of rainfall & temperature
* New ground control points
* New drone
* New sensors
