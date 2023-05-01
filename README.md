# Evaluating-Air-Quality-Trends-in-the-United-States-Since-1990

Contributors: Alexander Heger, Yu Ting Hung, Ishan Nagrani, Lingxuan Wang, Fanfei Zhao

## **Summary** <br>
This report analyzes over 30 years of air quality data from the United States Environmental Protection Agency's 3,327 measurement sites across the U.S. to characterize regional trends and to estimate daily air quality indices (AQI) given pollutant concentrations. We focus primarily on airborne pollutants whose impact on health spurred the approval of the 1990 Clean Air Act: Carbon Monoxide, Nitrogen Dioxide, Sulfur Dioxide, Ozone, Particulate Matter-2.5 microns, and Particulate Matter-10 microns. We display the seasonality of each of these pollutants based on region, and demonstrate the impact of human and environmental activity on their concentrations. Finally, we use statistical learning to train 3 regression models to predict daily AQI given pollutant information in combination with wind and temperature.


## **Problem Statement** <br>
Our goal is to illustrate trends in air quality in the United States, identifying which pollutants have contributed most to air quality changes over the years. Our analysis will include how weather, natural disasters, and select world events affect air quality as measured by the U.S. Environmental Protection Agency (EPA). We will use Google Cloud Platform's (GCP) Dataproc service to distribute and interact with daily air quality information from the EPA's Historical Air Quality data set (hosted on BigQuery) which includes data from collection points across the U.S. dating back to 1990.

## **Motivation** <br>
Air pollution is a significant problem with adverse health outcomes, so understanding air quality trends is crucial for effective management strategies. In this study, we explore six pollutants that were key drivers of the 1990 Clean Air Act whose standards brought about the generation of our data set. We chose this problem based on our knowledge that historical air quality data can identify sources of pollution, inform targeted interventions, and aid in the development of evidence-based approaches that promote environmental sustainability and protect public health.

## **Data Source** <br>
The EPA Historical Air Quality data set is hosted here on Google Cloud Platform.

The EPA's documentation for the data set can be found here.
