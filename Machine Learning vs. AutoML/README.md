# Comparison of Automated Machine Learning against Traditional Modeling Techniques in Different Datasets

- **Goal:** Explore whether AutoML tools can both simplify machine learning process and enhance prediction power generally in different practical datasets
- **Project Breakdown:**
  - *First Phase (Iris Man vs. Machine.ipynb, iris_report2.docx):* Try to get familiarized with AutoML tools, and compare their performance with human-built machine learning models in traditional Iris dataset
  - *Second Phase (Panel_Data_Walmart.ipynb, walmart_report2.docx):* Discover AutoMLs' performance on Walmart sales panel dataset and compare it with performances of machine learning models, panel regression models, and Bayesian hierarchical models
- **Project Conclusion:** AutoMLs show similarly high accuracy in predicting simple datasets like Iris, but they significantly outperform other traditional modeling techniques in more complex panel datasets mainly due to their robustness in feature engineering. The application of AutoMLs on Walmart sales panel dataset can be furthermore extended to their usages in finance, where panel datasets widely exist. Full project report can also be found in this folder.
- **Data:**
  - *First Phase:* Iris dataset contains information of three species of flowers along with their petal and sepal features (the dataset comes from sklearn's database).
  - *Second Phase:* Three CSV files in this folder can be concatenated into one single dataset, where weekly sales of each department in each Walmart store are linked to numerous exogenous features.
