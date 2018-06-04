# Programmeerproject

## What impact has eating meat to our planet?
#### A project by Felicia van Gastel

A project that visualizes the impact of the meat and dairy production on the climate and environment.

### Problem statement
While focussing in the recent years on fossil fuels as a major cause of climate change, we forgotten that our agriculture also has a (very) big influence on our climate. Besides from using the bike more often instead of the car, is there something else we as individuals can do to minimize our impact on the climate? And what changes in our lives will have more impact than others?

The target audience for this problem are people who are willing to minimize their impact on
the climate and environment.

### Solution
This project will visualize the impact of meat and diary production on our climate.

#### Visual sketch
![Sketch.png](https://github.com/11096187/programmeerproject/blob/master/doc/Sketch.png)

#### Main features
- A world map with color gradients showing the amount of CO2 emission per country per capita.
- A multiline chart showing information about for example CO2 and production of meat over the years.
- A zoomable sunburst showing from on what contents the CO2 emission is based.
- Without clicking on a country, the multiline chart and sunburst will show information about the world as a whole. Clicking on a specific country, will show the information about this specific country.

### Prerequisites
#### Data sources
- https://data.worldbank.org/indicator/EN.ATM.CO2E.PC?end=2014&start=1960&view=chart
-
-

#### External components
- d3
- d3-tip
- topojson

#### Review of similar or related visualizations
- World map: http://bl.ocks.org/micahstubbs/8e15870eb432a21f0bc4d3d527b2d14f
- Multiline chart: http://bl.ocks.org/asielen/44ffca2877d0132572cb
- Zoomable sunburst: https://bl.ocks.org/mbostock/4348373
- Infographic about CO2 emissions: http://infographics.pbl.nl/website/globalco2-2016/

#### Hardest parts of implementing
- Missing data from certain countries
