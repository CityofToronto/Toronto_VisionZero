This is a consulting project by City of Toronto which is being done at Insight Data Science Fellows Program. The City of Toronto Transportation Services� Vision Zero initiatives aim to predict traffic collision rates, understand the root causes of crashes, and devise countermeasures to reduce injuries and fatalities on city streets.  

### Description of Data
1. The dataset form City of Toronto contains collision occurrences and the actions and outcomes for individuals involved in them from 2000 - 2019.  The data is approximately 2.6 million rows by 38 columns.  Columns include the longitude/latitude of collisions, time of day, day of year, road conditions (wet, dry), actions taken by road users (e.g. driver going straight, driver turning, pedestrian crossing street), and injuries sustained.  An incomplete data dictionary can be found here: https://github.com/CityofToronto/vz_challenge/tree/master/transportation/collisions#data-dictionary

* The data ingestion pipeline for collisions comes from multiple sources with multiple degrees of data accuracy (and processing speeds) � the fatalities and serious injuries come from Toronto Police Services (TPS), while minor injury and property damage only collisions come from the Collision Reporting Centre (CRC).

2. Boundaries of City of Toronto Neighbourhoods.