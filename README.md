# Glucose Prediction Using Framingham Heart Study Data

This project predicts glucose levels (or diabetes risk) using machine learning techniques applied to the Framingham Heart Study dataset. The notebook demonstrates data preprocessing, feature selection, model training, evaluation, and insights drawn from the dataset.

## 📊 Dataset

- **Source**: [Framingham Heart Study](https://www.kaggle.com/datasets/amanajmera1/framingham-heart-study-dataset)
- **File**: `framingham.csv`
- **Description**: The dataset contains demographic, behavioral, and medical history information for patients. Target feature includes diabetes indicators like glucose levels.

## 📁 Files

- `Glucose_Prediction_Summary.ipynb`: Jupyter notebook containing code for loading, preprocessing, training ML models, and evaluation.
- `framingham.csv`: Dataset used for training and evaluation.

## 📌 Features Used

Some of the key features include:
- `age`
- `education`
- `male`
- `cigsPerDay`
- `BPMeds`
- `prevalentStroke`
- `prevalentHyp`
- `diabetes`
- `totChol`
- `sysBP`, `diaBP`
- `BMI`
- `heartRate`
- `glucose`

## 🧠 Machine Learning Models

This notebook may include (based on your work):
- Logistic Regression
- Random Forest
- Decision Tree
- Support Vector Machine
- XGBoost (optional)

Each model is evaluated using accuracy, confusion matrix, and classification report.

## ⚙️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/m4milaad/glucose-prediction-framingham.git
   cd glucose-prediction-framingham

2. Install dependencies:
   ```bash
   pip install -r requirements.txt

3. Run the notebook:
   ```bash
   jupyter notebook Glucose_Prediction_Summary.ipynb


📈 Output
- Performance metrics of trained models

- Visualizations of feature importance

- Predictions and evaluation results

🧪 Requirements

- Python 3.7+
- pandas
- scikit-learn
- matplotlib
- seaborn
- jupyter

✍️ Author
Milad Ajaz Bhat

📄 License
This project is open-source and available under the MIT License.
