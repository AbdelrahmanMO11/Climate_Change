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
Programming Languages : Python 3.9.

Software Services: PowerBI.

Libraries : numpy , pandas , seaborn , matplotlib , datetime , chart_studio , plotly , colorlover , scipy , warnings and sklearn.

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
 
 ![image](https://user-images.githubusercontent.com/61950036/222575403-9aac2764-4c76-408e-8d5d-b0c74dbc29c4.png)

 
 ![image](https://user-images.githubusercontent.com/61950036/222567901-c89a6884-0bb3-43c1-ac0b-a818671731a7.png)
 
 ![image](https://user-images.githubusercontent.com/61950036/222575483-7657282c-edc7-4a5b-b09e-6d8f2b59cdc1.png)


 
 interactive visualization
 ![image](https://user-images.githubusercontent.com/61950036/222573840-04fcbb22-0b2e-49d0-bb26-393ea4cf56ca.png)
 ![image](https://user-images.githubusercontent.com/61950036/222567747-97496801-c9c3-448b-afc0-040d4c6fb9f0.png)
 
- Visualizations using PoweBI:
 we've made an interactive PowerBI file which gives the ability to analyze either a certian part of each dataset or the whole dataset 
 ![image](https://user-images.githubusercontent.com/61950036/222566732-5c032d6a-04d3-42f9-aa80-bcd6b8fd86e0.png)
 
 
 ## Modeling
 
 we used polynomial regression to predict the average temprature in the future (2100) if we sticked to the same sources of energy, ways of manufacture  ... etc. we use today


![image](https://user-images.githubusercontent.com/61950036/222568922-9ebec42b-6ed2-414a-a668-01d127686600.png)


