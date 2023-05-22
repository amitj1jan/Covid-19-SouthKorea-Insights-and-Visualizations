## Covid-19-SouthKorea-Insights-and-Visualizations
### Summary
Explore and visualize the Covid-19 outbreak in South Korea with the Covid-19-SouthKorea-Insights-and-Visualizations project. Gain valuable insights into the impact of Covid-19 across provinces and understand the correlation between age, gender, and Covid-19 cases. The project includes data cleaning, cluster mapping, province-wise distribution, heatmap analysis of missing data, city-wise and overseas country-wise distribution, hypothesis testing, and correlation analysis. Python packages used include pandas, matplotlib, seaborn, missingno, altair, folium, geopandas, and more.

### Data Source: 
https://www.kaggle.com/kimjihoo/coronavirusdataset 

### Key Features
- **Data Cleaning and Preprocessing:** Explore and clean the patientinfo dataset to ensure data accuracy for analysis and visualizations.
- **Heatmap Analysis of Missing Data:** Create a heatmap representation of missing data patterns in the dataset, identifying the extent and patterns of missing 
- **Province-wise Distribution:** Visualize the distribution of Covid-19 cases across different provinces in South Korea, gaining insights into the geographical spread of the outbreak.
- **City-wise and Overseas Country-wise Distribution:** Plot the distribution of Covid-19 cases at the city and overseas country level, highlighting the impact of international travel and localized outbreaks.
- **Cluster Mapping with Folium:** Plot Covid-19 clusters on an interactive map using the Folium library, providing a spatial understanding of outbreak hotspots.
- **Track Covid Hotspots by Patient Routes:** Analyze and visualize the patient routes to track Covid-19 hotspots and understand the transmission patterns.
- **Hypothesis Testing and Correlation Analysis:** Conduct hypothesis tests to explore the relationship between age and Covid-19 deaths. Analyze correlations between gender, age, and confirmed cases to uncover meaningful insights.

### Observation
- Top five Covid-19 hit provinces in South Korea.
- Relationship between gender and Covid-19 cases, considering the impact of missing data.
- Strong positive correlation (0.76) between people's age and Covid-19 deaths.
- Strong negative correlation between gender and confirmed cases, indicating females are more likely to contract Covid-19.
- Weak positive correlation between Covid-19 deaths and confirmed cases, suggesting that males are more likely to die from Covid-19 compared to females.

### Package Versions
Python: 3.9.2, 
pandas: 1.2.3, 
numpy: 1.20.1, 
matplotlib: 3.3.4, 
seaborn: 0.11.1, 
missingno: 0.4.2, 
altair: 4.1.0, 
folium: 0.0.0, 
geopandas: 0.8.1, 
geopy: 1.22.0, 
shapely: 1.7.1
