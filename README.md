# Exploratory Data Analysis (EDA) and Visualization for Breast Cancer Dataset

**Author**: Kiran Kumar D S  

**Project Type**: Exploratory Data Analysis (EDA)

---

## Overview

This project provides an in-depth exploratory data analysis (EDA) and visualization of the **Breast Cancer Dataset**. The dataset comprises several biological features that describe cell nuclei present in images. The goal is to gain insights into these features to understand their role in determining whether a tumor is benign or malignant. This project is part of my portfolio to showcase my skills in **Python**, **Pandas**, **Matplotlib**, and **Seaborn** for EDA.

---

## Table of Contents

1. [Dataset Overview](#dataset-overview)
2. [Key Findings](#key-findings)
3. [Data Cleaning and Preprocessing](#data-cleaning-and-preprocessing)
4. [Exploratory Data Analysis](#exploratory-data-analysis)
5. [Visualizations](#visualizations)
6. [Tools Used](#tools-used)
7. [Conclusion](#conclusion)

---

## Dataset Overview

The dataset consists of **569 rows** and **32 columns**, each describing various characteristics of cell nuclei. Some key features include:

- **Radius_mean**: Mean radius of the cell nuclei.
- **Texture_mean**: Standard deviation of grayscale values in the image.
- **Perimeter_mean**: Mean perimeter of the cell nuclei.
- **Area_mean**: Mean area of the cell nuclei.
- **Smoothness_mean**: Mean local variation in the radius lengths.
- **Compactness_mean**: Compactness of the cell nuclei.
- **Concavity_mean**: Severity of concave portions of the contour.
- **Symmetry_mean**: Symmetry of the nuclei.
- **Fractal_dimension_mean**: A ratio to quantify the complexity of the contour.

---

## Key Findings

From the exploratory analysis, several important insights were uncovered:

- **Insight 1**: A strong correlation exists between **radius_mean** and **perimeter_mean**, indicating that larger cell nuclei generally have more extensive boundaries.
- **Insight 2**: Malignant tumors exhibit higher **concavity_mean** and **compactness_mean**, reflecting more irregular and aggressive cell shapes.
- **Insight 3**: **Fractal_dimension_mean** shows minimal variation between benign and malignant tumors, suggesting it may not be a decisive differentiator by itself.

These insights offer a foundation for further research, including predictive modeling to enhance breast cancer diagnosis accuracy.

---

## Data Cleaning and Preprocessing

The data cleaning process involved:

- **Handling Missing Values**: No missing values were present in the dataset.
- **Outlier Detection**: Outliers were visually inspected via box plots.
- **Feature Engineering**: Unwanted columns (like `Unnamed: 32`) were dropped to optimize analysis.

---

## Exploratory Data Analysis

### Summary Statistics

Key summary statistics for some features:

- **Radius_mean**: Mean = 14.13, Std = 3.52
- **Perimeter_mean**: Mean = 91.97, Std = 24.30
- **Area_mean**: Mean = 654.89, Std = 351.91

### Correlation Analysis

A correlation heatmap was generated, and it revealed that **mean radius**, **mean perimeter**, and **mean area** have strong positive correlations, suggesting that larger cells generally have more extensive and irregular shapes.

---

## Visualizations

Several visualizations were created to aid in the analysis, including:

1. **Correlation Heatmap**: Highlights the relationships between various features.  
   ![Correlation Heatmap](![Corr Heat Map](https://github.com/user-attachments/assets/71786b34-1692-4c43-b837-ed9cc89a6211)

2. **Box Plot of Radius_mean**: Shows the distribution of cell radii across the dataset.
   ![Box Plot](![box plot](https://github.com/user-attachments/assets/372c0f5b-ccc2-4a74-84cc-800ac940568f)


---

## Tools Used

This analysis was conducted using the following tools:

- **Python**: Core programming language used for analysis.
- **Pandas**: For data manipulation and wrangling.
- **Matplotlib** & **Seaborn**: For data visualization.
- **Jupyter Notebook**: As the development environment.

---

## Conclusion

This exploratory analysis helped identify significant relationships between cell characteristics and tumor malignancy. The data cleaning process ensured that the dataset was ready for further analysis, and the visualizations revealed important patterns in the data. Future steps might include building predictive models to classify tumors based on these features.

For further insights and to explore the code, visit the Jupyter notebook included in this repository. Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/kirands) or visit my [website](https://www.k21projects.in) for more projects and insights.

---

**Next Steps**:

- Apply machine learning models to predict malignancy.
- Investigate additional features or techniques for better diagnostic accuracy.

