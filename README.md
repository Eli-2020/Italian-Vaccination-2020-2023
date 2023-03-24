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
Analysis of Italy vaccination campaign of covid-19 in 2021, the italian government got four diffenrent types of vaccines to protect the population,
## Description
This is a project developed at the [CRI](https://cri-paris.org/en) Université de Paris in the second semester of the Master of Digital Science, within the [Challenge Hub](https://master.cri-paris.org/en/challenge-hub) program.
The project is an analysis of the vaccination campaign against covid-19 in Italy that began in 2020, it is using three different types of vaccines, which need two doses to be effective, also have different times between the first dose and the second, likewise, their availability and quantities are different.
The age groups are eight, the first is made up of young people between 16 and 19 years old, the following groups are for ten years up to 89 years and the last one is ninety years or more.

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

* Italian vaccine campaign Date (December 27, 2020 to may 25, 2021) 
* source: [Italian Vaccination](https://www.kaggle.com/arthurio/italian-vaccination)

## Dataset

the file contains information by groups of vaccinated people grouped by date and company supplier of the vaccine, It does not have individual registers that allow for groupal analysis, for example combining gender and age.

shape (57618, 22)

* Administration date: date of the vaccine administration
* Vaccine supplier: Pfizer, Astrazeneca and Moderna
* Region: abbreviation of the Italian region
* Age range: age group
* Number of males: number of vaccinated males
* Number of females: number of vaccinated females
* Number of healthcare workers: number of vaccinated healthcare workers
* Number of non-healthcare workers: number of vaccinated non-healthcare workers
* Care home patients: number of vaccinated care home patients
* Number of 60-69 people: number of vaccinated people aged 60-69
* Number of 70-79 people: number of vaccinated people aged 70-79
* Number of over 80: number of vaccinated people aged 80+
* Armed forces: number of vaccinated military personnel
* School staff: number of the vaccinated school staff
* Vulnerable subjects: number of vaccinated vulnerable subjects
* Others: number of vaccinated people from other categories
* First dose: number of administered first vaccine doses
* Second dose: number of administered second vaccine doses
* NUTS1 code: European code for major socio-economic regions
* NUTS2 code: European code for basic regions for the application of regional policies
* ISTAT code: region code by Italian National Institute of Statistics
* Region name: full name of Italian regions

## Streamlit

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
