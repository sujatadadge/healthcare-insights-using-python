🩺 Healthcare Data Analysis using Python
📘 Overview

This project focuses on analyzing a healthcare dataset (Kaggle – Prasad22) to explore relationships between key health indicators such as Age, BMI, Blood Pressure, and Cholesterol.
Using Python and powerful libraries like Pandas, NumPy, Matplotlib, and Seaborn, the dataset was cleaned, visualized, and analyzed to discover patterns that can support better healthcare decision-making.

🎯 Objective

Clean and preprocess the healthcare dataset.

Perform Exploratory Data Analysis (EDA) to identify key health trends.

Visualize relationships between major health indicators.

Generate insights and a cleaned dataset ready for Power BI and SQL integration.

🧰 Tech Stack

Language: Python (Google Colab)

Libraries: Pandas, NumPy, Matplotlib, Seaborn

Dataset Source: Kaggle – Healthcare Dataset (Prasad22)

Output Files:

healthcare_analysis.ipynb → Python notebook

cleaned_healthcare_data.csv → Cleaned dataset for visualization

🧹 Data Cleaning Steps

Removed duplicates and handled missing values

Converted inconsistent text formats (e.g., names)

Filtered non-numeric data for correlation analysis

Created a new HealthRiskScore metric combining BMI, Cholesterol, and Blood Pressure

📊 Exploratory Data Analysis (EDA)

Visualizations included:

Age Distribution of Patients

Cholesterol Levels by Gender

Pairplot of BMI, Age, Blood Pressure, and Cholesterol

Correlation Heatmap of Key Health Metrics

Health Risk Score Distribution

💡 Key Insights

Age is positively correlated with Blood Pressure.

BMI and Cholesterol show a strong positive relationship.

Exercise is negatively correlated with BMI, indicating improved health outcomes.

Patients aged 40–60 tend to have higher Health Risk Scores.

🧠 Conclusion

This project highlights how data analysis can uncover critical health insights from raw data.
High BMI and Cholesterol contribute significantly to health risks, while regular exercise reduces them.
The project demonstrates how Python tools can transform healthcare data into actionable knowledge, supporting preventive care and decision-making.

🚀 Future Enhancements

Build Power BI dashboards using the cleaned dataset

Store and query data in MySQL for large-scale reporting

Develop a Machine Learning model to predict health risks

🏷️ Sample Commit Messages

Initial commit: Added dataset and setup notebook

Data cleaning completed: handled nulls and duplicates

Performed EDA and added visualizations

Created HealthRiskScore feature and summary insights

Exported cleaned dataset for Power BI

👩‍💻 Author

Sujata Dadge
📊 Data Analytics Enthusiast | Python & Power BI Learner
