# DataMiningProject-MilitarySpending
Data Mining Project - Military Spending Analysis using Python

### 1.	State where the data came from
 __•	Military Spending Data:__ <br />
    &ensp;&ensp; https://www.sipri.org/databases/milex/sources-and-methods#sources <br />
    &ensp;&ensp; Excel file: SIPRI-Milex-data-1949-2016.xlsx <br />
    &ensp;&ensp; Military Spending, Military expenditure by country as percentage of gross domestic product, Military expenditure per capita <br />
__•	The per Person GDP Data:__ <br />
    &ensp;&ensp; https://data.worldbank.org/indicator/NY.GDP.PCAP.PP.CD?year_high_desc=true <br />
    &ensp;&ensp; csv file: API_NY.GDP.PCAP.CD_DS2_en_csv_v2.csv <br />

### 2.	Data Cleaning in Data Mining Process <br />
* Understand original data source <br />
    &ensp;&ensp;i.	data format and how to collect columns (county and 5-years data) <br />
*	Check un-necessary data (need to skip rows): first 5 rows (below Figure 1) <br />
* Check any in-correct value:  '. .', '...', 'xxx' <br />
* Check consistency value from different data source: ‘USA’ and ‘Unite State’ <br />
