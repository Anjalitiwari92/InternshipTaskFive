# 🚢 Titanic Dataset - Visual and Statistical Exploration

## 📋 Task Overview

This project focuses on **extracting insights** from the famous Titanic dataset using **Pandas**, **Matplotlib**, and **Seaborn**.  
It covers both **statistical** and **visual** exploration methods to identify relationships, trends, and key survival patterns among passengers.

---

## 📂 Files Included
- `train.csv` — Training data with passenger details and survival outcome.
- `test.csv` — Test data for model evaluation (not explored here).
- `gender_submission.csv` — Sample submission file (not explored here).
- `exploration.ipynb` — Main Jupyter Notebook containing the full exploration and visualization.
- `README.md` — Project documentation (this file).

---

## 🛠 Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn

---

## 🔥 Key Steps Performed

### 1. Statistical Exploration
- `.info()` — Understanding dataset structure and missing values.
- `.describe()` — Summary statistics for numerical features.
- `.value_counts()` — Checking the distribution of the target variable (`Survived`).

### 2. Visual Exploration
- **Histograms**:
  - Age
  - Fare
  - SibSp (Siblings/Spouse Aboard)
  - Parch (Parents/Children Aboard)
- **Boxplots**:
  - Age vs Survival
  - Fare vs Passenger Class
- **Scatterplots**:
  - Fare vs Age colored by Survival
  - SibSp vs Parch colored by Survival
- **Pairplot**:
  - Relationships among multiple features (`Age`, `Fare`, `Pclass`, `Sex`, etc.) with Survival hue.
- **Correlation Heatmap**:
  - Correlation strength between all major numerical variables.

---

## 📈 Key Insights
| Aspect | Insight |
|:-------|:--------|
| Survival vs Gender | **Females** had a much higher survival rate. |
| Survival vs Class | **First-class** passengers survived more than second and third class. |
| Age vs Survival | **Younger passengers** (children, young adults) had better survival rates. |
| Fare vs Survival | **Higher-paying** passengers survived more. |
| Family Size | **Small families** had better survival rates than large ones or single travelers. |

---

## 🚀 How to Run Locally
1. Clone this repository:
   ```bash
   git clone https://github.com/Anjalitiwari92/InternshipTaskFive/titanic-exploration.git
   cd titanic-exploration
   ```

2. Install required packages:
   ```bash
   pip install pandas matplotlib seaborn
   ```

3. Open and run the Jupyter Notebook:
   ```bash
   jupyter notebook exploration.ipynb
   ```

---


# ⚡ Thank you for checking out the project!
