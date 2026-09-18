# Student Performance Analysis

## Project Overview

This project analyzes student performance using academic, family, social, and lifestyle-related factors. The analysis uses Python, Pandas, Matplotlib, and Seaborn to explore patterns and relationships in students' final grades.

## Project Purpose

The purpose of this project is to analyze student performance and identify the factors that may be related to students' final grades. The project uses data analysis, visualization, and correlation analysis to explore academic, family, social, and lifestyle factors that are associated with student performance.

## Dataset

The dataset contains information about **395 students** and **33 features**.

The features include:

* Student demographics
* Family background
* Parents' education and occupations
* Study time
* Previous failures
* Absences
* Social activities
* Lifestyle factors
* Previous grades (G1 and G2)
* Final grade (G3)

The target variable used for performance analysis is **G3**, the student's final grade.

## Tools & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## Data Cleaning & Validation

The dataset was checked for:

* Missing values
* Duplicate rows
* Categorical value consistency
* Numeric value ranges
* Dataset structure and data types

The dataset contained **no missing values** and **no duplicate rows**.

## Exploratory Data Analysis

The project explores the relationship between final grades and several factors, including:

* Study time
* Previous failures
* Absences
* Mother's education
* Father's education
* Mother's occupation
* Father's occupation
* Free time
* Going out
* Health
* Parents' status
* School
* Gender

Different visualizations, mainly bar charts and scatter plots, were used to understand these relationships.

## Correlation Analysis

A correlation matrix and heatmap were created for the numerical variables to identify relationships between different features and the final grade.

### Key Insights

1. G2 has the strongest positive correlation with G3 (0.905).
2. G1 also has a strong positive correlation with G3 (0.801).
3. Previous failures have a moderate negative correlation with G3 (-0.360).
4. Mother's education has a weak positive correlation with G3 (0.217).
5. Father's education has a weak positive correlation with G3 (0.152).
6. Study time has a very weak positive correlation with G3 (0.098).
7. Absences have almost no linear correlation with G3 (0.034).
8. Several social and lifestyle variables show weak relationships with final grades.
9. Correlation indicates association between variables but does not establish causation.

## Visualizations

The project includes visualizations such as:

* Final grade distribution
* Study time vs final grade
* Previous failures vs final grade
* Absences vs final grade
* Parents' education vs final grade
* Parents' occupation vs final grade
* Social and lifestyle factors vs final grade
* Correlation heatmap

## Conclusion

This project provides an exploratory analysis of student performance and highlights relationships between final grades and different academic, family, social, and lifestyle factors.

The analysis shows that previous grades have the strongest relationship with final grades in this dataset, while several other factors have weaker relationships. These findings describe patterns in the dataset and should not be interpreted as proof of causal relationships.

## How to Run

### 1. Clone the repository

```bash
```

### 2. Navigate to the project directory

```bash
cd Student-Performance-Analysis
```

### 3. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 4. Open the notebook

```bash
jupyter notebook
```

Open the project notebook and run the cells from top to bottom.

## Future Improvements

Possible future improvements include:

* Building a machine learning model to predict final grades
* Feature engineering
* Comparing different machine learning algorithms
* Evaluating model performance
* Creating an interactive dashboard
* Adding more advanced statistical analysis

## Author

**Muhammad Aqil**

BS Artificial Intelligence Student
University of Management and Technology (UMT), Lahore

