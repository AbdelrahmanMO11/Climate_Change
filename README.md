# Climate_Change
Analyzing climate change matter and the factors affecting it 

## Abstract

This project aims to visualize the change of the climate and the factors that affected it. The project utilized various datasets to demonstrate the changing in global temperature and how other factors contribute to it. The documentation of the sources of the datasets, the preprocessing, analysis, and conclusion thoughts about each dataset. 
In the end, we conclude how the temperature is rising fast, how greenhouse gasses affect it, and how renewable energy and other solutions could help avoid the danger

## Project Lifecycle 
 - Research & Data Acquisition
 - Analysis & Visualization
 - Conclusions & Decisions 
 - Repeatition along with new ideas


## Tech Stack 
Programming Languages : Python 3.9
Software Services: PowerBI
Libraries : numpy , pandas , seaborn , matplotlib , datetime , chart_studio , plotly , colorlover , scipy , warnings , sklearn

## Datasets Acquisition
Datasets format : Comma Separated Values (CSV) & Excell Sheets
<div class="alert alert-block alert-info" >
<a name='2'></a>
    
<h3>1. Global Temperature </h3>
    
Global Land and Ocean-and-Land Temperatures (GlobalTemperatures.csv):
Other files include:
Global Average Land Temperature by Country (GlobalLandTemperaturesByCountry.csv)
Global Land Temperatures By City (GlobalLandTemperaturesByCity.csv)

You can find this dataset [Here](https://berkeleyearth.org/data/).
    
   <h3>2. Ozone Hole Area </h3>
    
You can find this dataset [Here](https://www.kaggle.com/datasets/suhailsh7/antarctic-ozone-hole-area).
   <h3>3. Green House Gases Emissions </h3>
    
You can find this dataset [Here](https://www.kaggle.com/datasets/econdata/climate-change).
    <h3>4. Carbon Dioxid Emissions </h3>
    
You can find this dataset [Here](https://www.kaggle.com/datasets/kkhandekar/co2-emissions-1960-2018).
    <h3>5. Coal Consumption</h3>
    
You can find this dataset [Here](https://ourworldindata.org/grapher/coal-consumption-by-country-terawatt-hours-twh?tab=chart&time=1975..latest).
    <h3>6. Renewable Energy </h3>
    
You can find this dataset [Here](https://ourworldindata.org/grapher/renewable-energy-gen?time=1980..latest).
   </div>

## Preprocessing
in preprocessing phase we removed nulls and grouped the data according to what we need to analyze and visualize 

## Analysis and Visualization 
 we used known python libraries & PowerBI in order to Visualize & Analyze 
 
- Visualizations Using python: 
 
 ![image](https://user-images.githubusercontent.com/61950036/222564365-e991769b-20fd-4489-83ac-eee609fb989d.png)
 
 ![image](https://user-images.githubusercontent.com/61950036/222564609-5912846a-e473-44ac-8e16-d60a36b3ddd3.png)

 ![image](https://user-images.githubusercontent.com/61950036/222567747-97496801-c9c3-448b-afc0-040d4c6fb9f0.png)
 ![image](https://user-images.githubusercontent.com/61950036/222567901-c89a6884-0bb3-43c1-ac0b-a818671731a7.png)

 
 interactive visualization
 ![image](https://user-images.githubusercontent.com/61950036/222567272-4d9270b3-fd6d-4561-9ab5-59c6c8cc3cb2.png)

- Visualizations using PoweBI:
 we've made an interactive PowerBI file which gives the ability to analyze either a certian part of each dataset or the whole dataset 
 ![image](https://user-images.githubusercontent.com/61950036/222566732-5c032d6a-04d3-42f9-aa80-bcd6b8fd86e0.png)
 
 
 ## Modeling
 
 we used polynomial regression to predict the average temprature in the future if we sticked to the same sources of energy, ways of manufacture  ... etc. we use today
![image](https://user-images.githubusercontent.com/61950036/222568922-9ebec42b-6ed2-414a-a668-01d127686600.png)


