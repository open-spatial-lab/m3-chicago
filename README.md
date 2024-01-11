# My Block My Hood My City: Community Impact Data Visualization in Chicago, IL

## About

### OSL Data Collaboratory

This project is part of the Open Spatial Lab's 2023 Data Collaboratory. The Collaboratory is a 6-month program where OSL engages with social impact organizations to build a customized tool for data management, analysis, communication, and visualization. Engagement and feedback from My Block My Hood My City directly informed this work. 

Based at the University of Chicago Data Science Institute, the Open Spatial Lab creates open source data tools and analytics to solve problems using geospatial data science. Read more about OSL at https://datascience.uchicago.edu/research/open-spatial-lab/. 

### Project Scope

**About**: [My Block My Hood My City ](https://www.formyblock.org/)(M3) is a nonprofit organization based in Chicago with a mission to inspire youth, empower communities, and build a better world one block at a time. M3 runs programs for youth, seniors, and other residents to cultivate a deeper connection to their communities and the people within them in order to ensure everyone has what they need to succeed.

**Project**: OSL worked with My Block My Hood My City to develop an interactive map and visualization tool that tracks and communicates impact of M3 programs and activities. The tool integrates M3 program evaluation data along with community demographics and structural factors, including access to transportation and gang violence, to facilitate data-driven insights around its services and impact on its community. 

## Data Biography

### Community Variables
All demographic and socioeconomic community variables are sourced at the Census tract and zip code levels from the [American Community Survey (ACS) 2021 5-Year Estimates, via Social Explorer](https://www.socialexplorer.com/tables/ACS2021_5yr). Variables include
- Total Population
- Total Population: Hispanic
- Total Population: Not Hispanic or Latino
    - Black or African American alone
    - American Indian and Alaska Native alone
    - Asian alone
    - Native Hawaiian alone
    - Two or more races
    - White alone
 - Median Household Income (2021 inflation-adjusted)
 - Total Population 16-19 Years (_proxy for high school-aged youth_)
 - Total Population 16-19 Years: Not High School Graduate, Not Enrolled (Dropped Out)
 - Total Population 16-19 Years: High School Graduate, or Enrolled (In School)

### Transportation
Public transit Chicago Transit Authority rail/train lines, rail/train stations, and bus route shapefiles are from the [Chicago Data Portal](https://data.cityofchicago.org/browse?category=Transportation) (City of Chicago, 2023). 

### M3 Surveys
Anonymized re/post surveys on M3 youth program impacts and outcomes were conducted during the 2021-2022 school year, provided by M3. 

### M3 Block Clubs
[M3 Block Club locations](https://www.formyblock.org/blockclub) were provided by M3 and geocoded based on nearest street intersection by OSL. 

### M3 Partner Schools & Youth Programs Locations
M3 provided the names of its partner schools and youth programs with its [Explorer's Program](https://www.formyblock.org/explorers). 

