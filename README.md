# Day3_DataScience_Bootcamp

# 🚗 Used Car Price Prediction – Exploratory Data Analysis

## 📌 Project Overview

This project is completed as part of **Epochs '26 – Assignment 3**. The objective is to perform **Exploratory Data Analysis (EDA), Data Cleaning, and Feature Engineering** on the **Used Car Price Prediction Dataset**. These preprocessing steps are essential before developing any machine learning model for predicting used car prices.

---

## 📂 Dataset

**Dataset:** Used Car Price Prediction Dataset

The dataset contains information about used cars, including their specifications, condition, and selling prices.

### Features

* Brand
* Model
* Model Year
* Mileage
* Fuel Type
* Engine
* Transmission
* Exterior Color
* Interior Color
* Accident History
* Clean Title Status
* Price (Target Variable)

---

# 🎯 Objectives

* Explore the dataset and understand its structure.
* Identify numerical and categorical features.
* Perform descriptive statistical analysis.
* Detect missing values and duplicate records.
* Analyze feature distributions.
* Detect and handle outliers.
* Clean the dataset for future machine learning.
* Engineer meaningful features to improve model performance.

---

# 🔍 Exploratory Data Analysis (EDA)

The following analyses were performed:

* Dataset shape and structure
* Data type inspection
* Missing value analysis
* Duplicate record detection
* Statistical summary of numerical features
* Distribution analysis
* Categorical feature analysis
* Outlier detection
* Correlation analysis

---

# ⚠️ Data Quality Issues Identified

The dataset contained several quality issues:

* Missing values in categorical columns such as:

  * `clean_title`
  * `fuel_type`
  * `accident`
* `price` stored as formatted text and converted to numeric values.
* `milage` stored as text and converted to numeric values.
* Inconsistent formatting in some categorical columns.
* No duplicate records were identified.

---

# 🧹 Data Cleaning Techniques Applied

The following preprocessing steps were performed:

* Removed unnecessary symbols from price values.
* Converted mileage into numeric format.
* Converted appropriate columns into correct data types.
* Filled missing categorical values using appropriate techniques.
* Checked and removed duplicate records (if any).
* Identified outliers using statistical methods.
* Prepared the dataset for machine learning.

---

# ⚙️ Feature Engineering

The following engineered features were created:

1. **Vehicle Age**

   * Current Year − Model Year

2. **Mileage per Year**

   * Mileage divided by Vehicle Age

3. **Luxury Brand Indicator**

   * Binary feature identifying premium brands

4. **Accident History Indicator**

   * Encoded accident status into numerical values

5. **Clean Title Indicator**

   * Binary feature indicating clean ownership history

These engineered features can improve predictive performance in future machine learning models.

---

# 📊 Key Insights

1. The dataset contains over **4,000 used car records**, providing a diverse set of vehicles for analysis.

2. Missing values are mainly concentrated in the `clean_title`, `fuel_type`, and `accident` columns.

3. Price and mileage required preprocessing because they were stored as text rather than numeric values.

4. No duplicate records were found, indicating good data consistency.

5. Vehicle age and mileage are expected to be among the strongest factors influencing used car prices.

---

# 📁 Repository Structure

```text
used-car-price-prediction-eda/
│
├── task-3.ipynb
├── cleaned_used_cars.csv
├── README.md
├── requirements.txt
└── images/
    ├── price_distribution.png
    ├── mileage_distribution.png
    ├── brand_distribution.png
    ├── correlation_heatmap.png
    └── boxplots.png
```

---

# 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

# 🚀 How to Run

1. Clone the repository.

```bash
git clone https://github.com/your-username/used-car-price-prediction-eda.git
```

2. Navigate to the project directory.

```bash
cd used-car-price-prediction-eda
```

3. Install dependencies.

```bash
pip install -r requirements.txt
```

4. Open Jupyter Notebook.

```bash
jupyter notebook
```

5. Run `task-3.ipynb` to reproduce the analysis.

---

# 📈 Future Work

* Train regression models for price prediction.
* Compare multiple machine learning algorithms.
* Perform feature selection.
* Hyperparameter tuning.
* Evaluate model performance using RMSE, MAE, and R² score.

---

# 📌 Submission Details

**Assignment:** Epochs '26 – Assignment 3

Deliverables included:

* ✅ Exploratory Data Analysis
* ✅ Data Cleaning
* ✅ Feature Engineering
* ✅ Cleaned Dataset
* ✅ GitHub Repository

---

# 👨‍💻 Author

**ASIF HUSSAIN**

Completed as part of the **Epochs '26 Data Science Track**.

## Key Insights
1. The dataset contains a diverse range of used cars from multiple brands, with popular manufacturers contributing the majority of listings, indicating a varied and competitive used car market.
2. Most vehicles are relatively recent models, with a higher concentration of cars manufactured after 2015, suggesting that newer vehicles dominate the dataset.
3. Mileage has a noticeable impact on price. Cars with higher mileage generally have lower selling prices, indicating a negative relationship between mileage and vehicle value.
4. Luxury brands tend to command higher prices than economy brands, even for used vehicles, highlighting the influence of brand reputation on resale value.
5. Vehicles with a clean accident history and clean title generally have higher prices than those with reported accidents or title issues, showing that vehicle condition significantly affects resale value.

## Files
- task-3.ipynb
- cleaned_used_cars.csv
- README.md
