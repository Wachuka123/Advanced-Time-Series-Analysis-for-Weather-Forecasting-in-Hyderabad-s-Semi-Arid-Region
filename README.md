# Advanced-Time-Series-Analysis-for-Weather-Forecasting-in-Hyderabad-s-Semi-Arid-Region
 This project develops a predictive model for agricultural weather in Hyderabad. It uses SARIMA to forecast temperature and rainfall. The model analyzes historical data and seasonal patterns. It aims to improve agricultural planning and water management
# Developing a Deep Learning Model for Predicting Agricultural Weather Conditions and Crop Water Requirements in Hyderabad, India Using Time Series Data

## List of contributors:
    Name	                           Github
    1. Edwin Mutendwa                  https://github.com/Mutendwa 
    2. 
    3.                   
    4. 
    5. 






***Keywords:*** Deep Learning, Time Series Data, Agricultural Weather Conditions, Crop Water Requirements, Hyderabad, India

## Overview

This project focuses on leveraging deep learning techniques to predict agricultural weather conditions and crop water requirements in Hyderabad, India. Hyderabad, located in the semi-arid region of Telangana, experiences diverse climatic influences that significantly impact its agriculture, economy, and daily life. The city's weather patterns, including temperature variations, humidity levels, and rainfall, play a crucial role in shaping agricultural productivity and water resource management. Given the challenges posed by climate change, accurately understanding and forecasting these weather patterns are essential for effective planning and management in sectors like agriculture and water resources.

## Context

India, a nation of rich cultural and historical heritage, is characterized by diverse ethnicities, languages, and religions. It has a varied geographical landscape, ranging from the Himalayas in the north to the Deccan plateau in the south. The country experiences a tropical monsoon climate, with distinct wet and dry seasons affecting agriculture significantly. Hyderabad, as a major city in southern India, exemplifies these climatic complexities, making it an ideal study area for predicting and managing agricultural weather conditions using advanced deep learning models.

