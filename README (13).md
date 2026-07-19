# 📈 Stock Market Analysis & Visualization

> *"The stock market is a device for transferring money from the impatient to the patient."*
> — A project that turns raw price data into a story worth reading.

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Wrangling-150458?logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557C)
![Seaborn](https://img.shields.io/badge/Seaborn-Styling-4c72b0)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## 🧭 About This Project

Ever wondered how analysts spot trends before the crowd does? This project simulates a **60-day stock price journey** and puts it under the microscope — tracking momentum with moving averages and reading the market's mood through trading volume.

No live APIs, no internet dependency, no setup headaches. Just clean, reproducible data and two charts that tell the whole story at a glance.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🎲 **Synthetic Data Generator** | Creates realistic daily closing prices using a random walk model (seeded for reproducibility) |
| 📊 **Moving Averages** | Calculates 5-day and 10-day rolling averages to smooth out noise and reveal trend direction |
| 🕯️ **Price Trend Chart** | Visualizes closing price alongside both moving averages for quick trend-spotting |
| 🟢🔴 **Volume Bar Chart** | Color-coded bars (green = price up, red = price down) show buying vs. selling pressure |
| 🎨 **Clean Aesthetic** | Styled with Seaborn's `whitegrid` theme for a polished, presentation-ready look |

---

## 🛠️ Tech Stack

- **Python 3**
- **Pandas** — data wrangling & rolling calculations
- **NumPy** — random data generation
- **Matplotlib** — plotting engine
- **Seaborn** — visual styling

---

## 🚀 Getting Started

### 1. Clone or download this project
```bash
git clone <your-repo-url>
cd stock-market-analysis
```

### 2. Install dependencies
```bash
pip install pandas numpy matplotlib seaborn
```

### 3. Run the notebook
Open `PR_FINAL_5.ipynb` in Jupyter Notebook / JupyterLab / VS Code and run all cells.

```bash
jupyter notebook PR_FINAL_5.ipynb
```

---

## 📐 How It Works

1. **Data Creation** — 60 days of dummy stock data are generated starting `2024-01-01`, with prices evolving through a random walk (`np.random.normal`) and volumes randomized between 5M–15M shares.
2. **Trend Smoothing** — Rolling windows of 5 and 10 days are applied to the closing price to calculate moving averages.
3. **Visualization** — Two stacked subplots are rendered:
   - **Top:** Price line + both moving averages
   - **Bottom:** Volume bars colored by daily price direction

---

## 📊 Sample Output

```
Date        Close     MA(5)     MA(10)    Volume
2024-01-01  150.50      —          —      8,432,109
2024-01-02  152.30      —          —      6,120,554
...
```

*(Actual values will vary slightly with each run due to the random seed logic — but the seed ensures your results stay reproducible.)*

---

## 📁 Project Structure

```
📦 stock-market-analysis
 ┣ 📜 PR_FINAL_5.ipynb     → Main analysis notebook
 ┗ 📜 README.md            → You are here
```

---

## 💡 Possible Future Enhancements

- 🔌 Connect to a real-time stock API (e.g., Alpha Vantage, yFinance)
- 📉 Add RSI / MACD indicators for deeper technical analysis
- 🖥️ Build an interactive dashboard using Streamlit or Plotly Dash
- 🧠 Layer in a simple ML model to predict next-day price direction

---

## 🤝 Contributing

Suggestions and improvements are always welcome — feel free to fork this project and submit a pull request!

---

## 📄 License

This project is open-sourced for learning and demonstration purposes. Feel free to use and adapt it.

---

<p align="center">Made with ☕, curiosity, and a healthy respect for market volatility.</p>
