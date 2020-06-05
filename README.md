# Bureau of Prison API

I started to create a scraper for statistics section of BOP's website, but then after some exploration I managed to dig up some of the bop.gov's API endpoints.

Quick Facts Enpoint:
--------------------

https://www.bop.gov/PublicInfo/execute/quickfacts?todo=query&output=json

The JSON response contains all of the following stats:

*Statistics for people in federal prisons*
+ Age
+ Citizenship
+ Ethnicity (Hispanic and Non-Hispanic)
+ "Gender"
+ Offenses
+ Prison Security Levels
+ Race
+ Restricted Housing
+ Sentences Imposed

*Population Statistics*
+ Number of people in BOP Custody
+ Number of people in privagely managed facilities
+ Number of people in other kinds of facilities

*Staff Statistics*
+ Staff Ethnicity/Race
+ Staff "Gender"

Facility Endpoint:
------------------
https://www.bop.gov/coronavirus/data/additional.json

*Information for individual facilities*
+ Name
+ Address
+ Bed Count (w/ male and female breakdown)

Corona Virus Endpoint:
----------------------
https://www.bop.gov/coronavirus/json/final.json

*Reported Corona Virus Stats by Facility:*
+ City
+ Inmate Deaths
+ Inmate Recoveries
+ Inmates Having Tested Positive
+ Staff Having Tested Positive
+ Staff Recoveries
+ Staff Death Amount
