# Visual-representation-of-the-relationship-between-post-secondary-school-count-and-unemployment-rate
This project integrate three datasets to examine the relationships between secondary school 
count, unemployment rate, and median household income by States.  
The repository provide code and available libraries to create regression lines, providing a visual representation of the 
relationships between the unemployment rate (y-axis), the number of post-secondary schools by state (x-axis), 
the 2022 national median household income (x-axis). Ultimately, it also offers recommendations to political 
leaders of these counties based on my findings.  
Data sources: 
I used data from the following sources to accomplish this project.  - - - 
Post secondary School geographic data:  
Source: National Center for Education Statistics, 2023 
https://nces.ed.gov/opengis/rest/services/Postsecondary_School_Locations/EDGE_GEOCODE_POSTSECONDARY
 SCH_2223/MapServer/0/query?outFields=*&where=1%3D1&f=geojson 
The Center EDGE program provides updated annual statistic for point location (latitude and longitude for 
post-secondary institutions included in the NCES Integrated Postsecondary Education Data System (IPEDS) 
(nces.ed.gov). The raw data has the OBJECTID, UNITID, NAME, STREET. CITY, STATE, ZIP, SFTIP, 
COUNTY, LOCALE, LAT, LON, CSBSA, NMCBSA, CBSATYPE, CSA, NMCSA, CD, SLDL, SLDU and 
SCHOOLYEAR columns.  
The code to download the dataset will be provided in separate file.  
Educational support services data 
Source: Quarterly Census of Employment and Wages - Bureau of Labor Statistics, 2023 
https://data.bls.gov/cew/apps/table_maker/v4/table_maker.htm#type=1&year=2023&qtr=A&own=2&ind=61
 1710&supp=0    
This includes information on employment and wages for State government educational support services 
(NAICS 611710) across all U.S. counties, for the 2023 year and covers all establishments sizes. The data 
has the reported US counties names, Annual Establishments, Annual Average Employment, Total Annual 
Wages, Annual Average Weekly Wage, Annual Wages per Employee, Annual Average Employment Location 
Quotient and Total Annual Wages Location Quotient.  
The code to download this dataset will be provided in separate file. 
County-level Data Set – national unemployment rate, 2023 
Source: Economic Research Service / U.S Department of Agriculture 
https://data.ers.usda.gov/reports.aspx?ID=4038  
This data set provide unemployment rate from 2015 to 2023 and the average median household income for 
2022. The website states that average annual unemployment data was unavailable for Puerto Rico in 2020 
because of missing monthly observations for March and April 2020.  
How to download? 
 Click on the source URL 
 In the state pane, select "NATIONAL” 
  
Below the save button , choose "Excel" to download the raw data. 
Detected issue 
The detected limitation is missing data for some states due to reporting issues. For this reason, only two datasets 
file will be used to produce the regression lines because of data join requirements.
