+++
title = "Computational Design for Landscape Architects"
outputs = ["Reveal"]
+++

# Computational Design
### for Landscape Architects

[Brendan Harmon](https://baharmon.github.io/)

<img height="50px" src="lsu-coad-logo.png">


{{< note >}}
Hello. 
I am Brendan Harmon,
an assistant professor of landscape architecture
at Louisiana State University.
Today I will be talking about
my recent research and forthcoming book
on computational design.
While I have expertise in the spatial sciences,
recently I have been focused on 
computational ecology and 
computational design 
- on computational methods 
for ecological research
and the creative use of computation 
in the design process.
{{< /note >}}

---

# Design Research

* Ecological Robotics
* Computational Ecology
* Historic Preservation
* Point Cloud Modeling

{{< note >}}
This talk will explore several applications
of computational design including
planting and remote sensing with robots,
lidar analytics and biomass estimation, 
the preservation of heritage landscapes,
and point cloud modeling. 
{{< /note >}}

---

{{< slide background-image="ecological-robotics-7.jpg" >}}

# Ecological Robotics

{{< note >}}
Since 2019, I have been exploring 
creative, ecological applications for robots
such as autonomous planting and sensing.
I have been developing methods
for robotic planting 
both in the lab and the field.
{{< /note >}}

---

{{< slide background-image="ecological-robotics-2.jpg" background-size="contain" >}}

{{< note >}}
In the lab I developed a process 
for 3D printing with seeds.
I use a robotic system to extrude seeds 
in a paste of clay, planting media, and water.
With robotic paste-based extrusion,
seeds can be precisely planted
in computationally generated patterns.
Initially I tested this process in the lab,
printing seed mixes
in computational patterns
in small trays.
{{< /note >}}

---

{{< slide background-image="ecological-robotics-3.jpg" background-size="contain" >}}

{{< note >}}
This prototype uses Grasshopper 
to generate planting designs
and program the robot and extruder.
With this process, 
planting patterns can be generated from
algorithms such as
procedural noise gradients,
cellular automata,
space filling curves, or
AI image generation.
{{< /note >}}

---

{{< slide background-image="ecological-robotics-5.jpg" >}}

{{< note >}}
With robotic planting,
ecological gradients - for example -
can be computationally designed
and autonomously planted.
Here is a gradient of procedural noise.
{{< /note >}}

---

{{< slide background-image="ecological-robotics-6.jpg" >}}

{{< note >}}
And here is a tray of seedlings
planted in a prodecural noise gradient. 
{{< /note >}}

---

{{< slide background-image="ecological-robotics-4.jpg" background-size="contain" >}}

{{< note >}}
To scale up, I will deploy this
planting system on a field robot.
I plan to experiment with other 
methods for autonomous planting
such as seed hoppers.
Eventually I plan to conduct 
a controlled field experiment.
After autonomously seeding test plots,
I will use lidar to monitor growth.
With autonomous seeding at field scale,
landscapes can be 
planted iteratively and adaptively
and designed for ecological performance
with new computational aesthetics. 

{{< /note >}}

---

{{< slide background-image="ecological-robotics-8.jpg" >}}

{{< note >}}
This is our new unmanned ground vehicle
with real-time kinematic GNSS,
a robotic arm, and a lidar module.
I will use this field robot to plant test plots
and a demonstration garden. 
Applications for autonomous planting
include seeding meadows and prairies,
reforestation, ecological restoration,
and precision agriculture.
Imagine reforestation schemes 
that are no longer monocultural grids,
but rather in diverse communities
planted in gradients based on 
microclimatic, topographic, 
hydrological, and soil conditions.
Imagine meadows or perennial plantings 
that are no longer randomly sown
or slowly, meticulously laid out in drfits,
but rather are rapidly, robotically sown in gradients
to catalyze the emergence of 
diverse, resilient ecosystems.
{{< /note >}}

---

{{< slide background-image="robotic-wall.png" >}}

# Construction Robotics

{{< note >}}
I also teach creative applications
of robotics for autonomous construction. 
For example, in my classes, 
students learn how to
parametrically model brick walls
and then robotically lay the bricks.
{{< /note >}}

---

{{< slide background-image="hilltop-1.jpg" >}}

# Drone Data Analytics

{{< note >}}
My recent research in computational ecology
explores the use of lidar
to estimate biomass and carbon. 
Since 2020 I have been using drones
with lidar and multispectral sensors
to study the evolution of the meadow
established at LSU's Hilltop Arboretum.
{{< /note >}}

---

{{< slide background-image="hilltop-2.jpg" >}}

{{< note >}}
Here is the fixed wing drone with a multispectral sensor
that I use to capture monthly imagery of the meadow
with red, green, blue, near infrared, and rededge channels.
{{< /note >}}

---

{{< slide background-image="hilltop-3.jpg" background-size="contain" >}}

{{< note >}}
With regular aerial surveys 
I can map fluxes of aboveground biomass and carbon
in the meadow. 
Here, for example, is 
a 3D scatterplot of
the net annual biomass of the meadow
in its first year. 
By accounting for carbon storage in meadows and prairies,
we can demonstrate their ecoystem services
and advocate for their creation or conservation.
{{< /note >}}

---

{{< slide background-image="hilltop-4.jpg" >}}

{{< note >}}
Along with this research program, 
I regularly teach drone piloting, photogrammetry, and lidar
to landscape architecture students
in my computational design course. 
{{< /note >}}

---

{{< slide background-image="duelling-oak.jpg" background-size="contain" >}}

# Atlas of Heritage Trees

{{< note >}}
For another project 
- the Atlas of Heritage Trees -
I am laser scanning ancient trees
of significant historical, 
cultural, and ecological importance.
Louisiana has many large, old, 
and culturally significant specimens
of southern live oak and bald cypress. 
These trees are charismatic megaflora – 
specimens that capture 
the imagination of the public 
and encourage broader support 
for biodiversity conservation.
{{< /note >}}

---

{{< slide background-image="monarch-of-the-swamp.jpg" background-size="contain" >}}

{{< note >}}

Large, old tree populations, however, 
are in decline around the world. 
Louisiana's ancient trees are at risk
due to coastal change,
lack of legal protection, 
and senescence.
To preserve a record of these 
irreplaceable cultural icons, 
I am compiling an Atlas of Heritage Trees.
As a digital humanities project,
this research aims to document and share
the legacy of these heritage trees.
As a work of computational ecology,
this research aims to estimate the 
biomass and carbon of large, old trees
which act as keystone ecological structures. 
{{< /note >}}

---

<img src="big-cypress-point-cloud.jpg" width="500">
<img src="big-cypress-voxels.jpg" width="400">
<img src="big-cypress-marching-cubes.jpg" width="400">
<img src="big-cypress-dendro.jpg" width="400">

{{< note >}}
As part of this project,
I have developed a method 
for building volumetric models
from laser scanned point clouds. 
My volumetric modeling process 
can be used to calculate 
the volume of large, old trees
with extensive cavities
for biomass and carbon estimation. 
It can also be used to 3D print models 
of these specimens
for outreach, education, and exhibition.

{{< /note >}}

---

{{< slide background-image="big-cypress-print-xl.jpg" >}}

{{< note >}}
Here, for example, 
is a 3D print of the Big Cypress,
a 1500 year old Bald Cypress 
on Cat Island in Louisiana.
It is the largest recorded bald cypress
and the reigning national champion.
{{< /note >}}

---

# Heritage Preservation

<img src="faro-focus.jpg" width="250">
<img src="matrice.jpg" width="600">

{{< note >}}
My research in heritage preservation 
uses remote sensing technologies 
such as lidar
to preserve a record
of disappearing heritage landscapes.
I use drones with lidar, 
terrestrial laser scanning,
and neural radiance fields
to record the spatial structure
and phenomenological character
of heritage landscapes.
Here are some of the tools I use -
a laser scanner on a tripod 
for scanning on the ground
and a drone with real-time kinematic GNSS
and a lidar module
for scanning from above.
By combining aerial and ground based scans,
we can reconstruct complex landscapes
in minute detail.
{{< /note >}}

---

{{< slide background-image="rosedown-landscape.jpg" >}}

# Rosedown

{{< note >}}
With funding from the National Park Service,
my colleague Nick Serrano and I
scanned Rosedown Plantation
in St. Francisville, Louisiana.
Rosedown is unique for its 
extant, largely intact plantation gardens;
these gardens are important
not only for being representative of 
plantation garden design in the American South,
but also as artifacts of enslaved labor.
{{< /note >}}

---

{{< slide background-image="rosedown-rockery.jpg" >}}

{{< note >}}
With terrestrial laser scanning,
we captured temporal aspects of the landscape
such as the flowers in bloom on the rockery
- pictured here -
and the spanish moss swaying
on the live oak allee. 
{{< /note >}}

---

{{< slide background-image="rosedown-tunnel.jpg" >}}

{{< note >}}
The scan of the tunnel through the rockery,
captured details such as the pebble wash
and the moss and lichen on the bricks.
This level of immersive detail records
some of sensory experience
and phenomenological character
of the site in ways that other media cannot.
{{< /note >}}

---

{{< slide background-image="rosedown-staircase.jpg" >}}

{{< note >}}
The scan of the service staircase
captures how the tall steps are worn underfoot,
recording an index of the labor of the enslaved.
The point clouds for this project can be viewed
on my server xyz.cct.lsu.edu.
And the data has been archived online on Zenodo
with a free culture license.
{{< /note >}}

---

{{< slide background-image="petit-versailles-1.webp" background-size="contain" >}}

# Le Petit Versailles

{{< note >}}
Drone lidar can be use for landscape archeology.
Since lidar can penetrate forest canopy, 
it can reveal hidden landforms, traces of past landscapes.
Le Petit Versailles 
was the 19th century pleasure garden of Valcour Aimee.
Long abandoned, the ruins of the garden 
are lost beneath dense overgrowth
and a canopy of mature southern live oaks.
{{< /note >}}

---

{{< slide background-image="petit-versailles-2.webp" background-size="contain" >}}

{{< note >}}
To study this historic landscape,
I collected drone lidar during leaf off season this January.
Then I used a cloth simulation filter algorithm
to classify and segment bare ground,
revealing the historic waterways, mound, rockery, and paths.
This is just the beginning of this project;
I plan to experiment with other ground classification techniques
such as the multiscale curvature classification
and progressive morphological filter algorithms.
I also plan to use terrain analysis techniques 
- such as landform classification with geomorphons,
skyview factor, and principal component analysis -
to identify features in the landscape. 
In the future I plan to use these techniques 
to reveal lost histories and landscapes of the enslaved
thoughout the southern United States.
{{< /note >}}

---

{{< slide background-image="alford-1.jpg" >}}

# African American Burial Grounds

{{< note >}}
With an interdisciplinary team of colleagues,
I have begun a long term project
to preserve a record of the burial grounds
of enslaved African Americans 
and their descendants.
In the American South, 
These sites have long faced 
precarious conditions; 
originally built peripheral 
to antebellum plantations, 
today many occupy remnant parcels 
of isolated land. 
Climate change, 
industrial expansion, 
precarious land-tenure records, 
and dwindling populations 
of descendant communities 
threaten these cultural landscapes. 
The aim of this project 
is to develop a methodology for documenting 
the history, material culture, 
ecological character, and soundscapes 
of these neglected heritage sites. 
Here is a point cloud of Alford Cemetery
captured by a drone with a lidar module.
With drone lidar,
we can record these landscapes 
and their surroundings from above
at centimeter resolution. 
{{< /note >}}

---

{{< slide background-image="alford-2.jpg" background-size="contain" >}}

{{< note >}}
With terrestrial laser scanning,
we can record gravesites in immersive detail.
We are also experimenting with 
new scanning techniques such as 
neural radiance fields. 
Our plan is to use 
a segmented point cloud model 
of the cemetery as a way to 
map, curate, and explore other data.
Selecting a gravsite
within the point cloud model of the cemetery,
for example,
would reveal a curated collection
of geneological records, 
architectural drawings and measurements,
and photographs.
We have grand plans for this project
and over the next decade 
hope to record sites throughout
the southern United State and the Caribbean.
{{< /note >}}

---

{{< slide background-image="point-cloud-path-1.jpg" background-size="contain" >}}

# Point Cloud Modeling

{{< note >}}
I am also interested in point clouds
as a new design medium for landscape architecture,
that is both hyper-detailed, yet also abstract.
With point cloud modeling, 
complex, detailed scenes can be composited
by classifying, segmenting, transforming, 
and merging point clouds. 
{{< /note >}}

---

{{< slide background-image="cloud-forest.jpg" background-size="contain" >}}

{{< note >}}
Features - such as these trees - 
can be classified and segmented
either manually or automatically
with algorithms and machine learning techniques.
When individual specimens have been isolated,
their biomass and carbon can be calculated.
{{< /note >}}

---

{{< slide background-image="gaussian-planting-1.jpg" background-size="contain" >}}

{{< note >}}
Segmented point clouds can then be transformed manually 
or algorithmically with, for example, Grasshopper
to create new designs.
Here is a simple example of 
laser scanned plants scattered
in a Gaussian distribution.
{{< /note >}}

---

# Future Research

* **Project:** field robotics

* **Paper:** computational aesthetics

* **Book:** computational ecology

* **GIS plugins:** earthworks and mass flows of water and sediment

* **Grasshopper plugins:** lidar & geospatial analytics

{{< note >}}
My future plans include 
creative applications of field robotics,
a paper on computational aesthetics,
a book on computational ecology,
and plugin development. 
I plan to explore new ecological applications 
for field robotics such as 
mobile lidar scanning,
rapid ecological censuses,
procedural mowing, 
spot burning of weeds,
and experiment with different planting and seeding systems. 
I plan to write a paper on computational aesthetics 
that delves into contemporary philosophies such as
object oriented ontology and vital materialism.
Now that I have finished writing my book 
on computational design for landscape architects 
which is due out this May,
I plan to write a new textbook on computational ecology.
Recently I developed a GIS plugin for simulating landscape evolution.
Now I plan to develop open source GIS plugins 
for grading and earthworks
and erosion modeling.
I also plan to develop open source Grasshopper plugins
for lidar analytics and terrain analysis. 
{{< /note >}}

---

{{< slide background-image="book.png" background-size="contain" >}}

{{< note >}}
My new book on Computational Design
will be published this May.
If you enjoyed this talk
and then try the book!
{{< /note >}}

---

{{< slide background-image="open-education.png" background-size="contain" >}}

{{< note >}}
I also publish open education materials online
including tutorials, videos, and datasets. 
{{< /note >}}

---

Learn more at
[**baharmon.github.io**](https://baharmon.github.io/)

