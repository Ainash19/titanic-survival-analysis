# titanic-survival-analysis
Statistical analysis of Titanic passenger age and survival rates

# 🚢 Titanic Survival Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-blue?logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-blue?logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Data%20Visualization-orange?logo=python&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-Statistics-purple?logo=scipy&logoColor=white)
![Statistics](https://img.shields.io/badge/Statistics-Hypothesis%20Testing-green)
![License](https://img.shields.io/badge/License-Educational-lightgrey)

## 📊 Project Overview

This project investigates whether **age** significantly influenced the survival of passengers aboard the RMS Titanic. Using descriptive statistics, histograms, and hypothesis testing, the average ages of survivors and non-survivors are compared to determine whether age was a determining factor in survival outcomes.

**Course:** MATH 1202 – Statistics
**Institution:** Fanshawe College

---

## 🔍 Research Question

> **Do survivors and non-survivors of the Titanic differ in their average age?**

---

## 📁 Data Source

* **Dataset:** Titanic Passenger Dataset
* **Source:** Kaggle Titanic Dataset
* **Original Data:** Historical passenger records, ship manifests, and survivor lists from the 1912 Titanic disaster
* **Variables Used:** Age and Survived
* **Sample Size:** 332 passengers after removing missing age values

---

## 🛠️ Tools & Technologies

* Python 3
* Pandas
* NumPy
* Matplotlib
* SciPy
* Jupyter Notebook

---

## 📈 Key Findings

### Descriptive Statistics

| Metric                    | Survivors | Non-Survivors |
| ------------------------- | --------: | ------------: |
| Sample Size               |       127 |           205 |
| Mean Age                  |     30.27 |         30.27 |
| Median Age                |      27.0 |          27.0 |
| Standard Deviation        |     15.37 |         13.36 |
| Interquartile Range (IQR) |      18.0 |          18.0 |

### Hypothesis Testing

**Null Hypothesis (H₀):** Mean age of survivors = Mean age of non-survivors

**Alternative Hypothesis (Hₐ):** Mean age of survivors ≠ Mean age of non-survivors

| Test Statistic |    Value |
| -------------- | -------: |
| T-statistic    | -0.00023 |
| P-value        |   0.9998 |
| α              |     0.05 |

**Conclusion:** Fail to reject H₀.

---

## ✅ Conclusion

Age was **not** the primary determinant of survival on the Titanic. Statistical analysis revealed no significant difference between the average ages of survivors and non-survivors.

Although children often had higher survival rates due to evacuation procedures such as **"women and children first,"** factors such as gender and passenger class likely played a more important role in determining survival outcomes.

---

## 📂 Project Structure

```text
Titanic-Analysis/
│
├── Titanic.ipynb         # Jupyter Notebook containing analysis
├── data/
│   └── titanic.csv       # Dataset
├── README.md             # Project documentation
├── requirements.txt      # Project dependencies
└── .gitignore            # Ignored files
```

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/Ainash19/titanic-survival-analysis.git
cd titanic-survival-analysis
```

### 2. Create a virtual environment 

```bash
python -m venv venv
```

Activate:

Windows:

```bash
venv\Scripts\activate
```

Mac/Linux:

```bash
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install pandas numpy matplotlib scipy notebook
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Run the analysis

Open `Titanic.ipynb` and select **Run All**.

---

## 📊 Visualizations

The project includes two histograms:

* Histogram 1: Age distribution of survivors.
* Histogram 2: Age distribution of non-survivors.

Both distributions appear very similar, supporting the results of the t-test.

---

## 📝 Methodology

1. Data cleaning with `dropna()`.
2. Separation into survivor and non-survivor groups.
3. Computation of descriptive statistics.
4. Construction of histograms using Matplotlib.
5. Independent two-sample t-test using SciPy.

---

## 📚 References

* Kaggle Titanic Dataset
* Historical records from the RMS Titanic disaster (1912)

---

## 👤 Author

**Ainash Zhumagulova**
Computer Programming and Analysis Student
Fanshawe College

---

## 📄 License

This project is intended for educational purposes.

---

### 🔖 Tags

`Python` • `Statistics` • `Data Science` • `Hypothesis Testing` • `T-Test` • `Matplotlib` • `Jupyter Notebook`

**Last Updated:** June 2026
