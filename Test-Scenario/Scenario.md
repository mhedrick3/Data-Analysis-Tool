##DATA CLEANSING TOOL SCENARIO
The scenario we want to use for this project is to combine population data, administrative district data, and church location data of Uganda into a single data store. We will be importing population figures, and area in kilometers for each district in Uganda along with the district boundaries. We will create a population density by district for individuals under the age of 18 by calculating and storing the number of people per square kilometer. By combining this information with the church locations, we can identify potential church partnerships for Compassion’s program based on youth population density.

-	Uganda District population projections 2015-2020 (includes api to access data) - http://catalog.data.ug/dataset/uganda-s-district-population-projections-2015-2020
-	Districts Administrative Boundaries (GeoJSON) - http://catalog.data.ug/dataset/districts-2014
-	Uganda Church locations (a KML file) – Included in this folder
-	Uganda district area (km2) (CSV file)  - Included in this folder

The goal is to integrate this data in a way that uses a common formatting for like fields (i.e. dates, numbers stored as text conversion) and common values (i.e. common set of country and region names). 
