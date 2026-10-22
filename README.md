# Credit Wise – Loan Approval Prediction

## Project Overview
Credit Wise is a machine learning project that analyzes applicant and financial data to predict whether a loan will be approved. The project uses Python for data preprocessing, exploratory data analysis, visualization, and classification model evaluation.

## Objectives
- Analyze loan applicant data.
- Handle missing values in numerical and categorical columns.
- Explore relationships between applicant characteristics and loan approval.
- Apply feature encoding and feature scaling.
- Train and compare machine learning classification models.

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Machine Learning Models
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes

## Project Workflow
1. Load and inspect the dataset.
2. Handle missing values.
3. Perform exploratory data analysis (EDA).
4. Visualize loan approval patterns and financial features.
5. Encode categorical variables.
6. Analyze feature correlations.
7. Split data into training and testing sets.
8. Apply feature scaling.
9. Train and evaluate classification models using precision, recall, F1-score, accuracy, and confusion matrices.
10. Perform feature engineering and evaluate the models again.

## Files
- `credit_wise.ipynb` – Jupyter Notebook containing the analysis and machine learning workflow.
- `loan_approval_data.csv` – Dataset required to run the notebook (add this file if you have permission to share it).

## How to Run
1. Clone or download this repository.
2. Install the required libraries:
   `pip install pandas numpy matplotlib seaborn scikit-learn jupyter`
3. Place `loan_approval_data.csv` in the same directory as the notebook.
4. Open Jupyter Notebook and run `credit_wise.ipynb` cell by cell.

## Model Evaluation
The models are evaluated using precision, recall, F1-score, accuracy, and confusion matrices. Actual performance results should be recorded after running the notebook.

## Disclaimer
This project is for educational purposes only. Predictions from this project should not be used as the sole basis for real-world lending or credit decisions.

- [`credit_wise.ipynb`](credit_wise.ipynb): notebook with the analysis and model
  training code.
- [`requirements.txt`](requirements.txt): Python packages used by the notebook.

## Run the notebook

1. Install Python and Jupyter.
2. Install the project dependencies:

   ```bash
   python -m pip install -r requirements.txt
   ```

3. Place the authorized project dataset at `loan_approval_data.csv` in the
   project folder. The notebook reads this relative path in its first data
   loading cell.
4. Start Jupyter and open `credit_wise.ipynb`.

The dataset was not present in the project folder when this repository was
prepared, so the notebook cannot run end-to-end until you add that CSV. Do not
publish applicant or other personal data unless you are authorized to share it.
