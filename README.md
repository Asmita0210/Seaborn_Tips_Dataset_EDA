# Seaborn Data Analysis & Visualization Assignment

---

## Overview
This repository contains a comprehensive data analysis and visualization notebook utilizing the **Seaborn** and **Pandas** libraries. The notebook explores the classic `tips` dataset, walking through data cleaning, feature engineering, statistical aggregation, advanced multivariate analysis, and automated pipeline execution.

---

## Key Sections & Visualizations Guide

Here is an overview of the core sections covered in the notebook, along with markdown image placeholders showing where to embed your generated visual outputs:

### 1. Data Exploration + Cleaning & Feature Engineering
* **Q1–Q2:** Pandas preprocessing, categorical type casting (`Thur` $\rightarrow$ `Sun`), feature engineering (`tip_percent`), and binning into **Low**, **Medium**, and **High** categories.

---

### 2. Categorical Analysis
* **Q3 (Boxplot Analysis):** Total bill vs. day with `hue='sex'` (examining median and variability).  
<img src="visualisations/Total Bill vs Day by Sex.png" alt="Total Bill vs Day by Sex" width="600"/>

* **Q4 (Outlier Detection):** Statistical IQR method implementation to isolate and print outlier rows.

* **Q5 (Violin Plot Insight):** Total bill vs. day distribution shapes.  
<img src="visualisations/Total Bill Distribution Across Days.png" alt="Total Bill Distribution Across Days" width="600"/>

* **Q6 (Strip + Box Combination):** Layered visualization combining a boxplot and a stripplot with jitter and alpha transparency.  
<img src="visualisations/Boxplot with Layered Stripplot.png" alt="Boxplot with Layered Stripplot" width="600"/>

* **Q7 (Swarmplot Density Study):** Raw data density distribution across days.  
<img src="visualisations/Swarmplot of Total Bill across Days.png" alt="Swarmplot of Total Bill across Days" width="600"/>

---

### 3. Statistical Aggregation
* **Q8 (Barplot with Custom Estimator):** Comparing median vs. mean estimators for total bill by day.  
<img src="visualisations/Boxplot with Layered Stripplot.png" alt="Boxplot with Layered Stripplot" width="600"/>

* **Q9 (Confidence Interval Understanding):** Barplot error bar analysis.  
<img src="visualisations/Barplot without Error Bars.png" alt="Barplot without Error Bars" width="600"/>

* **Q10 (Countplot Business Insight):** Customer traffic frequency across days split by sex.  
<img src="visualisations/Customer Count by Day and Sex.png" alt="Customer Count by Day and Sex" width="600"/>

---

### 4. Interaction Effects
* **Q11–Q12 (Pointplots):** Analyzing interaction effects between time/day and total bill segmented by sex and smoking behavior.  
<img src="visualisations/Day vs Total Bill by Sex.png" alt="Day vs Total Bill by Sex" width="300"/>
<img src="visualisations/Day vs Total Bill by Smoker Status.png" alt="Day vs Total Bill by Smoker Status" width="300"/>

---

### 5. Distribution Analysis
* **Q13–Q17:** Histogram tuning (bins 10 vs 50), KDE plots, skewness checks, ECDF analysis, and real-world probability evaluations.  
<img src="visualisations/Histogram Comparison.png" alt="Histogram Comparison" width="200"/>
<img src="visualisations/Total Bill KDE by Sex.png" alt="Total Bill KDE by Sex" width="200"/>
<img src="visualisations/ECDF of Total Bill.png" alt="ECDF of Total Bill" width="200"/>

---

### 6. Multivariate Analysis & Advanced Catplot
* **Q18–Q20:** 2D histograms, KDE contour plots for density, and faceted `catplot` boxes comparing lunch and dinner.  
<img src="visualisations/2D Histogram of Total Bill vs Tip.png" alt="2D Histogram of Total Bill vs Tip" width="300"/>
<img src="visualisations/Density Contour Plot.png" alt="Density Contour Plot" width="300"/>
<img src="visualisations/Lunch vs Dinner Bill Comparison.png" alt="Lunch vs Dinner Bill Comparison" width="600"/>

---

### 7. Business Problem & Full EDA Pipeline
* **Q21 (Business Problem):** Strategic business optimization using supporting plots to maximize restaurant revenue.  
 <img src="visualisations/Revenue Data.png" alt="Revenue  Data" width="600"/>

* **Q22 (Bonus Coding Challenge):** Modularized EDA pipeline function (`analyze_dataset(df)`) combining cleaning, feature engineering, and automated plotting.

---

## Getting Started

1. **Clone this repository:**
   ```bash
   git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
   cd your-repo-name
