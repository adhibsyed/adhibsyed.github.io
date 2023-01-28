---
name: Generating Glacier Velocity Maps of Rink Isbrae Utilising Sentinel-1 A/B SAR Data
tools: [SNAP, Google Earth, SAR]
image: "/assets/images/p1/p1map2.jpg"
description: Offset tracking within the SNAP software was utilised to generate velocity maps of the Rink Isbrae glacier.

---

# Generating Glacier Velocity Maps of Rink Isbrae Utilising Sentinel-1 A/B SAR Data
<br>
<div style="text-align: justify">This project focuses on using radar data to track changes in the movement of Rink Isbrae, one of the quickest glaciers on the planet, located in the Uummannaq district of Greenland. The glacier has a large drainage basin of 30,000 square kilometers and it drains a significant portion of the Greenland ice sheet, 3.5%, through a 4.5 km wide area at the terminus. The goal of this project was to create detailed maps of the glacier's velocity during the month of July from 2016 to 2022. This tool can be used to track changes in glacier movement caused by climate change and to identify patterns when analyzed over a long period of time. </div>
<br>
{% include elements/figure.html image="/assets/images/p1/p1map1.png" caption="Velocity map (July 2018) of Rink Isbrae plotted over the SAR image mosaic that has been terrain corrected." %}
<br>
<div style="text-align: justify">The SAR data was obtained from the Sentinel 1-A (2014) and 1-B (2016) satellite constellations developed by the European Space Agency (ESA). This data was processed in Sentinel Application Platform (SNAP) v9.0 in three stages. The pre-processing stage involved the following steps: Read > Apply Orbit File > Thermal Noise Removal > Calibration > Write. The processing stage involved the following steps: DEM-Assisted-Coregistration > Subset > Offset-Tracking > Write. Finally, the post-processing stage involved these steps: Stacking the Products (BandMaths) > Range-Doppler Terrain Correction > Visualisation. </div>
<br>
{% include elements/figure.html image="/assets/images/p1/p1map3.jpg" caption="Velocity map of Rink Isbrae, July 2016, plotted over Google Earth Image." %}
<br>
<div style="text-align: justify">From the velocity maps obtained from the SAR data utilising feature tracking based on patch intensity cross-correlation optimisation, it can be inferred that the Rink Isbrae glacier is a reasonably fast-moving glacier with velocities ranging from 6.42 m/day to 7.42 m day. The observed velocities in the month of July for the years 2016-2022 are recorded in the line chart given below. No distinct velocity variation patterns could be noticed within this project, considering the analysis was done in only seven intervals by using a series of fourteen Sentinel 1-A/B SAR images. If more extensive analyses were undertaken over a significant stretch of time, this technique would be beneficial in monitoring patterns and evaluating the effects of climate change, however it is beyond the scope of this project. </div>
<br>
{% include elements/figure.html image="/assets/images/p1/p1map10.png" caption="Line chart highlighting the velocity variation of Rink Isbrae glacier in different years" %}
