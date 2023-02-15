---
name: Network Analysis and Raster Interpolation in ArcGIS
tools: [ArcGIS Pro, Network Analysis, Raster Interpolation]
image: "/assets/images/p5/p5map1.jpg"
description: These maps highlight the impacts of bank branch closures in the Isle of Wight.
---

# Investigating the impacts of bank branch closures in the Isle of Wight utilising GIS analysis - Network Analysis and Raster Interpolation
<br>
<div style="text-align: justify;">High street bank branches have been closing at a steady pace these past few years, and this change can be attributed to the momentous transition to digital for all things finance. Most of the bank branch closures are concentrated in rural or more deprived areas, and this risks the financial exclusion of different communities and demographics. This project utilises GIS-based network analysis and raster interpolation to examine the change in accessibility to a bank branch by means of walking and biking; and investigates if areas with insufficient internet infrastructure lie outside of the catchment area of the banks. </div>
<br>
<div style="text-align: justify;">The Isle of Wight, located off the south coast of England, is the English county with the highest rate of bank branch closures between 2014 and 2019, with 52% of the total number of bank branches on the island closing. With a total population of 138,260 according to the 2011 UK census conducted by the Office for National Statistics, the closure of bank branches will unavoidably end up excluding specific demographics or communities who will find it challenging to access a physical bank or utilise digital banking. Boundary data that classifies the IOW into different Output Areas (OA) was obtained from the UK data service, and these boundaries are based on the 2011 UK census. The data containing the postcodes for the IOW and the road network data required for the network analysis was obtained from the Ordnance Survey dataset, accessed via EDINA Digimap. Legal and financial commercial services data, which includes the information necessary to identify bank branch closures, was obtained from the Ordnance Survey dataset via EDINA Digimap from December 2014 to June 2019. Finally, raster datasets containing the broadband internet data speed at each postcode in IOW were obtained from the Office of Communications (OFCOM), UK, to identify areas in IOW that have inadequate internet infrastructure in addition to a lack of accessibility to a bank branch. These datasets were manipulated to include the data just for the IOW and then stored together in a geodatabase within ArcGIS, ensuring they all used the British National Grid coordinate system.</div>
<br>
{% include elements/figure.html image="/assets/images/p5/p5table1.png" caption="Table 1: The number of people, postcodes, and occupied households within the bank catchment area in 2014 and 2019." %}
<br>
<div style="text-align: justify;">The network analysis confirms the decline of accessibility to high street bank branches by means of walking and biking. When comparing the numbers obtained (Table 1) from the analysis, it can be noticed that there is a significant decrease, almost one-third, in the number of people, postcodes, and occupied households that are within the bank service area. Less than 45% of the total population of IOW lived within walking distance of a bank branch in 2019, when compared to 67% in the year 2014. While 84% of the people lived within biking distance of a bank branch in 2014, the branch closures led to its decrease, and only 64% of the people lived within biking distance of a bank branch in 2019.</div>
<br>
{% capture carousel_images %}
/assets/images//p5/p5map3.jpg
/assets/images//p5/p5map5.jpg
/assets/images//p5/p5map4.jpg
/assets/images//p5/p5map6.jpg
{% endcapture %}
{% include elements/carousel.html %}
<br>
<div style="text-align: justify;">Internet banking could be a viable alternative that can alleviate some of the impacts caused by the closure of bank branches. However, the requirements for internet banking are quite steep, especially in rural areas where the infrastructure for the internet might not be developed enough. In the maps given below, it is apparent that most of the rural areas don’t have sufficient internet infrastructure to obtain internet speeds greater than 2 Mbps, which is inadequate for internet banking, and a significant portion of these areas lie outside of the catchment area of the banks. Furthermore, it is to be noted that even if IOW had better internet infrastructure, there would still be a sizeable portion of the population who would not be comfortable with internet banking and would prefer only the physical banking experience.</div>
<br>
<img style="border: 0.1px solid grey;" src="/assets/images/p5/p5map1.jpg" alt="Biking Distance Overlay 2Mbps">
<br>
<img style="border: 0.1px solid grey;" src="/assets/images/p5/p5map2.jpg" alt="Walking Distance Overlay 2Mbps">



