# Titanic Survival Prediction

This repository contains a Python-based machine learning project that predicts whether a passenger survived the Titanic disaster. The project utilizes **Logistic Regression** to classify passengers based on features such as age, gender, ticket class, and fare.

## 📁 Project Structure
* `train.csv`: The training dataset containing passenger information (features and labels).
* `titanic_prediction.ipynb`: Jupyter Notebook containing data preprocessing, exploratory data analysis, and model building.

## 🚀 Features & Workflow
The implementation follows a standard data science workflow:
1. **Data Collection & Processing**: Loading and exploring the dataset dimensions and types.
2. **Handling Missing Values**: 
   * Dropping irrelevant columns with excessive missing data (e.g., `Cabin`).
   * Imputing missing values in numerical columns (e.g., `Age`) with the mean.
   * Imputing missing categorical values (e.g., `Embarked`) with the mode.
3. **Exploratory Data Analysis (EDA)**: Visualizing survival rates and demographic distributions using `seaborn` and `matplotlib`.
4. **Model Training**: Implementing a **Logistic Regression** model using `scikit-learn`.
5. **Evaluation**: Evaluating the model performance using accuracy score.

## 🛠️ Prerequisites & Installation

To run this project locally, ensure you have Python installed, then clone this repository and install the required dependencies:

```bash
git clone [https://github.com/Ibragoran10/titanic-survival-prediction.git]
cd titanic-survival-prediction
pip install numpy pandas matplotlib seaborn scikit-learn
