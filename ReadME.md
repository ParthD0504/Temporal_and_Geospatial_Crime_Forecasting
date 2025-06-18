# Crime Data Analysis and Forecasting

This repository contains a Jupyter Notebook that performs a comprehensive exploratory analysis and time-series forecasting on crime incident data from 2020 to the present. The analysis covers data cleaning, demographic and spatial breakdowns, seasonal and event-driven pattern detection, anomaly identification, and a 360-day ARIMA forecast of future crime counts.

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/ParthD0504/Temporal_and_Geospatial_Crime_Forecasting.git
   cd Temporal_and_Geospatial_Crime_Forecasting
   ```

2. **Install dependencies**  
   _Key libraries:_ numpy, pandas, matplotlib, seaborn, statsmodels

3. **Download the data**  
   Place `Crime_Data_from_2020_to_Present.csv`

4. **Launch the notebook**
   ```bash
   jupyter notebook notebooks/crime_forescasting.ipynb
   ```

## 📝 Notebook Outline

1. **Data Loading & Cleaning**  
   - Read CSV, handle missing values, drop duplicates  
   - Normalize time and date columns, extract year/month/day features  

2. **Exploratory Analysis**  
   - **Overall Trends** — Yearly and monthly crime counts  
   - **Seasonality** — Identify peaks and troughs across months  
   - **Crime Types** — Most common offense categories  
   - **Regional Differences** — Geospatial hotspot mapping  
   - **Weekday Patterns** — Crime distribution by day of week  
   - **Impact of Major Events** — Changes around key dates  
   - **Demographics** — Victim age, sex, descent breakdowns  
   - **Outliers & Anomalies** — Unusual spikes or dips  
   - **Economic Correlation** — Compare crime trends to economic indicators  

3. **Time-Series Forecasting**  
   - Inspect ACF/PACF to select ARIMA order (p=100, d=1, q=0)  
   - Fit ARIMA model and generate a 360-day forecast  
   - Visualize observed vs. forecasted crime counts  


## ⚙️ Requirements

- Python 3.7+
- numpy
- pandas
- matplotlib
- seaborn
- statsmodels

You can install all at once via:
```bash
pip install numpy pandas matplotlib seaborn statsmodels
```


