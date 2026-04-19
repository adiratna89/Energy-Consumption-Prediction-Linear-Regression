
# Energy Consumption Prediction – Linear Regression

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) 
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-16a34a?style=for-the-badge)

### Predicting building **energy consumption** using exploratory data analysis (EDA), visualization, and a Linear Regression model in Python.

---

## 🔍 Project Overview

This project analyses an energy consumption dataset of different building types and builds a Linear Regression model to predict energy usage based on features like square footage, number of occupants, appliances used, average temperature, and day of the week.  
It is designed as a compact end‑to‑end ML project: data understanding, EDA, preprocessing, model training, and evaluation – all inside a single Jupyter Notebook.

---

## 📂 Dataset

- **Source:** [Kaggle – Energy Consumption Dataset (Linear Regression)](https://www.kaggle.com/datasets/govindaramsriram/energy-consumption-dataset-linear-regression?resource=download)  
- **Target variable:** `Energy Consumption`  
- **Example features:**
  - Building Type (Residential, Commercial, Industrial)
  - Square Footage  
  - Number of Occupants  
  - Appliances Used  
  - Average Temperature  
  - Day of Week  

---

## 🧠 Goals

- Perform EDA to understand distributions and relationships in the energy data.
- Visualize patterns across building types and days (weekday vs weekend).
- Build and train a Linear Regression model to predict energy consumption.
- Evaluate model performance using regression metrics and inspect prediction output.

---

## 🛠 Tech Stack

- **Language & Environment:**  
  ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
  ![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

- **Data & Visualization:**  
  ![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
  ![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
  ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)
  ![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge)

- **Machine Learning:**  
  ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)

---

## 📊 Notebook Workflow

The main notebook:  
`Energy Consumption Prediction using LINEAR REGRESSION , EDA, VISUALIZATION.ipynb`

High‑level steps:

1. **Import libraries & load data**  
   - Read `train_energy_data.csv` (and optionally `test_energy_data.csv`) with pandas.
2. **Initial exploration**  
   - `.head()`, `.info()`, `.describe()` to understand the structure and statistics.  
   - Check missing values and basic distributions.
3. **EDA & Visualization**  
   - Count plots for building types and day of week.  
   - Distribution plots and boxplots for numeric features.  
   - Correlation heatmap to inspect feature relationships with energy consumption.
4. **Data preprocessing**  
   - Encode categorical variables (e.g., Building Type, Day of Week).  
   - Train–test split for the regression model.
5. **Modeling – Linear Regression**  
   - Train a Linear Regression model using scikit‑learn.  
   - Predict on test data and analyse results.
6. **Evaluation & Outputs**  
   - Compute regression metrics (e.g., MAE, MSE, R²).  
   - Save or view predictions (e.g., `linear_regression_predictions.csv`).  
   - Use plots to visually compare predicted vs actual energy consumption.

---

## 🚀 How to Run Locally

1. **Clone the repository**

```bash
git clone https://github.com/adiratna89/Energy-Consumption-Prediction-Linear-Regression.git
cd Energy-Consumption-Prediction-Linear-Regression
```

2. **Create & activate a virtual environment** (optional but recommended)

```bash
python -m venv venv
venv\Scripts\activate  # Windows
# source venv/bin/activate  # macOS/Linux
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

> If there is no `requirements.txt` yet, install at least:
> ```bash
> pip install pandas numpy matplotlib seaborn scikit-learn jupyter
> ```

4. **Launch Jupyter Notebook**

```bash
jupyter notebook
```

5. **Open the notebook**

- Open `Energy Consumption Prediction using LINEAR REGRESSION , EDA, VISUALIZATION.ipynb`.
- Run all cells in order to reproduce the analysis and model results.

---

## 🖼 Sample Visualizations & Output

Here are a few snapshots from the notebook to give a quick visual idea of the analysis and model results.

### 1. EDA – Building Type Distribution

![Building Type Distribution](./Screenshot%202026-04-20%20020612.png)

### 2. EDA – Day of Week Distribution

![Day of Week Distribution](./Screenshot%202026-04-20%20020720.png)

### 3. The best‑fit Linear Regression Line (with confidence interval)

![Linear Regression Line](./Screenshot%202026-04-19%20215523.png)

---

## 📌 Project Status & Notes

- ![Status](https://img.shields.io/badge/Status-Completed-16a34a?style=for-the-badge)  
- This project is intended as a portfolio‑friendly ML mini project showing:
  - Clean EDA and visualizations.
  - A simple but well‑structured regression pipeline.
  - Clear separation of data, analysis, and output files.

---

## 📧 Contact

If you have feedback or suggestions, feel free to reach out via GitHub or LinkedIn.  
Always open to learning and collaboration in data science and machine learning.
