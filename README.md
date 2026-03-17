# Student Placement Prediction using Logistic Regression

## Project Objective

This project predicts whether a student is likely to be placed or not based on academic performance and skill-related features.

The goal is to understand classification workflow, feature influence, and model evaluation in machine learning.

---

## Dataset Features

The model uses the following input features:

* CGPA
* AptitudeScore
* CommunicationSkill
* Internships
* Projects
* Certifications
* MockInterviewScore
* Backlogs
* Attendance
* CodingScore

Target Variable:

* Placed

  * 1 → Placed
  * 0 → Not Placed

---

## Project Workflow

1. Data Loading and Understanding
2. Data Visualization (scatter plots and correlation heatmap)
3. Feature Selection
4. Train-Test Split
5. Feature Scaling using StandardScaler
6. Model Training using Logistic Regression
7. Model Evaluation

   * Accuracy
   * Confusion Matrix
   * Classification Report
8. Manual Prediction on new student data
9. Model Saving using Pickle

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Model Performance

The model performance is evaluated using:

* Accuracy Score
* Confusion Matrix
* Precision, Recall and F1-Score

These metrics help understand classification correctness and model reliability.

---

## Key Insights

* Higher coding score increases placement probability
* Students with more backlogs have lower placement chances
* CGPA and mock interview performance positively influence placement
* Practical experience such as internships and projects improves outcomes

---

## How to Run the Project

1. Download the dataset and notebook/script
2. Install required libraries:

```
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Run the notebook or Python file
4. Observe model evaluation results and predictions

---

## Future Improvements

* Try advanced models such as Decision Tree and Random Forest
* Perform hyperparameter tuning
* Deploy model using Streamlit or Flask
* Add more real-world features

---

## Author

Machine Learning Beginner Project
Student Placement Prediction using Logistic Regression

