Table of Content
================
* [Italy-Vaccination-2020 to 2023](#Italy-Vaccination-2020-to-2023)
  * [Description](#description)
  * [Installation guide](#installation-guide)
  * [Files](#files)
  * [Dataset](#dataset)
  * [Streamlit](#streamlit)
  * [Discussion](#discussion)
  * [Credits](#credits)
  * [Licensing](#licensing)
  * [Authors](#Authors)
# Italian-Vaccination-2020-2023
Analysis of Italy vaccination campaign of covid-19 between December 27, 2020 and March 22, 2023, the italian government got diffenrent types of vaccines to protect the population and two boosters to maintain the protection.  
## Description
This is the continuation of a project developed at the [CRI](https://cri-paris.org/en) Université de Paris in the second semester of the Master of Digital Science( May 2021), within the [Challenge Hub](https://master.cri-paris.org/en/challenge-hub) program.
It is a way of presenting the information regarding what has happened with the vaccination campaign in Italy through the streamlit tool, which allows the user to interact with the information in a friendly and close way.
See the previous [analysis](https://github.com/Eli-2020/Italy_vaccination_campaign).

## Installation guide

If you use conda, you can install: 

   * conda install pandas
   * conda install seaborn
   * conda install numpy

If you use pip, you can install: 

   * pip install pandas
   * pip install seaborn
   * pip install numpy
    
## Files

For this project, one downloaded file was used in the direction given above, 

* Italian vaccine campaign Date (December 27, 2020 to March 22, 2023) 
* source: [Italian Vaccination](https://www.kaggle.com/arthurio/italian-vaccination)

## Dataset

the file contains information by groups of vaccinated people grouped by date and company supplier of the vaccine, It does not have individual registers that allow for groupal analysis, for example combining gender and age.

shape (57618, 22)

* Administration date: date of the vaccine administration
* Vaccine supplier: Pfizer, Astrazeneca and Moderna
* Region: abbreviation of the Italian region
* Age range: age group
* Males: number of vaccinated males
* Females: number of vaccinated females
* First dose: number of administered first vaccine doses
* Second dose: number of administered second vaccine doses
* Previous infection: 
* Additional Booster Dose:
* Second Booster:
* db3: 
* NUTS1 code: European code for major socio-economic regions
* NUTS2 code: European code for basic regions for the application of regional policies
* ISTAT code: region code by Italian National Institute of Statistics
* Region name: full name of Italian regions

## Streamlit
[Streamlit-Dashboard](https://eli-2020-italy-vaccination-campaign-italy-ib2dqr.streamlit.app/)
## Discussion
- It remains to be analyzed if the vaccination had problems by region, if the youngest population group that includes minors should have been vaccinated in the first months and instead, the group over 90 years old should have been the priority or if the health personnel had to be vaccinated even faster. One point that is identified with all vaccines is that they have ups and downs in the number of vaccines applied, so determining which days the vaccination rate is lowered would be part of a new analysis.

## Credits
- The analysis of the dataset was carried out by **Eliseo Baquero** [@Eli-2020](https://github.com/Eli-2020)
- the file is in jupiternotebook format 
- "Italian-Campaign.pynb"

## Licensing
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Authors:
* **Eliseo Baquero** [@Eli-2020](https://github.com/Eli-2020)
