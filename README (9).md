<div align="center">

# 🦠 COVID-19 Global Data Analysis

### *Turning raw pandemic numbers into clear, visual stories.*

![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Wrangling-150458?logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Plotting-11557C)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-4C72B0)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-Educational%20Use-yellow)

</div>

---

## 📖 Overview

This project takes a real-world **COVID-19 dataset** and transforms it into meaningful, easy-to-read insights. It walks through the full mini data-science pipeline — **loading, cleaning, aggregating, and visualizing** — to answer one simple question:

> *Which countries were hit hardest by confirmed COVID-19 cases?*

The result is a clean, color-coded bar chart highlighting the **Top 10 most affected countries**, built with just a few lines of well-structured Python.

---

## ✨ Key Features

| 🔧 Feature | 📋 Description |
|---|---|
| 🧹 **Data Cleaning** | Converts raw date strings into proper datetime format and fills missing `State_Province` values |
| 📅 **Chronological Sorting** | Arranges all records by date for consistency |
| 📊 **Smart Aggregation** | Calculates the maximum confirmed cases per country |
| 🏆 **Top 10 Ranking** | Identifies and ranks the ten hardest-hit countries |
| 🎨 **Beautiful Visualization** | Renders a polished horizontal bar chart using Seaborn's `viridis` palette |

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| 🐍 **Python** | Core programming language |
| 🐼 **Pandas** | Data loading, cleaning & aggregation |
| 🔢 **NumPy** | Numerical operations |
| 📈 **Matplotlib** | Base plotting engine |
| 🌊 **Seaborn** | Statistical, aesthetically pleasing visualizations |

---

## 📂 Project Structure

```
📦 COVID-19-Data-Analysis
 ┣ 📓 PR_FINAL_1.ipynb     → Main Jupyter Notebook
 ┣ 📊 covid_data.csv        → Dataset (must sit in the same folder)
 ┗ 📄 README.md             → You are here!
```

---

## ⚙️ How It Works

```mermaid
graph LR
A[📥 Load Dataset] --> B[🧹 Clean & Prepare Data]
B --> C[📊 Aggregate by Country]
C --> D[🏆 Rank Top 10 Countries]
D --> E[🎨 Visualize with Seaborn]
```

1. **Import Libraries** — `os`, `pandas`, `numpy`, `matplotlib`, `seaborn`
2. **Load the Dataset** — reads `covid_data.csv` from the current working directory
3. **Clean the Data** — parses dates, sorts chronologically, fills missing values
4. **Aggregate** — computes peak confirmed cases per country
5. **Visualize** — plots a horizontal bar chart of the Top 10 countries 📈

---

## 🚀 Getting Started

### 1. Install dependencies
```bash
pip install pandas numpy matplotlib seaborn
```

### 2. Run the notebook
```bash
jupyter notebook PR_FINAL_1.ipynb
```

> ⚠️ **Important:** Make sure `covid_data.csv` is placed in the **same directory** as the notebook, otherwise you'll hit a `FileNotFoundError`.

---

## 📈 Sample Output

```
✅ Data successfully loaded and cleaned!
Total Records: XXXX | Total Columns: XX

📊 Generating Bar Chart for Top 10 COVID-19 Confirmed Cases...
```

Followed by a clean, professionally styled **horizontal bar chart** ranking the Top 10 countries by confirmed cases.

---

## 🌱 Future Enhancements

- [ ] 📉 Time-series trend analysis (daily / monthly growth)
- [ ] 🖥️ Interactive dashboard using Plotly or Streamlit
- [ ] ⚰️ Recovery vs. death rate comparison
- [ ] 🗺️ Country-wise heatmap on a world map

---

## 🙌 Author

Built with ❤️, curiosity, and a healthy amount of `pandas.groupby()`.

---

## 📜 License

This project is shared for **learning and educational purposes**. Feel free to fork it, explore it, and build something even bigger on top of it! 🚀

