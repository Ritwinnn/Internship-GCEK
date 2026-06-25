# Day 5 — Loan Prediction using Machine Learning

## Overview
On Day 5 of my internship, I worked on building a Loan Prediction model using Machine Learning. This project involved data preprocessing, model training, testing, and making predictions using a Decision Tree Classifier.

## Objective
- Learn data preprocessing
- Understand feature selection
- Train a Decision Tree model
- Visualize the decision-making process
- Predict loan approval status

## Tools Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Google Colab

## Steps Performed

### 1. Dataset Loading
Loaded the loan prediction dataset directly from GitHub.

```python
df = pd.read_csv(url)
2. Data Cleaning

Removed missing values for better accuracy.

df = df.dropna()
3. Data Conversion

Converted categorical values into numerical format:

Male → 1
Female → 0
Yes → 1
No → 0
Graduate → 1
Not Graduate → 0
Urban → 2
Semiurban → 1
Rural → 0
4. Feature Selection

Selected important features:

Gender
Married
Education
Self Employed
Applicant Income
Loan Amount
Credit History
Property Area
5. Data Splitting

Split data into training and testing sets.

X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2, random_state=42)
6. Model Training

Trained a Decision Tree Classifier.

model = DecisionTreeClassifier(max_depth=4, random_state=42)
model.fit(X_train, y_train)
7. Accuracy Testing

Checked the model accuracy.

accuracy = model.score(X_test, y_test)
print(f"Test Accuracy: {accuracy * 100:.2f}%")
8. Decision Tree Visualization

Visualized the trained decision tree using Matplotlib.

9. Custom Prediction Testing

Tested custom user profiles for loan approval prediction.

Example output:

Loan Approved
Loan Denied
Key Learnings
Data preprocessing techniques
Feature engineering
Model training and testing
Decision tree working mechanism
Real-world prediction systems
Outcome

Successfully built and tested a Loan Prediction model using Machine Learning and understood the complete workflow from data preparation to prediction.