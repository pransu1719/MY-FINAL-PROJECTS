# 😊 Global Happiness Insights

> *What really makes a country happy? Let the data speak.*

A lightweight Python analysis pipeline that explores the drivers of happiness across nations — GDP, social support, health, freedom, generosity, and trust — using a synthetic-but-realistic dataset of **5,000 records**.

---

## ✨ What This Project Does

🔍 **Auto-generates data** — if `global_happiness_report_5000.csv` doesn't exist, the script creates it on the fly (seeded for reproducibility).

📊 **Summarizes the numbers** — prints mean, std, min, and max for every metric in a clean table.

🎨 **Visualizes the story** — three eye-catching charts:

| # | Chart | What It Shows |
|---|-------|----------------|
| 1 | 🔥 Correlation Heatmap | Which factors move together with happiness |
| 2 | 💰 GDP vs Happiness | Does money really buy joy? |
| 3 | 🤝 Social Support vs Happiness | The power of human connection |

---

## 🗂️ Dataset Columns

| Column | Description |
|--------|-------------|
| `Country` | Nation surveyed |
| `Region` | Geographic region |
| `Year` | Survey year (2015–2026) |
| `Happiness Score` | Overall happiness rating |
| `GDP per Capita` | Economic contribution |
| `Social Support` | Community & relationship strength |
| `Healthy Life Expectancy` | Health contribution |
| `Freedom to Make Choices` | Personal liberty score |
| `Generosity` | Charitable spirit |
| `Perceptions of Corruption` | Trust in institutions |

---

## 🚀 How to Run

```bash
# 1. Install dependencies
pip install numpy pandas matplotlib seaborn

# 2. Launch the notebook
jupyter notebook PR_FINAL_2.ipynb

# 3. Run all cells — charts will pop up one by one
```

> 💡 **Tip:** Close each chart window to move on to the next one.

---

## 🛠️ Tech Stack

- 🐍 Python
- 🐼 Pandas & NumPy
- 📈 Matplotlib & Seaborn
- 📓 Jupyter Notebook

---

## 📌 Sample Output

```
============================================================
 DATASET SUMMARY STATS
============================================================
                              mean    std   min    max
Happiness Score               ...    ...   ...    ...
GDP per Capita                ...    ...   ...    ...
...
============================================================
```

---

## 🌍 Why This Matters

Happiness isn't just a feeling — it's measurable, comparable, and (partly) predictable. This project is a small step toward understanding **what truly drives well-being** across the globe.

---

<p align="center">Made with ❤️, curiosity, and a bit of Python magic ✨</p>
