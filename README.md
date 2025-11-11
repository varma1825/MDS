🥗 Comparing Tesco Food Purchases with the UK Eatwell Guide

This project analyses grocery purchase patterns from Tesco at the London ward level and compares them against the UK Eatwell Guide recommendations. Using spatial and statistical analysis in R, the project visualizes healthy and unhealthy food consumption patterns across London to identify dietary inequalities and public health risks.

📊 Key Features

🗺️ Spatial mapping of food categories (fruit & veg, sugary drinks, sweets, ready meals).

🧮 Calculation of Euclidean distance between actual purchases and Eatwell Guide proportions.

📈 Visualization using tmap, tidyverse, and sf libraries.

🥧 Pie chart of average Tesco purchase proportions across Eatwell categories.

📂 Integration of shapefiles (London_Ward_CityMerged.shp) with ward-level grocery data (year_osward_grocery.csv).

🧠 Objectives

Assess alignment between consumer purchasing behaviour and national dietary guidelines.

Identify wards with greater deviation from recommended nutritional balance.

Provide insights for public health planning and nutrition interventions.

🛠️ Tools & Libraries

tidyverse, dplyr, readr, sf, tmap, here

R version ≥ 4.3

Spatial shapefiles for London wards (ONS)

📁 File Structure
├── MDS.Rmd                 # Main analysis script (R Markdown)
├── MDS.pdf                 # Rendered report with visual maps and charts
├── year_osward_grocery.csv # Tesco grocery dataset
├── London-wards-2018/      # Shapefiles for spatial mapping
└── README.md               # Project overview and usage

📸 Outputs

Choropleth maps showing:

Fruit & vegetable purchases 🍎

Sugary drink purchases 🥤

Ready-made meal purchases 🍱

Sweets purchases 🍬

Pie chart of average dietary composition by category.

Table of Euclidean distances from Eatwell ideal proportions.

📚 Keywords

R, spatial analysis, public health, nutrition, Eatwell Guide, Tesco, London, geospatial, data visualization