![India_240-animated-flag-gifs](https://github.com/WanjuguN/Phase-4_Group-4-Project/assets/151353695/e688bec8-7cd9-48d2-abc5-521c36fd805b)


## Significance:
Understanding India's climatic diversity and its impact on agriculture is crucial for sustainable development and disaster preparedness. This project aims to contribute to this understanding by developing a predictive model that can aid farmers, policymakers, and researchers in making informed decisions regarding crop management, water resource allocation, and disaster mitigation strategies in Hyderabad and similar regions.

## Problem Statement
Accurately predicting weather conditions in Hyderabad, India, particularly critical events like droughts and extreme temperatures, remains a significant challenge. The existing models often fail to incorporate the complex interplay between time series and geospatial data, leading to less reliable forecasts. This gap in accurate weather prediction hinders effective agricultural planning and water resource management, which are crucial for sustaining the region's agrarian economy. Therefore, there is a pressing need to develop an advanced predictive model that can reliably forecast weather conditions by integrating various data types and capturing intricate weather patterns. This study aims to address this need by utilizing deep learning techniques to improve prediction accuracy and provide actionable insights for stakeholders.

## Research Statement
The research aims to leverage deep learning techniques to develop a robust predictive model for weather conditions in Hyderabad. By incorporating both time series and geospatial data, the study will explore trends, patterns, and correlations among various weather parameters. The primary focus will be on predicting critical weather events, such as droughts and extreme temperatures, and understanding their impact on crop water requirements. This research will not only contribute to the scientific community's understanding of weather dynamics in the semi-arid tropics but also provide valuable insights for agricultural planning and water resource management in the region.

## Data Source

The dataset for this research is provided by the International Crops Research Institute for the Semi-Arid Tropics (ICRISAT), an esteemed international non-profit organization dedicated to scientific research for development. Established in 1972, ICRISAT is headquartered in Patancheru, Hyderabad, India, and operates several regional centers across Africa, including Bamako (Mali) and Nairobi (Kenya), as well as research stations in Niamey (Niger), Kano (Nigeria), Lilongwe (Malawi), Addis Ababa (Ethiopia), and Bulawayo (Zimbabwe). India, the host country, has granted ICRISAT special status as a UN Organization, providing it with unique immunities and tax privileges.

ICRISAT has been collecting daily weather data in Hyderabad since 1978, resulting in a comprehensive dataset that spans over 40 years. This dataset includes crucial weather parameters such as maximum and minimum temperatures, relative humidity (morning and afternoon), wind speed, rainfall, bright sunshine hours, evaporation, radiation, and reference crop evapotranspiration (FAO56-ET). Additionally, it encompasses geospatial data, including longitude and latitude, enhancing the depth and scope of weather analysis.

## Research Objectives
1. Develop and validate a deep learning model to accurately predict future weather conditions using historical time series and geospatial data.
2. Analyze trends and patterns in historical weather data to identify significant seasonal and geographical variations.
3. Utilize K-means clustering to classify seasons in Hyderabad.

## Research Problems
1. How can a deep learning model be developed to predict future weather conditions, incorporating historical and geospatial data?
2. What trends and correlations exist in the weather data over time and across different locations?
3. How can seasonal variations in weather patterns in Hyderabad be effectively characterized and understood, considering the dynamic nature of climatic conditions?

Hypothesis¶

**Objective 1: Develop and validate a deep learning model to accurately predict future weather conditions using historical time series and geospatial data.**

***Null Hypothesis (H01):*** There is no significant relationship between historical time series data, geospatial data, and the accuracy of the deep learning model in predicting future weather conditions.

***Alternative Hypothesis (H11):*** There is a significant relationship between historical time series data, geospatial data, and the accuracy of the deep learning model in predicting future weather conditions.


**Objective 2: Analyze trends and patterns in historical weather data to identify significant seasonal and geographical variations.**

***Null Hypothesis (H02):*** There are no significant seasonal and geographical variations in historical weather data.

***Alternative Hypothesis (H12):*** There are significant seasonal and geographical variations in historical weather data.


**Objective 3: Utilize K-means clustering to classify seasons in Hyderabad.**

***Null Hypothesis (H0):*** There is no significant difference in seasonal weather patterns in Hyderabad that can be classified using clustering techniques.

***Alternative Hypothesis (H1):***
Seasonal weather patterns in Hyderabad exhibit significant differences that can be effectively classified and understood using clustering techniques.

## Data Source

The dataset for this research is provided by the International Crops Research Institute for the Semi-Arid Tropics (ICRISAT), an esteemed international non-profit organization dedicated to scientific research for development. Established in 1972, ICRISAT is headquartered in Patancheru, Hyderabad, India, and operates several regional centers across Africa, including Bamako (Mali) and Nairobi (Kenya), as well as research stations in Niamey (Niger), Kano (Nigeria), Lilongwe (Malawi), Addis Ababa (Ethiopia), and Bulawayo (Zimbabwe). India, the host country, has granted ICRISAT special status as a UN Organization, providing it with unique immunities and tax privileges.

ICRISAT has been collecting daily weather data in Hyderabad since 1978, resulting in a comprehensive dataset that spans over 40 years. This dataset includes crucial weather parameters such as maximum and minimum temperatures, relative humidity (morning and afternoon), wind speed, rainfall, bright sunshine hours, evaporation, radiation, and reference crop evapotranspiration (FAO56-ET). Additionally, it encompasses geospatial data, including longitude and latitude, enhancing the depth and scope of weather analysis.

## Data Cleaning Process

![image](https://github.com/WanjuguN/Phase-4_Group-4-Project/assets/151353695/57572da1-1adb-4f62-9e89-ae4e1c8e6334)

## Exploratory Data Analysis (EDA)

### Data Point


The dataset originates from Hyderabad, India. Notably, all the longitudes and latitudes are identical (17.508409, 78.2723), which suggests the weather data was collected from a single location or observation point within Hyderabad. This is an important factor to consider when analyzing the data, as it might not represent weather conditions across the entire city.

### Correlation Heatmap

![image-1](https://github.com/WanjuguN/Phase-4_Group-4-Project/assets/151353695/4b5fae9c-00ef-41d4-8f9e-4b7d39d517b8)

The figures represent a correlation matrix for several weather-related variables. Each value shows the Pearson correlation coefficient between pairs of variables. A value of 1.0 indicates a perfect positive correlation, -1.0 indicates a perfect negative correlation, and 0 indicates no correlation. For instance, MaxT (maximum temperature) has a strong positive correlation with Evap (evaporation) at 0.876, meaning higher temperatures are associated with higher evaporation rates. Conversely, MaxT has a strong negative correlation with RH1 (relative humidity in the morning) at -0.737, indicating that higher temperatures tend to occur with lower morning humidity. MinT (minimum temperature) shows moderate correlations with several variables, like MaxT at 0.537 and FAO56_ET (reference crop evapotranspiration) at 0.505. Rainfall (Rain) has weaker correlations with most variables, with the highest being a moderate positive correlation with RH2 (relative humidity in the afternoon) at 0.356. SSH (bright sunshine hours) negatively correlates with both relative humidity measures and positively with variables like Radiation at 0.744, suggesting that more sunshine is linked with higher radiation levels but lower humidity. Overall, the matrix reveals how different climatic variables are interrelated, highlighting both direct and inverse relationships.

### Identifying any weather patterns in Hyderabad - Kmeans clustering
#### K_means clustering

![image-2](https://github.com/WanjuguN/Phase-4_Group-4-Project/assets/151353695/57a245e8-a5de-4925-acf4-ddfabff05beb)

The output is a scatter plot showing the results of KMeans clustering applied to a dataset that has been reduced to two principal components using PCA. Each point represents a data sample, plotted according to its values on the first two principal components. The colors indicate the clusters assigned by the KMeans algorithm, with three distinct clusters visible (yellow, purple, and teal). The red 'X' markers represent the centroids of each cluster, which are the central points calculated by the KMeans algorithm. These centroids are used to assign each data point to a cluster based on the shortest Euclidean distance to the centroid. This visualization helps to understand the separation and distribution of the clusters in a two-dimensional space. The clear separation between the colors indicates that the KMeans algorithm has effectively partitioned the data into three clusters.

#### Time Series

![image](https://github.com/WanjuguN/Phase-4_Group-4-Project/assets/151353695/ac7b5430-19b3-4d4e-bdd5-bf66cb805607)

The plot shows a highly variable pattern with occasional spikes indicating periods of heavy rainfall. Notably, there is a significant spike around the year 2000, suggesting an exceptionally high rainfall event. Hyderabad reported significant rainfall in 2000. News reports and historical accounts mention heavy downpours, particularly in August 2000.


## Machine Learning

### Sarima model for Average Temperature- Machine learning

![image](https://github.com/WanjuguN/Phase-4_Group-4-Project/assets/151353695/04667434-6b61-48d5-8077-c7f164688dfa)

### Sarima model for Rain- Machine learning

![image](https://github.com/WanjuguN/Phase-4_Group-4-Project/assets/151353695/1913cf13-8106-44c0-9ec5-1c55cb2df81f)

## Deep Learning
### Best deep Model for  Average Temperature prediction

![image](https://github.com/WanjuguN/Phase-4_Group-4-Project/assets/151353695/f0a64583-91d9-4fbd-8174-3764c0b21577)

### Best deep Model for  Rain prediction

![image](https://github.com/WanjuguN/Phase-4_Group-4-Project/assets/151353695/280f7bd5-ea62-4b85-8c69-0dcaaac5aa22)

## Exploratory Data Analysis (EDA) Recommendations for Farmers
### Temperature Trends

***Warmer Months:*** Peak temperatures occur from May to July, reaching highs around 35°C.

***Cooler Months:*** January, February, November, and December experience lower maximum temperatures below 25°C.

#### Recommendations:

***Crop Selection:*** Opt for heat-tolerant crops during warmer months and those needing cooler temperatures during cooler months.

***Irrigation Management:*** Increase irrigation frequency during warmer months due to higher evaporation rates. Use efficient irrigation systems.

***Shade Structures:*** Consider temporary shade for sensitive crops during peak heat months to avoid heat stress.

### Rainfall by Month

***Peak Rainfall:*** Significant rain falls in June, July, and August, often exceeding 100 mm.

***Dry Periods:*** Minimal rainfall occurs in January, February, and March.

#### Recommendations:

***Planting Schedule:*** Plan planting before the rainy season (April) for rain-fed crops to ensure sufficient water for germination.

***Water Conservation:*** Implement rainwater harvesting during peak rainfall to store water for dry periods.

***Soil Erosion Prevention:*** Use cover crops, contour farming, and maintain vegetation cover to minimize soil erosion.

***Flood Management:*** Construct drainage systems and raised beds in flood-prone areas.

## Machine Learning Recommendations
### Best Model for Predicting Rainfall: SARIMA
1. Performance: Achieved low Mean Squared Error (MSE) of 0.8991.
2. Methodology: SARIMA effectively captures seasonal patterns by resampling monthly averages.
## Deep Learning Recommendations
1. Best Model for Predicting Temperature: Enhanced LSTM
2. Performance: High R² score of 91, indicating reliability.
3. Methodology: Utilizes sequences of normalized temperature data with three LSTM layers for accurate predictions.
## Limitations of the Study
1. Single Collection Point: Data from one location may limit generalization.
2. emporal Variations: Complex factors like climate change may not be fully captured.
3. Data Quality: Accuracy and completeness impact model performance.
## Conclusion
This study used advanced EDA, machine learning, and deep learning to model weather patterns in Hyderabad, India, enhancing agricultural decision-making and resource management. These methods are crucial for adapting to climate challenges and improving agricultural practices.
