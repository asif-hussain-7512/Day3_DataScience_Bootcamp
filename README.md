# 🚗 Day 3 – Data Science Bootcamp: Used Cars Data Cleaning & Exploratory Data Analysis

## 📌 Overview

This project is part of the **Data Science Bootcamp – Day 3** assignment. The objective is to clean a real-world used cars dataset, perform exploratory data analysis (EDA), engineer useful features, and prepare the dataset for future machine learning tasks.

The notebook demonstrates a complete data preprocessing workflow, including handling missing values, removing duplicates, feature engineering, visualization, and exporting the cleaned dataset.

---

## 📂 Repository Structure

```
Day3_DataScience_Bootcamp/
│
├── task_3.ipynb              # Main Jupyter Notebook
├── used_cars.csv             # Original dataset
├── cleaned_used_cars.csv     # Cleaned dataset
├── README.md                 # Project documentation
```

---

## 🎯 Objectives

- Load and inspect the dataset
- Handle missing values
- Remove duplicate records
- Perform exploratory data analysis (EDA)
- Engineer meaningful features
- Visualize important trends
- Export the cleaned dataset

---

## 📊 Dataset Information

The dataset contains information about used cars, including:

- Brand
- Model
- Model Year
- Price
- Mileage
- Fuel Type
- Transmission
- Engine
- Accident History
- Clean Title Status
- Other vehicle specifications

---

## 🛠️ Data Preprocessing

The following preprocessing steps were performed:

### ✅ Missing Value Treatment

- Filled missing categorical values using the mode or appropriate labels.
- Missing values in accident history were replaced with **"Unknown"** where necessary.

### ✅ Duplicate Removal

- Checked for duplicate records.
- Removed duplicate entries to improve data quality.

### ✅ Data Type Verification

- Verified column data types.
- Ensured numerical columns were correctly interpreted.

---

## ⚙️ Feature Engineering

Several new features were created to improve the usefulness of the dataset.

### Vehicle Age

Calculated using:

```
Vehicle Age = Current Year − Model Year
```

### Mileage Per Year

```
Mileage Per Year = Mileage / Vehicle Age
```

### Luxury Car Indicator

Created a binary feature identifying luxury brands such as:

- BMW
- Mercedes-Benz
- Audi
- Lexus
- Jaguar
- Porsche

### Accident Indicator

Converted accident history into a binary feature:

- 1 = Accident Reported
- 0 = No Accident

### Clean Title Indicator

Converted clean title information into:

- 1 = Clean Title
- 0 = Not Clean Title

---

## 📈 Exploratory Data Analysis (EDA)

The notebook includes multiple visualizations to understand the dataset.

### Distribution of Car Prices

- Histogram
- Density distribution

### Vehicle Mileage Distribution

- Histogram
- Distribution curve

### Vehicle Age Distribution

Shows how old the listed vehicles are.

### Top Car Brands

Bar chart displaying the most common manufacturers.

### Fuel Type Distribution

Visual comparison of different fuel categories.

### Transmission Distribution

Shows the frequency of Automatic and Manual vehicles.

### Price vs Vehicle Age

Scatter plot showing how age affects selling price.

### Mileage vs Price

Scatter plot illustrating the relationship between mileage and price.

### Boxplots

Used to identify potential outliers in:

- Price
- Mileage

---

## 🔍 Key Insights

- The dataset contains vehicles from multiple manufacturers across different model years.
- Vehicle prices vary significantly depending on brand and age.
- Most vehicles have moderate mileage.
- Luxury brands generally command higher prices.
- Older vehicles typically have lower market value.
- Mileage and vehicle age show a noticeable relationship with selling price.
- Feature engineering makes the dataset more suitable for predictive modelling.

---

## 📁 Output

The cleaned dataset is exported as:

```
cleaned_used_cars.csv
```

This dataset is ready for further analysis or machine learning applications.

---

## 💻 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📚 Python Libraries

```python
pandas
numpy
matplotlib
seaborn
```

Install using:

```bash
pip install pandas numpy matplotlib seaborn
```

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/asif-hussain-7512/Day3_DataScience_Bootcamp.git
```

2. Navigate to the project folder

```bash
cd Day3_DataScience_Bootcamp
```

3. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn
```

4. Launch Jupyter Notebook

```bash
jupyter notebook
```

5. Open

```
task_3.ipynb
```

and execute all cells.

---

## 📸 Sample Visualizations

The notebook contains visualizations including:

- Price Distribution
- Mileage Distribution
- Vehicle Age Distribution
- Top Brands
- Fuel Type Distribution
- Transmission Distribution
- Scatter Plots
- Boxplots

---

## 🎓 Learning Outcomes

Through this project, I learned how to:

- Clean real-world datasets
- Handle missing values effectively
- Perform exploratory data analysis
- Engineer useful features
- Visualize relationships between variables
- Prepare datasets for machine learning workflows

---

## 👨‍💻 Author

**Asif Hussain**

📧 Email: asifhussain@mulearn

GitHub:
https://github.com/asif-hussain-7512

---

## ⭐ Acknowledgement

This project was completed as part of the **Epochs '26 Data Science Bootcamp – Day 3 Assignment** under **μLearn**.

Special thanks to the mentors and organizers for providing the dataset and learning resources.

---

## 📜 License

This project is intended for educational purposes only.
