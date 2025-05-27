# Predicting-Forest-Fire-Occurrence-and-Severity-in-Algeria
 To analyze and predict the occurrence and severity of forest fires in Algeria using meteorological and environmental data from the Algerian Forest Fires dataset
Project Title: Predicting Forest Fire Occurrence and Severity in Algeria
Objective:
To analyze and predict the occurrence and severity of forest fires in Algeria using meteorological and environmental data from the Algerian Forest Fires dataset.
Dataset Overview:
Name: Algerian Forest Fires Processed Dataset
Source: [UCI Machine Learning]("Algerian Forest Fires - UCI Machine Learning Repository")
Additional Information
The dataset includes 244 instances that regroup data from two regions of Algeria, namely the Bejaia region, located in the northeast of Algeria, and the Sidi Bel-Abbes region, located in the northwest of Algeria. 122 instances for each region. The period from June 2012 to September 2012. The dataset includes 11 attributes and 1 output attribute (class). The 244 instances have been classified into “fires” (138 classes) and “not fire”(106 classes) classes
Attributes:
    - Date, Temperature, RH (Relative Humidity), Ws (Wind Speed), Rain, FFMC, DMC, DC, and ISI (fire weather indices)
    - Classes: fire, not fire
Project Scope:
Students will perform:
- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Feature Engineering
- Supervised Machine Learning (Classification)
- Model Evaluation & Selection
- Visualization & Interpretation
- Model Deployment (optional but ideal)

🛠️ Tools & Libraries:
- Python (Jupyter/Colab)
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn
- Streamlit or Flask (for deployment)
- Git & GitHub (for version control)
Project Workflow:
🔹 1. Problem Statement
Forest fires in Algeria cause serious environmental damage. Predicting their occurrence can help in proactive disaster management.
🔹 2. Data Collection
Students should:
- Download the dataset from the UCI Repository
- Store it as a CSV file (Algerian_forest_fires.csv)
🔹 3. Exploratory Data Analysis (EDA)
Tasks:
- Inspect column names and data types
- Check for missing values
- Describe statistical properties
Visualize:
- Correlation matrix
- Fire vs. No fire distributions
- Feature-wise distributions using boxplots and histograms
- Regional trends (Bejaia vs Sidi-Bel Abbes)
🔹 4. Data Preprocessing
Steps:
- Convert Date to datetime
- Encode Classes as binary (fire = 1, not fire = 0)
- Normalize/standardize numerical features (optional)
- Handle outliers if any
- Split dataset: Train/Test (80/20)
🔹 5. Feature Engineering
Ideas:
- Create Fire_Index = weighted sum of FFMC, DMC, DC, and ISI
- Extract month/season from date
- Use regional info (Bejaia vs Sidi-Bel Abbes) as a categorical feature
🔹 6. Model Building (Classification)
**Models to try**:
- Logistic Regression
- Random Forest
- XGBoost
- Support Vector Machine
🔹 7. Model Evaluation
Metrics:
- Accuracy
- Precision, Recall, F1-Score
- ROC-AUC
- Confusion Matrix
- Cross-Validation
🔹 8. Interpretability
Feature Importance using:
- RandomForest feature importance
- SHAP (optional)
- Partial dependence plots (optional)
🔹 9. Model Tuning
- Use GridSearchCV or RandomizedSearchCV
- Tune hyperparameters of the best model
🔹 10. Model Deployment (Optional but Recommended)
Tools:
- Use Streamlit/Flask to create a simple UI
- Input: Temperature, RH, Wind Speed, FFMC, etc.
- Output: Probability of fire
- Host on Streamlit Cloud or locally
🔹 11. Documentation and Reporting
Deliverables:
- Python notebook with all steps
- PDF/Markdown report summarizing:
- Problem, Data, Findings, Model Performance, Recommendations
- GitHub repo with README and code
