# Data Analysis on Houses - Summary and Highlights

This project involves analyzing a housing dataset to derive statistical insights and understand relationships among various features.

## **Highlights**

### **1. Data Processing**
- **Handling Null Values**: High null-value columns like `MiscFeature` (96.3%), `PoolQC` (99.52%), and others were removed as they offered limited analytical value.
- **Normality Checks**: 
  - **Shapiro-Wilk Test**: Used to assess normality; features like `LotArea` deviated significantly from a Gaussian distribution.
  - **Anderson-Darling Test**: Confirmed non-normality in features such as `OverallQual`.
  - **Visualization**: Histograms and other plots verified the results visually.

---

### **2. Correlation Analysis**
- **Heatmap**: A visual representation of correlations among numerical features, highlighting the strength of relationships.
- **Pearson Test**: Revealed weak correlations between `MSSubClass` and `SalePrice`, as well as between `LotArea` and `SalePrice`.

---

### **3. Statistical Tests**
- **ANOVA Test**: 
  - Neighborhood significantly impacts sale prices.
  - Sale conditions show a strong correlation with sale prices.
- **T-Test**: Demonstrated a significant relationship between `SalePrice` and `2ndFlrSF`.

---


