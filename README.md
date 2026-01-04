# 💳 Loan Default Prediction (Random Forest & Decision Tree)

📊 A machine learning project focused on predicting loan defaults using ensemble methods, comparing Decision Tree and Random Forest classifiers to identify high-risk borrowers.

**Dataset Overview:** The LendingClub dataset contains loan data from 2007-2010, including borrower financial information, credit scores, and loan repayment status. This project demonstrates the complete ML pipeline from exploratory data analysis to model comparison and feature importance analysis.

**Dataset Source:** [Loan Data (Kaggle)](https://www.kaggle.com/datasets/itssuru/loan-data)

## 📁 Project Structure

* `loan_prediction.ipynb`: Main script containing data exploration, visualizations, model training, and performance comparison.
* `loan_data.csv`: Dataset including borrower information (FICO score, interest rate, debt-to-income ratio, credit policy) and loan repayment status.

## 📈 Key Insights

* **Predictive Models:** Built and compared Decision Tree and Random Forest classifiers to predict loan default probability.
* **Model Performance:** Random Forest significantly outperformed Decision Tree with 84.66% accuracy vs 73.28% (11.38% improvement).
* **Feature Importance:** Identified FICO score and interest rate as the strongest predictors of loan default, with credit policy compliance also playing a key role.
* **Data Preprocessing:** Converted categorical features (loan purpose) into dummy variables using one-hot encoding for model compatibility.
* **Visualization Highlights:** Created FICO score distributions, loan purpose analysis, confusion matrix heatmaps, and feature importance plots using Seaborn and Matplotlib.
* **Business Application:** The model can help lending institutions identify high-risk borrowers and make more informed lending decisions.

## 🛠️ Tools Used

* Python (Pandas, NumPy, Seaborn, Matplotlib, Scikit-Learn)
* Jupyter Notebook (for data exploration and model development)
* Git & GitHub

## 📫 Contact
**www.linkedin.com/in/kanishkayadvv**

**Author:** Kanishka Yadav
