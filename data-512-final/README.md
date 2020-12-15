# Human Centered Data Science Final Project

**DATA 512 A Fall 2020** 

Juan Solorio

## Proposal & Motivation

Police violence and excess force or police brutality have always been a major area of concern for citizens especially among minority and underrepresented communities. In more recent times, over the last few months we’ve experience the social unrest and rightful outcry through the use of protests and marches from these communities to call out said brutality. 
For this project I plan to explore the demographics of police officers involved in shootings and use of force from the city of Seattle to gain a better understanding as to how might this have an effect on the type of response taken by said officers.


## Data

## Data

For the project I will be using the data provided by the [City of Seattle Open Data Program]( https://data.seattle.gov/browse?category=Public+Safety&provenance=official&page=2). Primarily I will be using three datasets:
* [SPD Officer Involved Shooting]( https://data.seattle.gov/Public-Safety/SPD-Officer-Involved-Shooting-OIS-Data/mg5r-efcm) - Records of Officer Involved Shootings (OIS) from 2005 to the present, including a brief narrative synopsis. Data set does not contain records from active investigations. Data is visualized in a dashboard on the SPD public site


* [Police Use of Force]( https://data.seattle.gov/Public-Safety/Use-Of-Force/ppi5-g2bj) - Records representing Use of Force (UOF) by sworn law enforcement officers of the Seattle Police Department.


* [Seattle PD Officers respoding to Crisis Calls]( https://data.seattle.gov/Public-Safety/Crisis-Data/i2q9-thny). - Data representing crisis contacts made by officers of the Seattle Police Department. Data is denormalized to represent the one to many relationship between the record and the reported disposition of the contact.


These datasets contain demographic information on Police Officers involved in the offence as well as that of the civilian victim. The data also contains geographical and temporal information which could give better insights as to how these events are affected by location or time.

There will also be need to use some government census data to make some statistical comparisons for the Seattle area, but more specifically the King County region, which Seattle belongs to. We will use the population statistics from [Washington's Government data](https://www.ofm.wa.gov/washington-data-research/population-demographics/population-estimates/estimates-april-1-population-age-sex-race-and-hispanic-origin):
* [Race and Hispanic](https://www.ofm.wa.gov/sites/default/files/public/dataresearch/pop/asr/race/ofm_pop_race_2010_and_2019.xlsx) - Washington State Office of Financial Management, Forecasting and Research Division, numbers from the 2010 census and estimates for the 2019 population.


## Research Questions Explored

The project will focus to answer the following:
1. Are certain demographics of police officers more likely to be involved in shootings?
    - are there certain pairing of police-to-victim demographics that appear more in the data?
    
    
2. Is there a precinct (geographical location) that shows more propencity to using force?


3. Is there a relation between the years of experience and their response to a crisis?


## Licence

Plese refer to the project [MIT license](https://github.com/JUAN-SOLORIO/data-512/blob/main/data-512-final/MIT_LICENSE.txt) for more details.
