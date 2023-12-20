# **Insights into Visitor Sentiments:** Analyzing Airbnb Reviews and Neighborhood Metrics
---
### **Project Overview**

This study aimed to investigate the correlation between subjective Airbnb reviews and objective neighborhood metrics in select US cities. It involved compiling crime statistics, demographics, socioeconomic indicators, and environmental metrics to understand how they relate to sentiments expressed in Airbnb reviews.

In contrast to prevailing research, which predominantly focuses on property-specific details, our approach transcends these limitations. Drawing inspiration from the comprehensive nature of Airbnb reviews, recognized for their substantive content, our study endeavored to decode broader perceptions and conditions pertaining to neighborhoods. We aimed to leverage location data embedded in these reviews, establishing a robust connection between subjective expressions and the tangible characteristics of urban development.

We hypothesized that leveraging location data could bridge the subjective impressions from reviews with the defining attributes of urban landscapes. Our objective was to contribute valuable insights that unravel the intricate relationship between subjective experiences and the objective realities within urban environments.

---
### **Objectives**
- Analyze how Airbnb listing attributes affect ratings
- Investigate correlations between subjective reviews and quantifiable rental property and neighborhood attributes in targeted US cities.
- Determine whether ratings can be predicted using neighborhood statistics
---

### **Data Collection & Cleaning**
 Created master analysis dataframe for Seattle, LA and New York using the following: 
1. **Inside Airbnb for listings and average ratings**
http://insideairbnb.com/get-the-data/  
2. **Inside Airbnb for individual review comments**
http://insideairbnb.com/get-the-data/  
3. **County Unemployment Rate**
https://www.kaggle.com/datasets/jayrav13/unemployment-by-county-us/data  
4. **State Crime Rates**
https://ucr.fbi.gov/crime-in-the-u.s/2019/crime-in-the-u.s.-2019/tables/table-1  
5. **County Gun Deaths**
https://www.kaggle.com/datasets/ahmedeltom/us-gun-deaths-by-county-19992019  
6. **State Cost of Living**
https://advisorsmith.com/data/coli/#data  
7. **County Demographics**
https://www.kaggle.com/datasets/muonneutrino/us-census-demographic-data  
8. **City Average temps**
https://www.kaggle.com/datasets/sudalairajkumar/daily-temperature-of-major-cities  

---
### **Methodologies and Tools**
- **Sentiment Analysis**: Implement TextBlob for sentiment analysis of Airbnb review comments and consider numerical ratings.
- **Visualization**: Use Matplotlib,Plotly,Seaborn for visual representation of relationships.
- **Correlation and Prediction Techniques**: Employ regression analysis, correlation coefficients and other analysis techniques

---
### Anticipated Challenges

- Data integration challenges (location data, scraping keywords).
- Learning curve with GitHub.
- Selecting relevant variables for comparison.
- Distinguishing correlation from causation.
- Addressing temporal changes in socioeconomic factors and reviews.
- Addressing Short-Term Rentals vs Long-Term Rentals

---
### Expected Results

- Higher ratings in areas with higher cost of living, warmer climates, suburban settings, and newer houses.
- Lower ratings in lower-income areas and those with higher crime rates.

---
### Conclusion

This study aims to understand how subjective Airbnb reviews align with objective neighborhood metrics in specific US cities, shedding light on the dynamics shaping urban perceptions in these areas.
