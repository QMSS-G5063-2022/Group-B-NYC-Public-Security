# Group-B-NYC-Public-Security
## **Title: Exploring Connection between Home Ownership and Neighbourhood Safety**

#### Team Members
  - Huaqing Gu
  - Jinghan Ma jm5223@columbia.edu
  - Lin Wang linw05031@gmail.com
  - Hanzhi Zhang

**ABSTRACT:** Our group is interested in housing selection and security issues in New York city. For this project, we plan to use NYPD public safety data and New York city zip code data as major data sources, combining variables that represent total occupied housing units and owner-occupied units to create a new variable that measures the percentage of owner-occupied units per NYC zip code. We are looking forward to exploring the following questions:
  - How does the local crime rate impact housing density and occupancy rate? We plan to use graphs to visualise the relationship between housing density and counts of felony crimes in New York City.
  - How does the crime severity level impact housing distribution? Upon categorising different crime levels (felony, serious crime, robberies, dangerous weapons, etc), we expect to visualise a difference in selection.
  - How does selected demographic characteristics differ at the zip code level? Is there a spatial relationship existing within NYC?
  - How does certain statistical bias impact the results of our hypothesis? 
     a) Specifically in this project, why do we need to pay particular attention to the Modifiable Areal Unit Problem?
     b) Do statistically significant different felony crimes with high values occur in similar locations as statistically significant clusters for dangerous weapons? 

**Techniques:** GIS, python, R, Geoda, ggmap, ggplot

**Data Description:**
  - 2010 Census Demographic profile shapefile from the Tigerline census website to obtain 2010 zip code tabulation area data for the entire United States (https://www2.census.gov/geo/tiger/TIGER2010DP1/  File name=ZCTA_2010Census_DP1.zip ).  
  - Use the following shapefile for NYC zip code tabulation areas to subset the USA Demographic profile data to include NYC zip codes only (download NYC shapefile via drop-down menu on right hand side of this site: https://geo.nyu.edu/catalog/nyu_2451_34509)
  - Crime data for NYC from the following site: https://data.cityofnewyork.us/Public-Safety/NYPD-Complaint-Data-Current-YTD/5uac-w243 (offers data in both tabular and shapefile forms) 
  - Use data tool created by the nonprofit Measure of America of the Social Science Research Council: DATA2GO.NYC (offers a list of demographic variables by boroughs, community districts, and census tracts)

**Visualisation:**
  - Map: visualises a count of felony crimes in NYC zip codes, and creates a separate map for robberies only, dangerous weapons only, and dangerous drugs only.  
  - Line Chart : visualises the number of felonies in NYC change against time for different regions. If more felonies happen when holidays come? Or there have been more crimes in recent years.
  - Bar Chart : visualises the average number of felony for a specific hour to find out when there are more crimes happening.
  - Point Chart: visualises comparisons of the average number of felony between different areas of NYC (by time of the day and by home ownership)
  - Word Cloud: creates word clouds of the type of felony occurred and key words used in the description of police records for each region of NYC
