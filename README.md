# SONAR Rock vs Mine Prediction

This is a beginner-friendly machine learning project that uses **Logistic Regression** to classify SONAR signals as either **rocks** or **mines** using a dataset from the UCI Machine Learning Repository. It’s a classic binary classification problem that's great for practicing data preprocessing, model building, and evaluation.

---

## Problem Statement

The goal is to develop a model that can distinguish between SONAR signals bounced off a rock and those bounced off a metal cylinder (mine), using 60 numerical features recorded per signal.

---

## Dataset Description

- **Source**: UCI Machine Learning Repository  
- **Instances**: 208 samples  
- **Features**: 60 numerical attributes per sample  
- **Target Labels**:  
  - `M` → Mine  
  - `R` → Rock

---

## Tools & Libraries Used

- Python
- Pandas  
- NumPy  
- Scikit-learn  

---

## Workflow

1. **Import Dependencies**
2. **Load the Dataset**
3. **Data Exploration**
   - View shape and statistics
   - Check label distribution
4. **Preprocessing**
   - Feature/label separation
   - Train-test split
5. **Model Training**
   - Logistic Regression
6. **Model Evaluation**
   - Accuracy on both training and test data
7. **Prediction System**
   - Manual testing using NumPy arrays

---

## Results

The model performs reasonably well using Logistic Regression:

- Accuracy on **training data**: ~83%  
- Accuracy on **test data**: ~78%  

> Note: Results may vary slightly depending on random state and train-test split.

---

##  How to Run

1. Clone this repository or download the notebook.
2. Ensure the dataset is correctly linked in your environment.
3. Run the notebook step-by-step in **Jupyter Notebook** or **Google Colab**.

**Dataset link**: [Download Sonar Data](https://drive.google.com/file/d/1Tuq_EzLyVneiju99IzPi2hFyYFohfymV/view?usp=drive_link)

> Update the file path in the notebook to match your environment.

---

## Future Enhancements

- Try other classification models like SVM, Random Forest, or Gradient Boosting  
- Add visualizations for better feature and result analysis  

---

## Acknowledgments

- [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/connectionist+bench+(sonar,+mines+vs.+rocks))  
- The open-source Python and Scikit-learn community

