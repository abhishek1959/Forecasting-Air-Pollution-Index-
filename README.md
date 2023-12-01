# Forecasting-Air-Pollution-Index-
As We Know Blasting from open-pit coal mines causing massive air pollution so, In this Project I forecast Air Pollution Index from the data provided by Coal India Limited Company.

## Introduction :
Open-pit mining holds a firm grip on India's coal production landscape, as it remains the dominant method employed. Anticipated future coal demand suggests a robust trajectory ahead. However, the nation faces formidable environmental challenges arising from diverse mining activities, notably the emission of particulate matter and various gaseous pollutants. These issues have a detrimental impact on air quality, prompting concerns and limitations on coal utilization.

## Blasting from open-pit coal mines causing massive air pollution : 
The two main air pollutants in NCL coal fields are suspended particulate matter (SPM) and reparable particulate matter (RPM). Air quality monitoring is regularly carried out at both dustgenerating and nongenerating locations in the vicinity in order to evaluate the particulate pollution in and around the opencast mining projects of the Singrauli coalfield. SPM and RPM concentrations are predominate at coal working surfaces, coal yards, coal handling facilities, and haul roads used to transport coal, as well as close to drilling sites, in overburden, and on such haul roads. Air pollution measurements available via multisensory system are PM10, PM2.5, SO2, NO2, NOx, CO, NH3, O3 and BENZENE.

## We are analyzing the impact of blasting activities on air pollution in Coal India. The time series data consists of air pollution measurements taken during the time of blasting events. We had explored the data using a combination of the following statistical inference techniques:

### (a) Classification: Dataset follows Flow time series for the period of 3 months (1st feb - 1st may).
### (b) Curve fitting: I have polled the curve for air pollution level with respect to time refer code number 16 in which I diveided the x-axis in to 24 parts representing one single day.
### (c) Descriptive analysis: After decomposing the time series data using the seasonal_decompose function from statsmodels, we can analyze the resulting plots to draw conclusions about seasonality and trend, The trend component represents the long-term pattern or direction of the time series. It captures the overall upward or downward movement of the data over time. From the above time series data no trend is observed.
### The seasonal component represents the repetitive patterns or cycles that occur within the data. It captures regular fluctuations that repeat at fixed intervals. From the graph we observe the time interval of seasonal graph of every data is very small. Thus we observe no such seasonality in our time series data. In code number 14 measures of frequency, central tendency, dispersion or variation, and position of air pollution data are mentioned.
### (d) Explanatory analysis: The available air pollution measurements via the multi-sensory system include PM10, PM2.5, SO2, NO2, NOx, CO, NH3, O3, and BENZENE.

## Here are some of the key causes and effects of air pollution in Singrauli:
1. The release of particulate matter, sulfur dioxide (SO2), nitrogen oxides (NOx), and other pollutants during coal mining and burning processes leads to poor air quality.

2. Singrauli houses several thermal power plants that rely on coal as the primary fuel. These power plants emit a substantial amount of pollutants, including particulate matter, sulfur dioxide, nitrogen oxides, and carbon dioxide (CO2), which contribute to air pollution in the region.

3. Singrauli has various heavy industries such as aluminum smelters, cement plants, and chemical factories. These industries release pollutants into the air during their operations, including harmful gases, particulate matter, and volatile organic compounds (VOCs), contributing to air pollution.

4. Dust from construction sites, open areas, and unpaved roads is a significant contributor to air pollution in Singrauli. Construction activities without proper dust control measures can release particulate matter into the air, causing respiratory problems and reducing air quality.


### 1. Prolonged exposure to polluted air can lead to respiratory problems such as asthma, bronchitis, and other respiratory tract infections.

### 2. Air pollution in Singrauli not only affects human health but also has detrimental effects on the environment. It contributes to the acidification of water bodies, soil degradation, and damage to vegetation and ecosystems.

### 3. The release of greenhouse gases, particularly carbon dioxide from coal combustion, contributes to climate change. It exacerbates global warming and the associated impacts such as heatwaves, altered precipitation patterns, and other climate-related events.

 ## Some Important Points: 
1. Here we are filling NA values using cubic interpolatation. This ensures that the summary statistics, such as the meanand standard deviation, are less affected compared to filling with other values like zero or the mean. This helps to maintain the integrity of the statistical measures.

## ADFULLER TEST: 
The adfuller function from the statsmodels.tsa.stattools module is used to perform the Augmented Dickey-Fuller (ADF) test on each column in the DataFrame. The ADF test is a statistical test used to determine if a time series is stationary or not.
The ADF test examines whether a time series is nonstationary. The null hypothesis of the ADF test is that the time series is non-stationary. The alternate hypothesis is that the time series is stationary


