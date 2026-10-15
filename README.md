# CreditWise-ML 💳
### Loan Approval Prediction using Machine Learning

CreditWise-ML is a machine learning project that predicts loan approval outcomes based on applicant details such as income, credit score, savings, and other relevant factors.

The goal of this project is to explore applicant data, train different machine learning models, and compare their performance to find which model works best for loan approval prediction.

## 📌 Project Overview

In this project, I worked on the complete machine learning workflow, from data cleaning and analysis to model training and evaluation. I also experimented with feature engineering to see how creating new features affects model performance.

## 📂 Dataset

- **File:** `loan_approval_data.csv`
- **Records:** 1,000 applicants
- **Target variable:** Loan approval status
- **Features:** Income, credit score, savings, and other applicant-related attributes

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn

## ⚙️ Project Workflow

1. **Data Loading:** Loaded the dataset using Pandas.
2. **Data Cleaning:** Handled missing values using mean imputation for numerical columns and most-frequent-value imputation for categorical columns. Removed the applicant ID.
3. **Exploratory Data Analysis (EDA):** Used visualisations and correlation analysis to understand the data and identify patterns related to loan approval.
4. **Preprocessing:** Encoded categorical variables and standardised numerical features.
5. **Train-Test Split:** Split the data into 80% training and 20% testing sets.
6. **Model Training:** Trained three classification models using the training data.
7. **Model Evaluation:** Compared the models using accuracy, precision, recall, F1-score, and confusion matrices.
8. **Feature Engineering:** Created a Debt-to-Income (DTI) ratio, squared credit score, and log-transformed income, then evaluated the models again.

## 🤖 Machine Learning Models

The following models were trained and compared:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes

## 📊 Results

| Model | Original Features | After Feature Engineering |
|---|---:|---:|
| Logistic Regression | 86.5% | **88.0%** |
| KNN | 76.0% | 75.5% |
| Gaussian Naive Bayes | 86.5% | 86.5% |

Logistic Regression achieved the highest accuracy of **88%** after feature engineering in this experiment.

Feature engineering improved Logistic Regression accuracy by 1.5 percentage points. KNN accuracy decreased slightly, while Gaussian Naive Bayes remained unchanged.

## 🚀 How to Run the Project

**1. Clone the repository**

```bash
git clone https://github.com/anubhav6780/CreditWise-ML.git
```

**2. Navigate to the project folder**

```bash
cd CreditWise-ML
```

**3. Install the required libraries**

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

**4. Start Jupyter Notebook**

```bash
jupyter notebook
```

**5. Run the notebook**

Open `credit_wise.ipynb` and execute the cells in order.

## 📚 Key Learnings

Through this project, I gained practical experience in data preprocessing, exploratory data analysis, feature engineering, classification algorithms, and model evaluation.

One key takeaway was that feature engineering does not always improve every model. Its impact depends on the algorithm and the features used.

## 🔮 Future Improvements

- Build an interactive web application using Streamlit.
- Allow users to enter applicant details and receive a prediction.
- Apply hyperparameter tuning and cross-validation.
- Explore model explainability to better understand prediction results.

## ⚠️ Disclaimer

This project is intended for educational purposes. Its predictions are experimental and should not be used as the sole basis for real-world lending decisions.

## 👨‍💻 Author

**Anubhav Prakash**

B.Tech Computer Science and Engineering Student

Interested in Artificial Intelligence and Machine Learning.
