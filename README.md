# Data Visualization Project

## Data

The data I propose to visualize for my project is ['Global Data: GDP, Life Expectancy & More'](https://www.kaggle.com/datasets/arslaan5/global-data-gdp-life-expectancy-and-more)



## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * Is the GDP per capita impacting the life expectancy? How are they behaving when related?
 * What are the regions with high CO2 emissions, Which countries in the particular region are contributing the most?
 * What is the distribution of GDP contribution by region and country?

## Sketches

Effect of GDP per capital on Life expectancy: This sketch is an idea to check how life expectancy is behaving with increasing GDP percapita


![GDP per capital vs Life expectancy](https://github.com/user-attachments/assets/39097ce0-14ef-4614-8451-6cd0d958afda)



CO2 Emission by region and country: This sketch is an idea of visualizing the CO2 emmisions using a sunburst chart


![CO2 emission by region and country](https://github.com/user-attachments/assets/191c3d6a-21fb-4a3d-9072-7bddccfb3a94)



GDP Contribution by region and country: This sketch is an idea of the contribution of different regions and countries to GDP. A dropdown can be added to check contributions to different variables such as Population, GDP growth, Unemployment, Life expectancy, CO2 emissions, etc. 


![GDP Contribution by region and country](https://github.com/user-attachments/assets/61f7e3d8-4340-410d-b635-06c4581b096c)





## Prototypes

I’ve created a proof of concept visualization for my first sketch: Relationship between GDP per capita and Life Expectancy 

[![image](https://github.com/user-attachments/assets/61bebcb7-f4d7-4db5-9ad9-05652d61a2ea)](https://vizhub.com/NitindotR/e8190a079a09434a80f368f120c1cce7?mode=embed)

A prototype of a Sunburst chart using javaScript and some methods from D3 package.I am working on adding practical data to the code and use more d3 methods replacing the usual javaScript elements.

[![image](https://github.com/user-attachments/assets/e440faba-893a-49a5-ad7a-b74e03632c47)](https://vizhub.com/NitindotR/sunburst)




## Progression

I have created an interactive sunburst chart of regions on the first level and countries on the second level. the distribution of area according to the co2 emissions by the countries.
    The sunburst chart shows the name of the region/name of the country and the co2 emissions in metric tons when hovered.
  - I Intially included the whole data but the visualization did not look impressive. It looked complex. So, I limited the chart to the top 3 regions with most co2 emissions.


[![image](https://github.com/user-attachments/assets/7f74720e-c050-436f-9ce1-79737f9c6346)](https://vizhub.com/NitindotR/sunburst-whole)


[![image](https://github.com/user-attachments/assets/fb6ccee1-0d5e-4dd3-acda-79bbc0f0494e)](https://vizhub.com/NitindotR/sunbursttop3)


Added interactivity to the scatter plot done before. Interaction added to the color legend with mouse actions.


[![image](https://github.com/user-attachments/assets/660afcbc-c10a-47d5-89f9-8437998b8c8d)](https://vizhub.com/NitindotR/global-scatter)


I made a map showing the top 10 countries with most CO2 emissions. I also added an interactive effect. Hovering the mouse pointer over the highlighted country in the world map, It     displays the value of the CO2 emissions in metric tons

  [![image](https://github.com/user-attachments/assets/5a4951df-25e1-48d4-aa9e-864700127b69)](https://vizhub.com/NitindotR/world-map)

  <img width="945" alt="Screenshot 2024-12-08 at 2 49 30 PM" src="https://github.com/user-attachments/assets/88fd7f72-0884-4da8-9947-6bbffd25398d">



I enhanced the sunburst chart, added a dropdown to select the region, the chart is updated according to the selected region. I also enhanced the interactivity adding a tooltip to display the details when hovered.

[![image](https://github.com/user-attachments/assets/41ea9595-cc78-46e2-810a-9f5dce656a33)](https://vizhub.com/NitindotR/34d6049582d44cb8b10e1557fb3e4023)

<img width="1512" alt="Screenshot 2024-12-07 at 11 03 19 PM" src="https://github.com/user-attachments/assets/140214c1-4f9d-4c3b-b087-01befffc5a44">
<img width="1512" alt="Screenshot 2024-12-07 at 11 03 39 PM" src="https://github.com/user-attachments/assets/5897a382-7618-499f-a553-cfd7a29fa8ae">
<img width="1512" alt="Screenshot 2024-12-07 at 11 04 12 PM" src="https://github.com/user-attachments/assets/5475993a-8f55-4882-8444-27dea928f6b1">







I created a treemap, added a dropdown to choose the metric on which the treemap has to be adjusted. It is initially CO2 emissions distribution among the regions and countries. The title is also changed based on the metric chosen from the dropdown. The region rectangles have a black border which makes the region division clear.

Interactivity is added to the treemap with a tooltip containing the details of the block displayed when hovered onto.


[![image](https://github.com/user-attachments/assets/3515aa0f-ca8b-4354-8d6c-48b8d9368060)](https://vizhub.com/NitindotR/treemap)

<img width="1512" alt="Screenshot 2024-12-07 at 10 53 16 PM" src="https://github.com/user-attachments/assets/aac2fc55-37d8-4287-86ed-612f8143207c">









