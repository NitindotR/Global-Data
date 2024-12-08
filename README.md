# Data Visualization Project

## Data

The data I propose to visualize for my project is 'Global Data: GDP, Life Expectancy & More'
link to the dataset: https://www.kaggle.com/datasets/arslaan5/global-data-gdp-life-expectancy-and-more



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




## Milestones

  - I have created an interactive sunburst chart of regions on the first level and countries on the second level. the distribution of area according to the co2 emissions by the countries.
    The sunburst chart shows the name of the region/name of the country and the co2 emissions in millions of metric tonnes when hovered.
  - I Intially included the whole data but the visualization did not look impressive. It looked complex. So, I limited the chart to the top 3 regions with most co2 emissions.


[![image](https://github.com/user-attachments/assets/7f74720e-c050-436f-9ce1-79737f9c6346)](https://vizhub.com/NitindotR/sunburst-whole)


[![image](https://github.com/user-attachments/assets/fb6ccee1-0d5e-4dd3-acda-79bbc0f0494e)](https://vizhub.com/NitindotR/sunbursttop3)


- Added interactivity to the scatter plot done before. Interaction added to the color legend with mouse actions.


[![image](https://github.com/user-attachments/assets/660afcbc-c10a-47d5-89f9-8437998b8c8d)](https://vizhub.com/NitindotR/global-scatter)





