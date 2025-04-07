# Smart Credit Risk Scoring System for Digital Lending

**Goal**: Predict whether a loan applicant is likely to default or not, to improve credit decisioning and reduce risk.(prioritize features based on impact)

**Dataset**: Lending Club loan dataset (public, available on Kaggle)

**Tech Stack**: Python, Jupyter, pandas, scikit-learn, matplotlib, seaborn

**ML Models**: Logistic Regression, Random Forest

**Business Impact**: 
- Reduce loan defaults
- Accelerate approval times
- Help prioritize low-risk borrowers

**Results**:
Accuracy and Class 0 Recall favor Random Forest.

Class 1 Precision and Class 1 Recall favor Logistic Regression.

Macro Average F1-Score favors Logistic Regression slightly.

Overall, the performance is quite close, but Random Forest has a slight advantage in accuracy and recall for Class 0, while Logistic Regression performs better in Class 1-related metrics and macro F1-score.

**Top Attributes affecting Credit Risk**

amount
status
age
duration
purpose