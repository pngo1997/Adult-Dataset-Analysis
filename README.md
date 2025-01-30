# 🏗️ Adult Dataset Analysis  

## 📜 Overview  
This project explores the **UCI Adult dataset**, analyzing demographic and work-related factors to understand income distribution. The analysis includes **data visualization, transformation, correlation analysis, and normalization** to prepare the dataset for machine learning applications.  

## 🎯 Problem Explanation  
The dataset consists of **demographic attributes** (e.g., age, education, marital status, race) and **work-related factors** (e.g., hours-per-week, occupation, capital gain/loss). The target variable is **income**, categorized as `<=50K` or `>50K`. The key tasks include:  

1. **Exploratory Data Analysis (EDA)**  
   - Compute **summary statistics** (mean, standard deviation, frequencies).  
   - Visualize distributions using **box plots, histograms, and scatter plots**.  

2. **Categorical Data Visualization**  
   - Create **bar charts** for categorical attributes (e.g., marital status, employment type).  

3. **Cross-Tabulation Analysis**  
   - Analyze relationships between **sex & income** and **race & income**.  
   - Display results using **bar charts** and **percentage comparisons**.  

4. **Comparing Low vs. High-Income Groups**  
   - Compute summary statistics for both groups.  
   - Identify distinguishing characteristics.  
   - Use **charts** to visualize differences.  

5. **Data Transformation**  
   - Convert categorical attributes into **dummy variables**.  
   - Save transformed data as `adult_numeric.csv`.  

6. **Correlation Analysis**  
   - Compute a **correlation matrix** among attributes.  
   - Display **top correlations with education and income**.  
   - Identify another correlation method available in Pandas.  

7. **Discretization & Normalization**  
   - **Discretize age** into `young`, `mid-age`, and `old` categories.  
   - **Min-Max Normalize** `hours-per-week` to a `[0,1]` range.  
   - **Standardize** numerical attributes using **Z-score normalization**.  
   - Implement normalization **without using external libraries** (e.g., Scikit-learn).  

8. **Handling Missing Values**  
   - Identify attributes with missing values.  
   - Fill missing values for numeric attributes using **mean imputation**.  
   - Remove rows where categorical attributes contain missing values.  
   - Verify that the final dataset has **no missing values**.  

## 🛠️ Implementation Details  
- Used **Pandas** for data manipulation and analysis.  
- Employed **Matplotlib & Seaborn** for visualization.  
- Implemented **custom normalization functions** instead of built-in scalers.  

## 🚀 Technologies Used  
- **Python** (for data preprocessing and visualization).  
- **Pandas & NumPy** (for data analysis and transformation).  
- **Matplotlib & Seaborn** (for creating visualizations).  
