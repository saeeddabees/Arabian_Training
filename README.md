# Titanic Survival Prediction - Random Forest Classifier

This project uses a **Random Forest Classifier** to predict passenger survival on the Titanic dataset. The notebook demonstrates data preprocessing, exploratory data analysis (EDA), model training, evaluation, and interpretation using feature importance.

## 🧠 Summary

- **Objective:** Predict survival using machine learning models with a focus on Random Forest.
- **Key Features Used:** `Sex`, `Age`, `Fare`, among others.
- **Outcome:** Random Forest outperformed other models due to its ensemble nature, reducing overfitting and improving generalization.

## 📊 Features Explored

The analysis suggests the following factors most strongly affected survival:
- Gender (`Sex`)
- Age
- Fare paid

## 📦 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook

## 🛠 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
# 🫀 Heart Attack Prediction using Machine Learning

This project is a data science notebook that explores and predicts the risk of heart attacks using machine learning algorithms. It involves data preprocessing, visualization, model training, and evaluation.

## 📁 Project Structure

- `heart_attack.ipynb`: Jupyter Notebook containing all data analysis, visualization, model building, and evaluation.
- Dataset: Loaded within the notebook (assumed to be from a CSV file).
- Models used: Logistic Regression, Decision Tree Classifier.

### 📊 Dataset Description

The dataset contains several clinical and demographic variables commonly used in cardiovascular risk prediction, such as:

- `age`: Age of the patient
- `sex`: Sex (1 = male; 0 = female)
- `cp`: Chest pain type
- `trestbps`: Resting blood pressure
- `chol`: Serum cholesterol (mg/dl)
- `fbs`: Fasting blood sugar > 120 mg/dl
- `restecg`: Resting electrocardiographic results
- `thalach`: Maximum heart rate achieved
- `exang`: Exercise-induced angina
- `oldpeak`: ST depression induced by exercise
- `slope`: Slope of the peak exercise ST segment
- `ca`: Number of major vessels colored by fluoroscopy
- `thal`: Thalassemia type
- `target`: Heart disease (1 = yes, 0 = no)

#### 🔍 Workflow Summary

1. **Importing Libraries**
2. **Data Cleaning & Preprocessing**
   - Handling missing values
   - Encoding categorical variables
3. **Exploratory Data Analysis (EDA)**
   - Correlation heatmap
   - Count plots for target and other features
4. **Modeling**
   - Train-test split
   - Logistic Regression
   - Decision Tree Classifier
5. **Evaluation**
   - Accuracy, confusion matrix, classification report
   - Visualization of confusion matrix

##### ✅ Results

- Two models were trained and evaluated.
- Accuracy metrics and performance plots are shown in the notebook.
- Logistic Regression and Decision Tree showed competitive performance in predicting heart disease.

###### 🛠️ Requirements

To run this project, you need:

- Python 3.x
- Jupyter Notebook
- pandas
- matplotlib
- seaborn
- scikit-learn

Install the required libraries with:

```bash
pip install pandas matplotlib seaborn scikit-learn
