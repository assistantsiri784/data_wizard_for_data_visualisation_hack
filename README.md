# data_wizard_for_data_visualisation_hack
# 🌍 Analyzing Global Climate Change Data for Policy Insights

This project provides a *comprehensive computational analysis* of global climate change indicators using Python. The focus is on *CO₂ emissions, average temperature trends, renewable energy adoption, forest cover, and extreme weather events* across multiple countries and decades.

The work also includes *predictive modeling* of temperature trends for specific countries (e.g., UK) and globally, using polynomial regression. The visual insights generated here can help in *policy-making, climate action planning, and awareness building*.

---

## 📂 Dataset Details

* *File:* climate_change_dataset.csv
* *Features include:*

  * Country – Country name
  * Year – Observation year
  * CO2 Emissions (Tons/Capita) – Per capita emissions
  * Avg Temperature (°C) – Annual average surface temperature
  * Renewable Energy (%) – Share of renewable energy in total energy mix
  * Forest Area (%) – Percentage of land covered by forests
  * Extreme Weather Events – Count of recorded extreme events
  * Rainfall (mm) – Annual rainfall
  * Population – Population of the country

---

## 🛠 Tools & Libraries

* *Python 3*
* *Libraries used:*

  * pandas – Data preprocessing & manipulation
  * numpy – Mathematical modeling
  * matplotlib & seaborn – Data visualization
  * scikit-learn (optional) – For predictive modeling (polynomial regression)

---

## 📊 Work Implemented

1. *Data Cleaning & Preprocessing*

   * Handled missing values, data type conversions, and feature engineering (e.g., Decade).

2. *Exploratory Analysis*

   * Global CO₂ emission trends
   * Average temperature anomalies
   * Renewable energy & forest cover analysis
   * Extreme weather events distribution

3. *Country-Specific Analysis*

   * Case study: *USA* and *UK*
   * Top emitters and renewable leaders identified

4. *Correlation Analysis*

   * CO₂ vs Renewable Energy
   * CO₂ vs Forest Area
   * Rainfall vs Extreme Events
   * Population vs CO₂

5. *Predictive Modeling*

   * *UK Avg Temperature Projection* – Polynomial regression (3rd degree)
   * *Global Avg Temperature Projection* – Forecasting global warming trajectory

6. *Visualizations*

   * Line plots, bar charts, scatter plots, histograms
   * Decadal comparisons & predictive trend lines

---

## ▶ Run Instructions

1. *Clone this repository*

   bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   cd <your-repo-name>
   

2. *Open the notebook in Google Colab*

   * Upload climate_change_dataset.csv to your Colab environment.
   * Run the notebook step by step.

3. *Install dependencies (if running locally)*

   bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   

4. *Execute*

   * Run the notebook to generate *all visualizations & predictions*.
   * Results include CO₂ trends, renewable analysis, correlation insights, and predictive graphs.

---

## 📌 References

* [IPCC AR6 Climate Change 2021 Report](https://www.ipcc.ch/report/ar6/wg1/)
* [NASA Earth Data](https://earthdata.nasa.gov/)
* [NOAA Climate Data Online](https://www.ncdc.noaa.gov/cdo-web/)
* [OpenWeatherMap](https://openweathermap.org/) – Weather App Reference
* [AccuWeather](https://www.accuweather.com/) – Weather App Reference
