## Student Performance Risk Analysis

### Problem Statement
Educational institutions often struggle to identify students at risk of failing early enough to intervene.
This project predicts student failure risk using academic and behavioral data.

### Dataset
- Source: UCI Machine Learning Repository
- Records: 395 students
- Features used: absences, study time, prior grades (G1, G2)

### Approach
1. Data cleaning and preprocessing
2. Exploratory Data Analysis to identify risk factors
3. Logistic Regression model for pass/fail prediction
4. Evaluation using recall and confusion matrix

### Key Insights
- Students with higher absences showed significantly higher failure risk.
- Prior academic performance (G1, G2) was the strongest predictor.
- Combining attendance with early grades provides an effective early warning signal.

### Model Performance
- Recall: **87%**
- Focused on minimizing missed at-risk students

### Tools Used
- Python (Pandas, NumPy, Scikit-learn)
- Google Colab
- GitHub

### Conclusion
This project demonstrates how simple, interpretable models can effectively identify students who may benefit from early academic intervention.
