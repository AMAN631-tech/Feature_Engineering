# Feature_Engineering


##  Topics Covered

### 1. Handling Missing Values
Missing data can reduce the quality of insights. Techniques include:
- **Removing rows/columns** with missing values
- **Imputing values** using mean, median, or mode
- **Using advanced techniques** like KNN or interpolation for imputation

### 2. Handling Outliers
Outliers can skew the results of models and affect accuracy. Common approaches:
- **Statistical methods** (IQR, Z-score)
- **Capping or flooring** extreme values
- **Visualization** using boxplots to detect outliers

### 3. Handling Imbalanced Datasets
Class imbalance can lead to biased models. Techniques include:
- **Resampling methods**: 
  - **Undersampling** the majority class
  - **Oversampling** the minority class
- **SMOTE** (Synthetic Minority Over-sampling Technique)

### 4. Encoding Techniques
Categorical data must be converted to numerical format for modeling. Techniques include:

#### 🔹 One-Hot Encoding (OHE)
- Used for **nominal** (unordered) categories
- Converts each category into a separate binary column

#### 🔹 Label Encoding
- Assigns each category a unique number
- Useful for simple or binary categories
- Not ideal for nominal data due to implied order

#### 🔹 Ordinal Encoding
- Used when categories have a meaningful **order**
- Example: Low < Medium < High

#### 🔹 Target Guided Ordinal Encoding
- Assigns numbers to categories based on the **mean of the target variable**
- Helps improve model performance by capturing relationship with target

---

##  Folder Structure

- `missing_values/` – Handling missing data with examples
- `outliers/` – Detecting and managing outliers
- `imbalanced_data/` – Techniques to deal with class imbalance
- `encoding/` – Various encoding techniques with code and explanation

---

##  Goal

The goal of this work is to build a strong foundation in **data preprocessing**, which helps improve model performance and ensure reliable results.

---

##  Contact

For any questions or collaboration, feel free to reach out!

