Week 5 — Comprehensive Data Science Project Reporting and Strategic Recommendations

Project Overview

This project presents a comprehensive end-to-end data science analysis of the Titanic passenger dataset. Week 5 integrates the work completed during Weeks 1–4 and converts the technical findings into a structured project report with data-driven insights and strategic recommendations.

The project covers data cleaning, exploratory data analysis, visualization, statistical analysis, machine learning, model evaluation, error analysis, and practical recommendations.

Objectives

* Integrate the analysis and findings from Weeks 1–4.
* Present the complete data science workflow in a structured report.
* Summarize important patterns and statistical findings.
* Evaluate machine learning models for passenger survival prediction.
* Analyse model performance and prediction errors.
* Develop strategic recommendations based on the findings.
* Discuss project limitations and possible future improvements.

Project Workflow

Week 1 — Data Cleaning and Exploratory Analysis

The original Titanic dataset contained 891 rows and 15 columns. Missing values were handled using appropriate techniques, the `deck` column was removed because of extensive missing data, and duplicate records were removed.

The final cleaned dataset contained:

* 780 rows
* 14 columns
* 0 missing values
* 0 duplicate records

Key findings included differences in survival by gender and passenger class.

Week 2 — Data Visualization

Multiple visualizations were created to understand relationships and patterns in the dataset, including:

* Survival distribution
* Survival by gender
* Survival by passenger class
* Age distribution
* Fare distribution
* Age versus fare
* Correlation heatmap
* Age-group survival analysis

These visualizations provided deeper understanding of the factors associated with passenger survival.

Week 3 — Statistical Analysis

Statistical hypothesis tests were performed to determine whether observed relationships were statistically significant.

Major analyses included:

* Chi-square test for gender and survival
* Welch's t-test for fare and survival
* One-way ANOVA for fare across passenger classes
* Tukey post-hoc analysis

The statistical results provided strong evidence that gender, passenger class, and fare were associated with survival and passenger characteristics.

Week 4 — Machine Learning

Machine learning models were developed to predict passenger survival.

The main models evaluated were:

* Logistic Regression
* Default Decision Tree
* Tuned Decision Tree

Logistic Regression achieved the strongest overall performance.

Final Model

Logistic Regression

* Accuracy: 80.13%
* Precision: 73.91%
* Recall: 79.69%
* F1 Score: 76.69%
* ROC-AUC: 0.8822

The model also showed a small train-test accuracy gap of approximately 1.60 percentage points, indicating relatively stable performance on the selected train-test split.

Key Findings

1. Female passengers had a substantially higher survival rate than male passengers.
2. First-class passengers had the highest survival rate, followed by second-class and third-class passengers.
3. Survivors had a higher average fare than non-survivors.
4. Fare differed significantly across passenger classes.
5. Logistic Regression provided the strongest overall predictive performance among the evaluated models.
6. Model errors were not evenly distributed across passenger subgroups.
7. Combining multiple passenger characteristics provided useful predictive information.

Strategic Recommendations

Based on the combined statistical and machine learning findings:

* Use multiple relevant variables rather than relying on a single factor for predictive decisions.
* Prefer stable and interpretable models when predictive performance is strong.
* Evaluate models using multiple performance metrics instead of accuracy alone.
* Monitor subgroup-level errors to identify areas where model performance differs.
* Combine exploratory analysis, statistical evidence, and machine learning results when making data-driven decisions.

Limitations

* The Titanic dataset is historical and may not represent modern real-world situations.
* The analysis identifies associations and predictive patterns but does not establish causation.
* The `deck` variable contained substantial missing data and was therefore removed.
* Model performance depends on the selected features and train-test split.
* Only a limited number of machine learning algorithms were evaluated.
* Differences in subgroup error rates do not by themselves establish systematic bias.

Future Improvements

Future work could include:

* Cross-validation for more robust model evaluation.
* Evaluation of additional algorithms such as Random Forest and Gradient Boosting.
* Systematic hyperparameter tuning.
* Additional feature engineering.
* Model probability calibration.
* More detailed subgroup and fairness analysis.
* Interactive dashboard development.
* Automated data quality checks.
* Improved version control and project documentation.

Tools and Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook / Python environment
* GitHub

Project Repositories

Week 1 — Data Analysis

https://github.com/ayushi2004-data/Week1_Data_Analysis

Week 2 — Advanced Data Visualization

https://github.com/ayushi2004-data/Week2_Advanced_Data_Visualization

Week 3 — Statistical Analysis

https://github.com/ayushi2004-data/Week3_Statistical_Analysis

Week 4 — Machine Learning

https://github.com/ayushi2004-data/Week4_Machine_Learning

Week 5 Deliverable

The main deliverable for Week 5 is the comprehensive project report:

Week5_Comprehensive_Data_Science_Project_Report.docx

The report integrates the technical work from Weeks 1–4 and presents the overall findings, model evaluation, strategic recommendations, limitations, and future improvements.

Conclusion

This Week 5
