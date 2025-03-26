# Student Alcohol Consumption & Academic Performance

### Overview
This project explores the **Student Alcohol Consumption** dataset from [Kaggle](https://www.kaggle.com/datasets/uciml/student-alcohol-consumption), focusing on how alcohol intake (weekday/weekend) correlates with academic success (grades G1, G2, G3). It merges two separate datasets (Math & Portuguese classes) into a single, consolidated DataFrame. By applying statistical analysis and machine learning techniques (Linear Regression, k-Nearest Neighbors, Decision Trees, etc.), we identify key predictors of final student performance and quantify how behaviors like alcohol consumption and study time impact grades.

---

## Project Contents
1. **BAN620_Final_Report.ipynb**  
   - Main Jupyter Notebook that covers:
     - Data cleaning & merging (student-mat.csv & student-por.csv)  
     - Exploratory Data Analysis (EDA)  
     - Multiple linear regression & model comparison (kNN, Decision Tree)  
     - Cluster analysis (K-Means) for student segmentation  

2. **annotated-Group4-Report.pdf / BAN620_Final_Report.pdf / BAN_620_Project_Report_Group_4.pdf**  
   - PDF reports summarizing methodology, findings, and recommendations in a more formal, written format.

3. **(Optional) Data Files**  
   - If the data is not too large or proprietary, include or reference it. Otherwise, direct users to Kaggle for the original dataset.

---

## Key Insights
1. **Grades G1 & G2** are the strongest predictors of final score (G3), with high R² across models.  
2. **Alcohol Consumption** (weekends especially) correlates negatively with academic performance, though the effect is somewhat moderate.  
3. **Parental Education** also influences performance, suggesting a partial protective factor against negative behaviors.  
4. **Linear Regression** outperformed k-Nearest Neighbors and Decision Trees in predicting final grades on validation data (R² up to ~0.91).  
5. **Clustering** revealed distinct student segments based on alcohol use, study habits, and outcomes.

---

## How to Run
1. **Clone this repo**:  
   git clone https://github.com/itsakram-dot/student-alcohol-performance.git
   cd student-alcohol-performance

2. Open & run the Jupyter Notebook
   jupyter notebook BAN620_Final_Report.ipynb

3. Explore the PDF Reports:
	•	Each PDF details the analysis flow, advanced techniques, and policy recommendations.

## Results & Conclusions
	•	R² up to ~0.91 suggests strong predictive power for final grades (G3).
	•	Moderate negative correlation between weekend alcohol consumption and G3 indicates important lifestyle implications.
	•	Cluster Analysis indicates possible high-risk groups combining low study time with high alcohol consumption.

 
