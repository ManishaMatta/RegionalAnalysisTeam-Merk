# RegionalAnalysisTeam

### Problem Statement
This project endeavors to comprehensively analyze and map out the socio-economic landscape of the U.S.-Mexico border region. By delving into various socio-economic indicators such as income levels, educational attainment, employment rates, healthcare accessibility, and housing conditions, the project seeks to offer a detailed understanding of the economic and social dynamics at play in this area. 

### [Project Video](https://www.youtube.com/watch?v=pt5gMPiQQZg)
<!--<iframe width="560" height="315" src="https://www.youtube.com/embed/pt5gMPiQQZg" frameborder="0" allowfullscreen></iframe> -->


### [ESRI Dashboard](https://sdsugeo.maps.arcgis.com/apps/dashboards/7806834971f84cab950fd2daa7a20be3)
<!-- <iframe width="100%" height="600px" src="https://sdsugeo.maps.arcgis.com/apps/dashboards/7806834971f84cab950fd2daa7a20be3"></iframe> -->
<!-- https://sdsugeo.maps.arcgis.com/apps/dashboards/7806834971f84cab950fd2daa7a20be3 -->


### Data Source 
1. [United States Census Bureau](https://data.census.gov/) : Census API for using American Community Survey (ACS) data
The data is extracted from the American Community Survey (ACS) and compiled into a singular table. From 23 counties in Texas, California, New Mexico, and Arizona 358 individual zip codes were extracted from those counties by selecting every zip code with at least 1000 residences. These zip codes form the basis of our analysis.
2. [U.S Department of Transportation](https://data.bts.gov/Research-and-Statistics/Border-Crossing-Entry-Data/keg4-3bc2/data): Border Crossing Entry Data
The dataset provides details on border crossing entries at U.S. ports, including traffic volume, transportation mode, demographics, and travel purpose, aiding in trend analysis and policy formulation.
3. Merck Shape File : US-Border Shapefile
US-Mexico Border Shapefile data provides geospatial information in Shapefile format, delineating the precise boundary lines for mapping and analysis.

### Social-Economic Determinent Analysis

* **Population Distribution - Border Crossing**
This analysis is built using the Border Crossing dataset extracted from the Bureau of Transportation.
This Map indicates the number of people crossing the US- Mexico border based on the size of the bubble. It also indicates the mode of their travel which is classified based on the color used to indicate each bubble.
The pop-up indicated all the details along with their port of entry.
Thus with this analysis we can understand and conclude that the most common means of border crossing is done as "Personal Vehicle Passengers" and the main point of entries are San Ysidro, El Paso and Hidalgo 
 
* **Population Distribution - Children**
This analysis is built using the American Census Survey[ACS] dataset extracted from the Census Bureau.
This Map indicates the number of Children below 18 years of age in the US- Mexico border. The ArcGIS Map have boundaries for each zipcode. The red- blue color the low-high variance of number of children in each zipcode.
The pop-up indicated all the the variance of total population to the number of children in the selected area.
Thus with this analysis we can understand and conclude that the higher population of children are present in the east & west coastal regions compared the the central border regions like Presidio & Terrell etc.
 
* **Population Distribution - Profession**
This analysis is built using the American Census Survey [ACS] dataset extracted from the Census Bureau.
This Map indicates the 4 different professional categories which are Male Professional, Female Professional, Armed Forces LaborForce, Unemployed LaborForce in the US- Mexico border. The ArcGIS Map have boundaries for each zipcode. The most prominent profession in each zipcode is highlighted in the map.
The pop-up describes each value explicitly and also adds a bar chart which give us the comparative analysis of the data distribution across the borders
Thus with this analysis we can understand and conclude that there are more Unemployed LaborForce in at costal regions compared to the other regions like in Cameron, Hidalgo and understand the increase in number on Armed Forces LaborForce in San Diego, Kinney and Yuma.
 
* **Population Distribution - HealthInsurance**
This analysis is built using the American Census Survey [ACS] dataset extracted from the Census Bureau.
This Map indicates the 4 different categories for Non availability of Health Insurance based on the age group from < 19 years, 19-34 years, 35 to 64 years and > 65 years in the US- Mexico border. The ArcGIS Map have boundaries for each zipcode. The most prominent age group with no health insurance in each zipcode is highlighted in the map.
The pop-up describes each value explicitly across the border.
Thus with this analysis we can understand and conclude that the most age group which do not have health insurance are among 19 to 34 years followed by people under 19 years.
 
* **Population Distribution - Poverty**
This analysis is built using the American Census Survey [ACS] dataset extracted from the Census Bureau.
This Map indicates the 2 different categories which are Poverty Level and Status in the US- Mexico border. The ArcGIS Map have boundaries for each zipcode. The blue & orange color in the map actually indicates a anomaly correlation increase poverty level with lower status and vice versa. The pop-up describes each value explicitly across the border.
Thus with this analysis we can understand and conclude that they are majorly present at Imperial & Cameron.
 
* **Population Distribution - Demographics**
This analysis is built using the American Census Survey [ACS] dataset extracted from the Census Bureau.
This Map indicates the 6 different categories of population distribution as demographics like White, Hispanic Latino, Black AfricanAmerican, Asian, AmericanIndian AlaskaNative, NativeHawaiian Other PacificIslander  Total Population in US- Mexico border. The ArcGIS Map have boundaries for each zipcode. The most prominent category is indicated for each zipcode. 
The pop-up describes each value explicitly across the border.
Thus with this analysis we can understand and conclude that the major ethnic group across the borders are white and hispanic.
 
* **Population Distribution: Languages Spoken**
This analysis is built using the American Census Survey [ACS] dataset extracted from the Census Bureau.
This Map indicates the 15 different categories of population distribution based on the language spoken at home along with their age distribution in Total Population in US- Mexico border. The ArcGIS Map have boundaries for each zipcode. The gradient value of the number of people speaking a language for each zipcode. We can chose different layers to access each category
The pop-up describes each value explicitly across the border.
Thus with this analysis we can understand and conclude that the language distribution follows the population density graph.
 
* **Population Distribution - Educational Attainment**
This analysis is built using the American Census Survey [ACS] dataset extracted from the Census Bureau.
This Map indicates the 23 different categories of population distribution based on their different  educational background in US- Mexico border. The ArcGIS Map have boundaries for each zipcode. The gradient value of the number of people persued a course for each zipcode. We can chose different layers to access each category
The pop-up describes each value explicitly across the border.
Thus with this analysis we can understand and conclude that the education distribution follows the population density graph.
 
* **Population Distribution - Accessibility**
This analysis is built using the American Census Survey [ACS] dataset extracted from the Census Bureau.
This Map indicates the 3 different categories of population distribution based on their disability across different age group  in US- Mexico border. The ArcGIS Map have boundaries for each zipcode. The gradient value of the number of people who are disabled for each zipcode. We can chose different layers to access each category
The pop-up describes each value explicitly across the border.
Thus with this analysis we can understand and conclude that the accessibility requirement follows the population density graph.
 
* **Population Distribution - Gender**
This analysis is built using the American Census Survey [ACS] dataset extracted from the Census Bureau.
This Map indicates the 2 different categories which are Male and Female Population in the US- Mexico border. The ArcGIS Map have boundaries for each zipcode. The blue & orange color in the map actually indicates a anomaly correlation where the populations are out of balance. The pop-up describes each value explicitly across the border, it also has a bar chart which indicates the distribution.
Thus with this analysis we can understand and conclude that Pima, Dona Ana & Cochise have such imbalance when compared .
 
* **Population Distribution - Public Assistance**
This analysis is built using the American Census Survey [ACS] dataset extracted from the Census Bureau.
This Map indicates the variation of household which require financial aid in the US- Mexico border. The ArcGIS Map have boundaries for each zipcode. The gradient value depicts the changes in number of houses across zipcodes. The pop-up describes each value explicitly across the border.
Thus with this analysis we can understand and conclude that the household aid follows the population density graph.
 
* **Population Distribution - Income**
This analysis is built using the American Census Survey [ACS] dataset extracted from the Census Bureau.
This Map indicates the variation of income below the poverty level in the US- Mexico border. The ArcGIS Map have boundaries for each zipcode. The gradient value depicts the changes in income across zipcodes. The pop-up describes each value explicitly across the border.
Thus with this analysis we can understand and conclude that the Income per household follows the population density graph.
 
* **Population Distribution - Citizenship**
This analysis is built using the American Census Survey [ACS] dataset extracted from the Census Bureau.
This Map indicates the variation of place of birth in the US- Mexico border. The ArcGIS Map have boundaries for each zipcode. The gradient value depicts the changes in people count across zipcodes. The pop-up describes each value explicitly across the border.
Thus with this analysis we can understand and conclude that the citizenship status follows the population density graph.
 
* **Population Distribution - Household Size**
This analysis is built using the American Census Survey [ACS] dataset extracted from the Census Bureau.
This Map indicates the variation of place of birth in the US- Mexico border. The ArcGIS Map have boundaries for each zipcode. The gradient value depicts the changes in household size across zipcodes. The pop-up describes each value explicitly across the border.
Thus with this analysis we can understand and conclude that the household size follows the population density graph.

### Correlation Analysis
![correlation_matrix](https://github.com/ManishaMatta/RegionalAnalysisTeam-Merck/assets/50313389/5d9aa7c4-8544-4562-b927-39e75d347e48)

**Unemployed Labor Force:**
* Strong positive correlation with Total Population (0.930), Female Population (0.903), and Educational Attainment for individuals aged over 25 (0.904).
* These correlations suggest that areas with higher unemployment tend to have larger total populations, higher proportions of females, and higher levels of educational attainment among individuals over 25.
**No Health Insurance Coverage:**
* Strong positive correlation with Hispanic/Latino Total Population (0.933), Total Households receiving Public Assistance (0.927), Disability (0.811), and No School Educational Attainment for individuals over 25 (0.796).
* Additionally, there's a moderate positive correlation with Unemployed Labor Force (0.700).
* These correlations suggest that areas with higher rates of uninsured individuals tend to have larger Hispanic/Latino populations, higher levels of household public assistance, higher rates of disability, and lower levels of school educational attainment among individuals over 25. There's also a weaker association with unemployment.

### Conclusion
In conclusion, this project offers a comprehensive analysis of the socio-economic dynamics within the US-Mexico border region. By amalgamating census data with transportation datasets, it unveils insights into residents' well-being and vaccine distribution behaviors. 
Correlation analysis exposes that higher unemployment correlates with larger populations, increased female representation, and elevated educational attainment. Moreover, areas with a higher prevalence of uninsured individuals tend to exhibit larger Hispanic/Latino populations, heightened rates of public assistance, increased disability cases, lower educational attainment, and a weaker association with unemployment. 
These findings contribute to a nuanced understanding of the region's socio-economic fabric and hold implications for targeted interventions and policy decisions.

### Future Scope
* Merck Investigator Program, Vaccine Confidence
* Temporal analysis for trend identification
* Geospatial modeling for predictive insights
* Cross-border collaboration for better decision-making
















