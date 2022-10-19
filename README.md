# Disclaimer
In order for us not to discard any contribution from the team members, i have not taken any file out from the contributors and hence the repository might look messy. 
Therefore, i am including a list of files that are relevant and important for the final project -

### (1) Dataset - All the dataset used in the project are included
https://github.com/fbrowther/Project-1/tree/main/Resources
### (2) Resources - All the details of the dataset is included
https://github.com/fbrowther/Project-1/tree/main/Resources
### (3) Skeleton plan of the project
https://github.com/fbrowther/Project-1/blob/main/Skeleton%20Plan%20of%20Approach%20to%20Answering%20Questions.md

### (4) Analysis file - 
(https://github.com/fbrowther/Project-1/blob/main/Project-1-FBRowther.ipynb) 
### (5) Analysis images - All the png files of the analysis are included - 
https://github.com/fbrowther/Project-1/tree/main/Analysis%20Images
### (4) Final presentation - 
(https://github.com/fbrowther/Project-1/blob/main/Project%201%20FBRowther1.pptx)
### (4) README.md file - 
https://github.com/fbrowther/Project-1/blob/main/README.md


# Project 1: Global Warming – UK Greenhouse Gas Emissions
Module 7 & 8 - Project 1 Group Challenge

---------
## Background 

![greenhousegas](Images/greenhouse-gas-emissions-606x303.jpeg)

Global warming is unfortunately becoming more evident in recent years and is having a devastating impact on populations globally. We wanted to find out how much greenhouse gas emissions has been contributing to global warming in the UK. 

In order to analyze this, we looked specifically at the dataset for UK from 'https://climate-change.data.gov.uk/' data repository for the period of 1990-2020. 

First and foremost, two datasets were obtained from the database, one archived on the basis of source of the greenhouse gas emmision and the other archived on the basis of end-users responsible for emission.

---------
## Plan

## Who, what, where, when?

![ghgskeleton](Images/maxresdefault.jpeg)

## 1. Which sector(s) are responsible for most of our emissions in the UK? 

## 2. Which end user is responsible for most of our emissions in the UK?
 
## 3. What are the top 4 contributing sectors?

## 4. What are the activities (top 10) of the major contributing sectors?

## 5. What is the trend in the major contributing sectors (for the timeframe of the dataset)?

## 6. When all the sectors are combined which activities contribute to most emission?

## 7. What are the fuels whcih contribute to the total emission?

## 8. Major components of the emission?

## 9. Top emitters of Carbon dioxide?

## 10. Top emitters of Methane?

## 11. Top emitters of Nitrous oxide?

## 12. Top emitters of Hydroflurocarbons?

## Conclude the trends of overall emissions in the UK
Observations and insights

---------
[Project 1 Rubric](https://docs.google.com/document/d/1fPa8EXPb5caZyzG2EdhzyWyhta9jC62siFMctNCvKog/edit)
---------
The two datasets were obtained from 'https://climate-change.data.gov.uk/' cleaned and unnessary columns were taken out before commencing the analysis.

---------
## Major Sectors
First and formost we determined the major sectors that contributed towards the green gas emission for the UK (from 1990-2020). We compared the analysis between sources and end-users dataset. 

![alt text](https://github.com/fbrowther/Project-1/blob/main/Analysis%20Images/Sectors%20responsible%20for%20GG%20emissions.png)

![alt text](https://github.com/fbrowther/Project-1/blob/main/Analysis%20Images/Sectors%20responsible%20-endusers.png)

Unlike the popuplar opinion that transport is a major player, the results show that transport sector consitutes to only 10% of the total while 87% of the emission is contributed by the other 3 sectors which include Agriculture, Business, Energy and Land-related activities.

In order to dive deeper into the four major sectors, we grouped together the dataset based on the Agriculture, Business, Transport, Energy & Land related activities using loc function and looked at the activities that were performed within these sectors.

---------
# 1st Contributor
## Top 10 Agricultural activities that contributed to greenhouse gase emissions.
### By Source
![alt text](https://github.com/fbrowther/Project-1/blob/main/Analysis%20Images/Top10AgriActivities-by%20source.png)
### By End-users
![alt text](https://github.com/fbrowther/Project-1/blob/main/Analysis%20Images/Top10AgriActivities-by%20Endusers.png)

The top 10 activities of the Agricultural sector (by source and end-users) included - 
Spreading, Grazing, Storage, Housing, Yarding, Urea application, Ammonium sulphate & diammonium phosphate application, Ammonium nitrate application, Calcium ammonium nitrate application and Other nitrogen including compounds application.                                                

---------
# 2nd Contributor
## Top 10 Business activities that contributed to greenhouse gase emission.
### By Source
![alt text](https://github.com/fbrowther/Project-1/blob/main/Analysis%20Images/Top10BusiActivities-by%20source.png)
### By End-users
![alt text](https://github.com/fbrowther/Project-1/blob/main/Analysis%20Images/Top10BusinessActivities-by%20Endusers.png)

The major activities of the business sector (by source and end-users) involved- 
(1) the use of natural gas, coal, Gas oil, Fuel oil in industrial combustion & 
(2) the use of Halocarbon bank hfc 134a, Halocarbon used for manufacturing hfc 134a, Halocarbon bank hfc 125, Halocarbon used for manufacturing hfc 125, Halocarbon in products at disposal hfc 134a, Halocarbon bank hfc 32 in refrigeration and air conditioning.

---------
# 3rd Contributor
## Top 10 Transport sector activities that contributed to greenhouse gase emission.
### By Source
![alt text](https://github.com/fbrowther/Project-1/blob/main/Analysis%20Images/Top10TransportActivities-by%20source.png)
### By End-users
![alt text](https://github.com/fbrowther/Project-1/blob/main/Analysis%20Images/Top10TransportActivities-by%20Endusers.png)

The major activities of the transport sector (by source and end-users) included the use of
Derv (diesel oil for road vehicles, Petrol, Gas oil, Aviation turbine fuel, Fuel oil, Aviation spirit,           Natural gas, Lubricants, Lpg, Burning oil, Coal, Biodiesel, Urea consumption, and Bio mtbe. These sources were used in HGVs, passenger cars, light duty vehicles, buses, military aircraft, civil aviation, fishing vessels, national navigation, railway combustion, mopeds and motorcycles.

---------
# 4th Contributor
## Top 10 Energy sector activities that contributed to greenhouse gase emission (by source).
![alt text](https://github.com/fbrowther/Project-1/blob/main/Analysis%20Images/Top10EnergyActivities-by%20source.png)

The major activties of the energy sector include the use of natural gas, non-fuel combustion, Gas oil, Lpg, Coal, gas flare, Opg, Msw, Coke oven gas, and Fuel oil for power stations, refineries, and manufacturing of solid fuels.                                  

## Top Land use -related activities that contributed to greenhouse gase emission (by end-users.
![alt text](https://github.com/fbrowther/Project-1/blob/main/Analysis%20Images/Top10LandActivities-by%20Endusers.png)

The major land use -related activties include Non-fuel-combustion and Biomass. 

Non-fuel consumption - Drainage of organic soils releases CO2 and NO2 into the atmosphere), Farming (Cropland), Wetland - Plants growing in wetlands emit methane to the atmosphere. 

Biomass - Grassland, crop land, forest land and settlements burning

---------
## Trends in 4 major sectors from 1990-2020 by source
![alt text](https://github.com/fbrowther/Project-1/blob/main/Analysis%20Images/Agriculture%20-%20Timeframe%20.png)

![alt text](https://github.com/fbrowther/Project-1/blob/main/Analysis%20Images/Business%20-%20Timeframe%20.png)

![alt text](https://github.com/fbrowther/Project-1/blob/main/Analysis%20Images/Transport%20-%20Timeframe%20.png)

![alt text](https://github.com/fbrowther/Project-1/blob/main/Analysis%20Images/Energy-%20Timeframe%20.png)

In order to identify whether there has been any changes to the activities of the top contributors, the entire dataset was grouped based on sectors and the trend in their activities for the entire duration of the dataset was anlaysed. 

A continual upwards trend contributing consistently to the greenhouse gases emission by agriculture, business and transport sector was noted. However, in case of the energy sector there has been slow but definite downward movement. UK government's has put forward plans to phase out of UK's coal plants within the next few years and this initiative should see further improvement in this sector.

---------
## Trends in 4 major sectors from 1990-2020 by End-users
![alt text](https://github.com/fbrowther/Project-1/blob/main/Analysis%20Images/Agri-timeframe-endusers.png)

![alt text](https://github.com/fbrowther/Project-1/blob/main/Analysis%20Images/Business-timeframe-endusers.png)

![alt text](https://github.com/fbrowther/Project-1/blob/main/Analysis%20Images/Transport-timeframe-endusers.png)

![alt text](https://github.com/fbrowther/Project-1/blob/main/Analysis%20Images/Land-timeframe-endusers.png)

A continual upwards trend contributing consistently to the greenhouse gases emission for agriculture, business, transport and land use -related sector was noted. 

---------
## When all the sectors are combined which activities contribute to most emission?
![alt text](https://github.com/fbrowther/Project-1/blob/main/Analysis%20Images/Top10%20activities%20by%20users%20irrespective%20of%20sector.png)

Refrigeration & air conditioning, soil emission (direct and indirect), Industrial combustion, agriculture soil management, animal waste management and national navigation (shipping) contributes to most emmsion within the UK.

## What are the fuels whcih contribute to the total emission?
![alt text](https://github.com/fbrowther/Project-1/blob/main/Analysis%20Images/Fueltype-souces.png)

Burning of the 'actual' fuel contributed to a third of the emission in the UK while the remaining 2/3 was contributed by - industrial combustion, agricultural soil management, refrigeration and air conditioning and industries (glass, chemical) activities

---------
Other Emissions included in the pie chart includes –
(a) 
Cattle, Horses, Pig and Poultry wastes
Soil emission (both direct and indirect),
Drainage of organic soils - settlements
Waste incineration,

(b)
Refrigeration and air conditioning,

(c)
Glass Production,
Gas flare,
Chemical Industries, 
Power stations, 
Industrial combustion, 
Manufacture of solid fuels and other energy industries

---------
## Major components of the emission -
![alt text(https://github.com/fbrowther/Project1/blob/main/Analysis%20Images/Greenhouse%20gases%20by%20Sources.png)

Greenhouse gases in our dataset agreed with and showed a similar composition of gases to the total emission noted before by other environment protection agencies such as USA. This included CO2 being on the top, followed by Methane, Nitrous oxide and Hydrofluorocarbons. 
1. Carbon dioxide (CO2)–
CO2 causes 80% of global warming and its release is mainly contributed by fossil fuels burning like coal, oil and gas or deforestation.
2. Methane (CH4)– 
Methane possess >80 times the warming power of carbon dioxide for the first 20 years after being released
3. Nitrous oxide (N2O) –
Increased N- based fertilizer use (>50 years) has been responsible for dramatic increase in its emission. 
4. Hydrofluorocarbons (HFC) –
HFCs are highly effective at trapping solar radiation (infrared radiation) and redirecting it toward Earth's surface. 
Major source of HFCs are refrigeration and air conditioning

---------
## 9. Top emitters of Carbon dioxide?
![alt text](https://github.com/fbrowther/Project-1/blob/main/Analysis%20Images/Top%20emitters%20of%20Co2.png)

As expected, CO2 emission was mainly due to industrial combustion, solid fuel industries and power stations.

---------
## 10. Top emitters of Methane?
![alt text](https://github.com/fbrowther/Project-1/blob/main/Analysis%20Images/Top%20emitters%20of%20Methane.png)

In case of Methane, the major emitters are industrial combustion, animal wastes management and power stations.

---------
## 11. Top emitters of Nitrous oxide?
![alt text](https://github.com/fbrowther/Project-1/blob/main/Analysis%20Images/Top%20emitters%20of%20NO2.png)

The top emitters for Nitrous oxide include agricultural soil & waste management, and combustion

---------
## 12. Top emitters of Hydroflurocarbons?
![alt text](https://github.com/fbrowther/Project-1/blob/main/Analysis%20Images/Top%20emitters%20of%20HFC.png)

The sole and the most emitter of hydroflurocarbons include refrigeration and air conditioning

---------
## Conclusion on the overall the trends of emissions in the UK

(1) With the help of this project we were able to identify the top most sectors that were contributing to around 90% of the emission. 
(2) Within these sector we were able to look deeper into what major activities that was responsible for the emission. 
(3) We also looked at the trend of the activities of the sectors to see if there has been any changes pertaining to more recent extreme weather conditions. 
(4) Since we noticed an upward trend in the activities of the top responsible sectors, we urge the policy makers to take more stringent measure to both curb and transform the practices of these sectors 
(5) finally we suggest we look into modalities that can be used to capture already released greenhouse gases, from the atmosphere and limit its damage.

---------
## References
* https://climate-change.data.gov.uk/ 
* 2019 UK greenhouse gas emissions: final figures – dataset of emissions by source
https://beta.gss-data.org.uk/cube/explore?uri=http%3A%2F%2Fgss-data.org.uk%2Fdata%2Fgss_data%2Fclimate-change%2Fbeis-2019-uk-greenhouse-gas-emissions-final-figures-dataset-of-emissions-by-source-catalog-entry
* 2019 UK greenhouse gas emissions: final figures – dataset of emissions by end user
https://beta.gss-data.org.uk/cube/explore?uri=http%3A%2F%2Fgss-data.org.uk%2Fdata%2Fgss_data%2Fclimate-change%2Fbeis-2019-uk-greenhouse-gas-emissions-final-figures-dataset-of-emissions-by-end-user-catalog-entry 
* Image source: Future Learn
https://www.futurelearn.com/info/blog/greenhouse-gases-emissions-environment

---------
Team - Group 4 (4)
* Grace Cheuk (gw-sc)
* Navindeep Bains (navinbains)
* Salma Abdirahman (Salma-abdirahman)
* Farjana Rowther (fbrowther)
