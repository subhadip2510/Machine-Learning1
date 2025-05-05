# Molecular Solubility Prediction using Machine Learning 🧪🤖

This project uses machine learning to predict the solubility (logS) of molecules based on a set of chemical descriptors. The dataset is sourced from the Delaney solubility dataset.

## 📊 Dataset

- **Source**: [Delaney solubility dataset](https://raw.githubusercontent.com/dataprofessor/data/refs/heads/master/delaney_solubility_with_descriptors.csv)
- **Target Variable**: `logS` (measured solubility)
- **Features**: Various molecular descriptors (e.g., molecular weight, LogP, hydrogen bond donors/acceptors, etc.)

## 🧠 ML Workflow

### 1. 📥 Load Data
Using pandas to read the CSV file directly from a URL.

### 2. 🧹 Data Preparation
- Selecting `logS` as the target variable.
- Inspecting and potentially cleaning the dataset.

### 3. 📈 Model Training
- Used regression models to predict logS values.
- Models likely include:
  - Linear Regression
  - Ridge/Lasso Regression
  - Random Forest Regressor
  - Possibly other scikit-learn regressors

### 4. 🧪 Evaluation
- Evaluated using metrics such as:
  - Mean Squared Error (MSE)
  - R² Score

### 5. 📉 Visualization
- Plots to compare predicted vs. actual logS values.
- Residual plots to check model performance.

## 🛠 Tools & Libraries
- Python
- Pandas
- scikit-learn
- Matplotlib / Seaborn (for visualization)

## 📚 References
- Dataset from Delaney (2014)
- Project inspired by Data Professor's ML workflows

## 🚀 How to Run
```bash
pip install -r requirements.txt
python ML1.ipynb
