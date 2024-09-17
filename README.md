# PM-Accelerator-Tech-Assessment
Tech Assessment for PM Accelerator Data Scientist

# *Weather Trend Forecasting Assessment*

## *Overview*
This project uses the "Global Weather Repository" dataset to forecast weather trends. The analysis is split into two parts: Basic and Advanced assessments, showcasing data cleaning, exploratory data analysis (EDA), and multiple forecasting models to predict future weather patterns.

## *Dataset*

The dataset contains daily weather information from cities around the world and includes 41 features such as temperature, precipitation, wind, humidity, and air quality indices.

- *Source*: [Kaggle - Global Weather Repository](https://www.kaggle.com/datasets/nelgiriyewithana/global-weather-repository/data)

### *Key Features*:
- last_updated: Timestamp of weather updates
- temperature_celsius: Temperature in Celsius
- precip_mm: Precipitation in millimeters
- humidity: Humidity level as a percentage
- air_quality_PM2.5: Air quality based on PM2.5
- And many more...

## *Basic Assessment*

### *1. Data Cleaning & Preprocessing*
- Handled missing values using the mean.
- Normalized numerical columns using MinMaxScaler.
  
### *2. Exploratory Data Analysis (EDA)*
- Visualized temperature trends over time.
- Analyzed precipitation distribution.

### *3. Forecasting Model*
- Built an ARIMA model to forecast temperature based on the last_updated feature.
- Evaluated model performance using *Mean Squared Error (MSE)*.

### *Code*
Refer to the *Tech Assessment.ipynb* file for step-by-step code and implementation.


## *Advanced Assessment*

### *1. Advanced EDA*
- Performed anomaly detection using *Isolation Forest* to identify outliers in temperature and precipitation data.

### *2. Multiple Forecasting Models*
- Built and compared multiple models such as *ARIMA* and *Prophet*.
- Combined forecasts using an ensemble approach for improved accuracy.

### *3. Unique Analyses*
- Conducted *Climate Analysis* by examining average temperature variations across countries.
- Analyzed the *Environmental Impact* by exploring the correlation between air quality and weather parameters.
- Performed *Spatial Analysis* using GeoPandas to visualize geographical weather patterns.

### *Code*
Refer to the *Tech assessment.ipynb* file for detailed advanced implementation.

## *Installation & Requirements*

To run this project locally, install the following dependencies:

bash
pip install pandas numpy matplotlib seaborn statsmodels scikit-learn fbprophet geopandas


## *Usage*

1. Clone this repository:

bash
git clone https://github.com/yourusername/weather-trend-forecasting.git


2. Navigate to the project folder:

bash
cd weather-trend-forecasting


## *Results*

- *Basic Assessment*: Demonstrates a simple time series forecast for temperature trends using ARIMA.
- *Advanced Assessment*: Explores multiple models, anomaly detection, and spatial analysis, providing deeper insights into weather trends.


## *Future Work*
- Further refinement of models by tuning hyperparameters.
- Integration of more complex machine learning models like LSTMs for enhanced time series predictions.


## *Contributors*
- Aditya Singh Thakur - Data Scientist
