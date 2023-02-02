# Spatial Analysis of the Intersection of HIV and COVID-19 Epidemics in California
<i> Individual Analysis Project for GEO448: Spatial Data Science at DePaul University </i><br>
<i>Highlights: Spatial Join, Spatial Clustering, Spatial Outlier Detection, Agglomerative Clustering </i><br>

Analysis explores the spatial relationship between the HIV and COVID-19 in California at the county level. The analysis focuses on analyzing new infection rates between the two epidemics and its impact on ethnic and minority groups. Through spatial clustering and outlier detection techniques, specific areas in California were determined to be more vulnerable to HIV and/or COVID-19. LISA interactive map was created to show significant clusters affected by both infection rates and social vulnerabilities. Agglomerative clustering was performed showing areas affected by higher social vlunerability related to ethnic and minority status.

- HIV Data: 3 datasets were used for the analysis which came from AIDsVu, a partnership between Gilead Sciences Inc., and the Center for AIDS Research at Emory University. The <a href="https://aidsvu.org/resources/#/datasets">datasets</a> include: 2020 National New Infections, 2020 National Prevalance, and 2020 National PrEP. <br>
- COVID-19 Data: 2 datasets were used for the analysis which came from the California Department of Public Health Open Data Database. The datasets include: <a href="https://data.ca.gov/dataset/covid-19-time-series-metrics-by-county-and-state">Statewide COVID-19 Cases Deaths Tests</a> and <a href="https://data.ca.gov/dataset/covid-19-vaccine-progress-dashboard-data">COVID-19 Vaccine Progress</a>. <br>
- Shapefiles: <a href="https://www.atsdr.cdc.gov/placeandhealth/svi/index.html">2020 Social Vulnerability Index (SVI)</a> for California by county comes from the CDC containing census tracts and spatial geometry data. 

Methodology:<br>
1. Data Preprocessing
2. Exploratory Data Analysis 
3. Exploratory Spatial Data Analysis 
4. Agllomerative Cluster Analysis 
For this analysis, rates insteas of case counts provided more beneficial insights due to the volume of HIV and COVID-19 cases. 

Summary of Results:<br>
Significant spatial clusters and outliers appear in different areas for HIV infection rate compared to COVID-19 infection rate. Highly significant clusters appear in counties in Southern California such as Los Angeles, Ventura, Orange, San Bernadino, Riverside, and San Diego as well as Bay Area counties including Marin, Contra Costa, and Alameda. In contrast, for COVID infection rate, clusters appear in Central California including Kern, Tulare, Madera, and Mariposa counties. The analysis shows that there are no significant spatial clusters or outliers between the two epidemics. In otherwards, there is no interaction spatially between the two. Highly significant clusters do appear in the exact same counties for racial and ethnic minority status as HIV infection, showing that there is significant overlap spatially between the two in these clusters. Moreover, by applying spatial weights, key areas in California can bevisualized and determiend as experiencing a higher social vulnerability regarding racial and ethnic minority status, socioeconomic status, and public health epidemics.
