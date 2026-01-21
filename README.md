# Diamond Price Estimation Project

**Authors:** Francesca Logiacco and Hilal Işık  
*This project is created and shared by the mentioned authors, with each joint author enjoying an equal interest in the undivided whole.*

---

## Project Overview

This project aims to **analyze and predict diamond prices** using linear regression, based on a dataset scraped from the **Australian Diamond Importers website** on **24th February 2022**.  

The dataset includes features such as:
- Shape, Carat, Colour, Cut, Clarity
- Fluorescence, Symmetry, Polish, Girdle size, Culet size
- Depth, Table, Length, Width, Size, and other attributes  
- Price in AUD (excluding GST)

The goal was to combine **data exploration, cleaning, feature engineering, modeling, and visualization** to create a predictive model for diamond pricing.

---

## Dataset Summary

- **Rows:** 219,704  
- **Columns:** 27 (float64: 6, int64: 2, object: 19)  
- **File size:** 26.6 MB  
- **Price:** 200 AUD (min) – 1,449,881 AUD (max)  
- **Carat:** 0.80 – 19.35  
- **Depth %:** 0 – 98.7  
- **Table %:** 0 – 94  

**Categorical feature examples:**

| Feature | Values / Description |
|---------|--------------------|
| Cut | Fair, Good, Very Good, Excellent, Ideal |
| Color | M (worst) → D (best) |
| Clarity | I3 (worst) → IF (best) |
| Fluorescence | None, Faint, Very Slight, Slight, Medium, Strong, Very Strong |
| Symmetry / Polish | Poor → Excellent |
| Girdle Min / Max | XTN → XTK (Extremely Thin → Extremely Thick) |
| Culet Size | N (Nano), VS, S, M, SL, L, VL, EL (Extremely Large) |

---

## Project Goals

1. **Explore and clean the diamonds dataset**  
2. **Linear Regression modeling** to predict diamond prices  
3. **Feature engineering** including handling categorical and numerical variables  
4. **Data visualization** for insights and patterns  
5. Transfer and visualize the processed data in **Tableau**  

---

## Analysis Steps

### **Data Exploration and Cleaning**
- Reading the dataset and checking basic info  
- Standardizing column names and dropping irrelevant columns  
- Handling missing values and dropping columns with >70% nulls  
- Removing duplicates and outliers  
- Splitting numerical vs categorical features  
- Plotting histograms, boxplots, and correlation heatmaps  

### **Feature Engineering**
- Creating dummy variables for categorical columns  
- Splitting dataset into training and testing sets  
- Standardizing numerical features  
- Concatenating numerical and categorical data for modeling  

### **Modeling**
- Building **Linear Regression models** using:
  - `statsmodels`
  - `scikit-learn`  
- Generating scatter plots and **Seaborn residual plots**  
- Calculating **Mean Squared Error**, **Model Evaluation**, and **Feature Importance**

### **Visualization**
- Transferring cleaned and modeled data to **Tableau** for interactive visual analysis  

---

## Tools and Libraries
- Python: `pandas`, `numpy`, `scipy`, `statsmodels`, `sklearn`, `matplotlib`, `seaborn`  
- Tableau for visualization  

---

## Deliverables
- **Cleaned and processed dataset**  
- **Linear regression model** predicting diamond prices  
- **Visualizations** (scatterplots, residual plots, feature importance, Tableau dashboards)  
- **Insights** on key drivers of diamond pricing  


---

## License / Credit
**Francesca Logiacco and Hilal Işık**  
All authors share **equal interest in the undivided whole**.  

> Data scraped from the **Australian Diamond Importers website**, 24th Feb 2022.
