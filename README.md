# Insights into Urban Dynamics: Analyzing Airbnb Reviews and Neighborhood Metrics

## Project Overview

This study explores the relationship between subjective Airbnb reviews and objective neighborhood metrics in specific US cities. The analysis involves crime statistics, demographics, socioeconomic indicators, environmental quality, aligning them with sentiments expressed in Airbnb reviews.
---
### Objectives

- Investigate correlations between subjective reviews and quantifiable neighborhood attributes in targeted US cities.
- Understand how guest experiences align with tangible neighborhood characteristics.
---
### Methodologies and Tools

- **Data Collection**: Utilize Python libraries (e.g., Pandas, Requests) for data collection and preprocessing.
- **Correlation Techniques**: Employ regression analysis, correlation coefficients and other analysis techniques(cluster, principle component, etc.)
- **Visualization**: Use Matplotlib or Plotly or Seaborn for visual representation of relationships.
- **Sentiment Analysis**: Implement TextBlob for sentiment analysis of Airbnb reviews and consider numerical ratings.
---
### Data Collection and Analysis

#### Airbnb Review Sentiment

- **Data Collection**: Extract Airbnb review texts and numerical ratings.
- **Methodology**: Use TextBlob for sentiment analysis of review texts and numerical ratings for quantitative analysis.

#### Crime Statistics

- **Data Collection**: Retrieve crime data (bjs.gov and city-data.com)
- **Methodology**: Match crimes to specific neighborhoods mentioned in reviews using geocoding techniques.

#### Demographic and Socio-economic Data

- **Data Collection**: Access census databases for population, income, education, and cost-of-living data in reviewed neighborhoods. Kaggle dataset available
- **Methodology**: Conduct demographic profiling, segmentation, regression, and correlation analysis.

#### Environmental Quality

- **Data Collection**: Obtain air quality, pollution (epa.gov) 
- **Methodology**: Spatial analysis to correlate environmental factors with review sentiments.
---
### Anticipated Challenges
<<<<<<< HEAD
- Joining data on location (city names vs long/lat, vs zip codes
- Scraping descriptive keywords from reviews
- Learning Github
- Selecting the ~right~ variables to compare
- Correlation vs. Causation
- Temporal Changes - Socioeconomic factors and Airbnb ratings may change over time
=======
- Data integration challenges (location data, scraping keywords).
- Learning curve with GitHub.
- Selecting relevant variables for comparison.
- Distinguishing correlation from causation.
- Addressing temporal changes in socioeconomic factors and reviews.
- Addressing Short-Term Rentals vs Long-Term Rentals
>>>>>>> 532822dc3916870c5e92ceeb42ef334768fa9d10

---
### Expected Results
<<<<<<< HEAD
Locations with higher cost of living have higher ratings
Warmer locations have higher ratings
Suburban locations have higher rating
Closer vicinity to the beach equals a higher rating
Newer houses have a higher rating 
Lower income areas have lower ratings
Areas with higher crime rates have lower ratings. 
=======
- Higher ratings in areas with higher cost of living, warmer climates, close proximity to the beach, suburban settings, and newer houses.
- Lower ratings in lower-income areas and those with higher crime rates.
>>>>>>> 532822dc3916870c5e92ceeb42ef334768fa9d10

### Conclusion
---
This study aims to understand how subjective Airbnb reviews align with objective neighborhood metrics in specific US cities, shedding light on the dynamics shaping urban perceptions in these areas.
