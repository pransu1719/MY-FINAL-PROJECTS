# 🌫️ Air Quality Analysis

> *Every breath tells a story — let's read it in the data.*

An exploratory analysis of air pollution across 10 major Indian cities, tracking how pollutants, seasons, and weather conditions shape the air we breathe every day.

---

## 🎯 Project Goal

Air pollution is one of the biggest public health challenges facing Indian cities today. This project analyzes **5,000 air quality records** to uncover patterns in pollutant levels, seasonal spikes, and city-wise pollution trends — turning raw sensor data into actionable insight.

---

## 🗂️ Dataset Overview

| Column | Description |
|--------|-------------|
| `Record_ID` | Unique record identifier |
| `Date` | Date of measurement |
| `City` | City where reading was recorded |
| `PM2.5` | Fine particulate matter (µg/m³) |
| `PM10` | Coarse particulate matter (µg/m³) |
| `NO2` | Nitrogen dioxide level |
| `SO2` | Sulfur dioxide level |
| `CO` | Carbon monoxide level |
| `O3` | Ground-level ozone |
| `AQI` | Air Quality Index score |
| `AQI_Category` | Good / Satisfactory / Moderate / Poor / Very Poor / Severe |
| `Temperature_C` | Temperature (°C) |
| `Humidity_%` | Relative humidity |
| `Wind_Speed_kmph` | Wind speed (km/h) |

🏙️ **Cities covered:** Delhi, Mumbai, Ahmedabad, Bengaluru, Chennai, Kolkata, Hyderabad, Pune, Jaipur, Lucknow

---

## 📊 Suggested Analyses & Visualizations

| # | Analysis | Insight |
|---|----------|---------|
| 1 | 🏆 City-wise Average AQI | Which city breathes easiest? |
| 2 | 🍂 Seasonal Pollution Trends | Why does winter smog spike so much? |
| 3 | 🌡️ Temperature vs Pollutant Levels | Does heat trap or disperse pollution? |
| 4 | 💨 Wind Speed vs AQI | Can wind clear the air? |
| 5 | 🚦 AQI Category Distribution | How often is the air "Severe" vs "Good"? |
| 6 | 🔥 Pollutant Correlation Heatmap | Which pollutants rise and fall together? |

---

## 🚀 How to Run

```bash
# 1. Install dependencies
pip install numpy pandas matplotlib seaborn

# 2. Launch the notebook
jupyter notebook PR_FINAL_4.ipynb

# 3. Load the dataset and run all cells
```

```python
import pandas as pd
df = pd.read_csv("air_quality_analysis_5000.csv")
df.head()
```

---

## 🛠️ Tech Stack

- 🐍 Python
- 🐼 Pandas & NumPy
- 📈 Matplotlib & Seaborn
- 📓 Jupyter Notebook

---

## 🔍 Key Questions This Analysis Can Answer

- ❓ Which city has the worst average air quality?
- ❓ Does AQI spike in winter months due to smog and inversion?
- ❓ Is there a strong link between PM2.5 and PM10 levels?
- ❓ How does wind speed affect pollutant concentration?
- ❓ Which pollutant contributes most to poor AQI days?

---

## 🌍 Why This Matters

Clean air is a basic right — yet millions across Indian cities live with hazardous AQI levels every winter. This project transforms environmental data into a story that can inform **policy, awareness, and everyday decisions** like when it's safe to step outside.

---

<p align="center">🌱 Built with data, curiosity, and a hope for cleaner skies 🌱</p>
