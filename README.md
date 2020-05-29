# Bureau of Prison API

I started to create a scraper for statistics section of BOP's website, but then after some exploration I managed to dig up the site's API.

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

For more info:
https://www.bop.gov/about/statistics/
