# 🚢 Titanic Survival Analysis

> *"Women and children first" — but does the data agree?*

An exploratory data analysis project that dives into the legendary Titanic disaster, uncovering the hidden patterns behind who survived and who didn't — powered by a synthetic 5,000-passenger dataset.

---

## 🎯 Project Goal

On the night of **April 14–15, 1912**, the RMS Titanic sank after striking an iceberg. This project recreates that story through data — testing whether **gender**, **class**, **age**, and **family size** truly influenced a passenger's chances of survival.

---

## ⚙️ What This Project Does

🧮 **Builds the dataset** — generates 5,000 realistic passenger records inline (no external file needed), complete with missing values for realism.

📈 **Analyzes survival patterns** — computes a custom survival probability model based on:
- 👩 Gender
- 🎫 Passenger Class
- 👶 Age
- 👨‍👩‍👧‍👦 Family Size (`SibSp` + `Parch`)

🎨 **Visualizes the findings** — four compelling charts:

| # | Chart | Insight |
|---|-------|---------|
| 1 | 🚻 Survival Rate by Gender | Did women really survive more? |
| 2 | 🎟️ Survival Rate by Passenger Class | Did money buy a seat on the lifeboat? |
| 3 | 📊 Age Distribution by Survival Status | Were children prioritized? |
| 4 | 👪 Survival Rate by Family Size | Is there safety (or danger) in numbers? |

---

## 🗂️ Dataset Columns

| Column | Description |
|--------|-------------|
| `PassengerId` | Unique passenger identifier |
| `Survived` | 0 = Did not survive, 1 = Survived |
| `Pclass` | Ticket class (1st, 2nd, 3rd) |
| `Sex` | Passenger gender |
| `Age` | Passenger age (some missing, like real records) |
| `SibSp` | Siblings/spouses aboard |
| `Parch` | Parents/children aboard |
| `FamilySize` | Derived: `SibSp + Parch` |

---

## 🚀 How to Run

```bash
# 1. Install dependencies
pip install numpy pandas matplotlib seaborn

# 2. Launch the notebook
jupyter notebook PR_FINAL_3.ipynb

# 3. Run all cells — charts will appear one by one
```

> 💡 **Tip:** Close each chart window to reveal the next one.

---

## 🛠️ Tech Stack

- 🐍 Python
- 🐼 Pandas & NumPy
- 📈 Matplotlib & Seaborn
- 📓 Jupyter Notebook

---

## 🔍 Key Questions This Analysis Answers

- ❓ Did being female significantly boost survival odds?
- ❓ Did 1st class passengers survive more than 3rd class?
- ❓ Were younger passengers more likely to survive?
- ❓ Did traveling with family help or hurt survival chances?

---

## 🌊 Why This Matters

The Titanic disaster remains one of history's most analyzed tragedies — a powerful reminder of how **social class, gender, and circumstance** shaped fate. This project turns that history into hands-on, visual data storytelling.

---

<p align="center">⚓ Built with curiosity, code, and a respect for history ⚓</p>
