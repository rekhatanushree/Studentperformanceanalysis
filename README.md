# AI-Powered Student Performance Analysis and Prediction

**Author:** Rekha J
**Programme:** Master of Computer Applications (MCA)
**Internship:** AICTE–IBM SkillsBuild Data Analytics with AI Internship 2026

## 1. Project Overview

This project analyzes student performance data using Python and machine learning. It explores academic patterns and builds a classification model to identify students who may benefit from additional academic support.

## 2. Problem Statement

Student performance depends on several factors, including study time, previous failures, absences, and earlier grades. This project analyzes these factors and uses machine learning to predict a student performance category based on a defined grade threshold.

## 3. Objectives

* Analyze student performance data.
* Explore patterns using graphs and statistical summaries.
* Prepare data for machine learning.
* Train a Random Forest classification model.
* Evaluate model performance.
* Demonstrate a prediction for a sample student.

## 4. Dataset

The project uses a student performance dataset containing academic and personal attributes, including studytime, failures, absences, G1, G2, and G3.

The target variable is defined as:

* `at_risk = 1` when G3 is less than 10.
* `at_risk = 0` when G3 is 10 or higher.

This threshold is a project-defined rule, not a universal measure of student ability.

**Dataset source:** Add the exact dataset URL used in your notebook.

## 5. Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

## 6. Methodology

1. Load and inspect the dataset.
2. Prepare the data.
3. Perform exploratory data analysis.
4. Create the target variable.
5. Split the dataset into training and testing sets.
6. Train a Random Forest classifier.
7. Evaluate the model.
8. Test a sample prediction.

## 7. Results

* Model accuracy: Enter the actual percentage from your notebook.
* Classification report: Review precision, recall, and F1-score.
* Confusion matrix: Include the matrix produced by the model.
* Visualizations: Describe the main patterns shown in your graphs.

## 8. Conclusion

This project demonstrates how data analytics and machine learning can be applied to student performance data. The results provide an educational example of classification and should not be used as the sole basis for decisions about students.

## 9. How to Run

1. Install the libraries listed in `requirements.txt`.
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Run the cells in order.
4. Review the graphs, evaluation metrics, and prediction output.

## 10. Limitations

The model depends on the selected dataset, features, and grade threshold. Its predictions are estimates and require careful interpretation. Real-world use would require additional validation and human oversight.
