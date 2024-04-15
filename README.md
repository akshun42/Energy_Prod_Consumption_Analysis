# Energy_Prod_Consumption_Analysis

Balancing the Equation: Exploring Energy Production and Consumption Dynamics

The project delved into the complex balance of global energy production and consumption over the last three decades. We took a deep dive into data spanning from 1990 to recent times to uncover how different regions and countries manage their energy needs, which ones produce more than they use, and those that struggle to meet their energy demands.

We analyzed trends and patterns, focusing on key questions like how the U.S. and China differ in their energy use, why Europe's energy consumption is declining, and which regions have ramped up their usage most significantly. Using comprehensive datasets, we were able to visualize the shifts in energy dynamics and provide insights into the role of renewable energy and how it's shaping the future of global energy landscapes.

The heart of our project was in organizing data into insightful visualizations. Starting with a world map, we color-coded countries to show energy production vs. consumption and created interactive elements for users to engage with the data. We highlighted key findings, such as Asia's dramatic increase in energy use and Europe's shift towards energy efficiency and renewables, painting a picture of a world in energy transition.

Our project offers a snapshot of where we've been and where we're heading in terms of energy use, shedding light on the critical balance between keeping the lights on and doing so sustainably.

Key Technologies Used:

Microsoft Excel for data organization
Tableau for data visualization

This project is not just about numbers; it's about understanding our world's energy narrative and contributing to the conversation on sustainable practices for the future






Introduction
This is an analytical project that delves into the intricate balance between energy production and
consumption across the globe. Through examining data from 1990 to 2022, this initiative seeks to shed
light on the trends and disparities in energy dynamics, highlighting the contrast between countries
with surplus production and those facing consumption challenges. By assessing regional patterns and
individual country profiles, the project aims to understand the evolution of the energy landscape, the
role of renewable sources, and the impact of economic and policy shifts on energy sufficiency and
sustainability.


Problem Statement
The aim of this project is to address the following issues :
1. How does the energy consumption in the United States compare to that in China?
2. What is the difference in energy production versus consumption in Russia?
3. What trends can be observed in the region-wise energy consumption over the years?
4. Which region has shown the most significant increase in energy consumption over the last decade?
5. What countries show rising behavior in consumption trends?
6. Why is Europe showing a decline in consumption 2019 to 2022?
7. Why does Japan show a negative from 2007 to 2021 in country wise consumption ?


Data Description
The project's dataset encompasses a historical series from 1990 to 2022, detailing global energy production
and consumption metrics including country-specific data illustrating the differences between energy output
and usage, renewable energy adoption rates, and CO2 emissions. Regional trends reveal Asia's rising energy
demands, contrasted by Europe's declining consumption, reflecting broader economic, demographic, and
policy influences on the energy sector.It harnesses datasets sourced from Enerdata's Yearbook, offering
insights into global energy production and consumption. These datasets provide comprehensive statistics,
detailing various aspects of energy consumption across various regions.


Links:
World Energy Primary Production
Total Energy Annual Data - U.S. Energy Information Administration (EIA)
Renewables in Electricity Production | Statistics Map by Region | Enerdata
United States Renewable Energy - dataset by doe | data.world
Wind & Solar Share in Electricity Production Data | Enerdata


Methodology:
1. Data Compilation and Structuring: Extracted data from the source was organized into multiple tables
within an Excel format, segmenting information on energy production and consumption. Tables were
interlinked and pivoted based on years and countries to see over the year trends in various regions.
2. Derived Metrics and Relationships: Calculated fields were generated to quantify the differences between
energy consumption and production. These metrics were used to create relationships across regions and
countries, focusing particularly on major nations like India, China, and the USA.
3. Visualization of Insights:The methodology aimed to visually present trends and anomalies in energy
dynamics. Visualization techniques were employed to highlight discrepancies and patterns, emphasizing
key insights within regions and countries of interest.
Design Process:
Our design begins with a world map illustrating energy production and consumption disparities from 1990 to
2022. Red countries lack energy, green overproduce, and gray balance both. Bar graphs depict production,
consumption, and CO2 emissions. Our interactive interface lets users filter data for insights.
The second dashboard categorizes nations by regions, aiding region-specific consumption trend analysis. We
highlight % reductions in electricity consumption between 2021-2022 and average reductions from
2000-2022. Red highlights reductions, green indicates increases, offering a clear view of regional consumption
Key Insights
1. How does the energy consumption in the United States compare to that in China?
For the year 2022 China's energy consumption appears to be the highest among all listed countries, with a
value visually estimated to be just over 3801 Mtoe(Million tons of oil equivalent) and for the US, it's 2,382
Mtoe indicating that China's consumption is higher than that of the US.
<img width="736" alt="Consumption_2022" src="https://github.com/akshun42/Energy_Prod_Consumption_Analysis/assets/162837369/c2d0caf2-5418-44d0-8400-afac1756b2eb">

2. What is the difference in energy production versus consumption in Russia?
The bar for energy production is green and indicates that Russia produced 1,455.3 Mtoe of energy and the
bar for energy consumption is orange and indicates that Russia consumed 822.3 Mtoe of energy. Hence, the
difference between energy production versus consumption comes out as : (1455.3 - 822.3)Mtoe = 633 Mtoe.

<img width="538" alt="Production_v:s_Consumption_2022" src="https://github.com/akshun42/Energy_Prod_Consumption_Analysis/assets/162837369/5530c4a4-8a8d-415a-b556-1a9bd532d13e">

3. What trends can be observed in the region-wise energy consumption over the years
The area chart shows a continuous increase in energy consumption for Asia over the years, while other
regions also show growth but not as pronounced.
Europe has shown gradual decrease in the consumption after 2021 due to various factors like COVID and the
Russia-Ukraine war.

<img width="799" alt="Region_wise_Consumption" src="https://github.com/akshun42/Energy_Prod_Consumption_Analysis/assets/162837369/83261007-7e14-4272-b5c9-e421c14cf113">

4. 4. Which region has shown the most significant increase in energy consumption over the last decade?
Over the last decade, Asia has seen the steepest rise in energy consumption among all regions, as depicted by
the area and line graphs indicating a substantial and consistent growth rate.(Refer Q3 Chart)

5. What countries show rising behavior in consumption trends?
China: The data for China shows a pronounced increase in energy consumption across the years, with figures
significantly rising from 881 Mtoe (Million tons of oil equivalent) in the first column to 2,506 Mtoe in the last
column.
India: There is a consistent upward trend for India as well, starting from 255 Mtoe and increasing to 527
Mtoe.

<img width="526" alt="Countrywise_Consumption" src="https://github.com/akshun42/Energy_Prod_Consumption_Analysis/assets/162837369/6bb07edf-74a0-47bf-b63f-f7e1c93e488d">

6. Why is Europe showing a decline in consumption 2019 to 2022?
The "Region wise consumption" area chart shows that in Europe, there is a decline in energy consumption in
recent years, particularly from 2019 to 2022, the reasons being :
Increased Energy Efficiency: European countries have been focusing on energy efficiency, which reduces
overall energy consumption.
Transition to Renewables: Europe has been actively transitioning to renewable energy sources, which might
affect the consumption statistics, especially if energy efficiency and conservation measures are also in place.
Technological Advancements: Adoption of more energy-efficient technologies in homes, industry, and
transportation. (Refer Q3 Chart)
7. Why does japan show a negative from 2007 to 2021 in country wise consumption
Japan's declining energy consumption is due to economic shifts towards less energy-intensive industries, a
decreasing and aging population, and a post-Fukushima move from nuclear to increased renewables and
energy efficiency measures. (Refer Q5 Chart)








