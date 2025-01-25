#  Heart Disease Prediction Project

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![Status](https://img.shields.io/badge/Status-In%20Progress-orange)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Classification-green)

##  Project Overview

This project aims to predict the likelihood of heart disease in patients using machine learning algorithms. By leveraging clinical and demographic data, the project demonstrates preprocessing, model implementation, and evaluation to classify individuals at risk.

---

##  Features

1. **Data Preprocessing:**
   - Cleaning and normalizing key features using `StandardScaler`.
   - Handling numerical and categorical data effectively.

2. **Exploratory Data Analysis (EDA):**
   - Visualizing distributions and relationships between variables.
   - Identifying correlations and feature importance.

3. **Machine Learning Models:**
   - Implementation of classification algorithms, including:
     - Logistic Regression
     - K-Nearest Neighbors (KNN)
     - Decision Trees
     - Support Vector Machines (SVM)
   - Model evaluation using accuracy, precision, recall, F1-score, and ROC curves.

4. **Visualization:**
   - Confusion matrices, feature importance plots, and performance comparisons.

---

##  Project Structure

```
/Heart-Disease-Prediction/
├── data/               # Dataset files
├── notebooks/          # Jupyter Notebooks for EDA and experiments
├── src/                # Python scripts for data processing and modeling
├── models/             # Trained models and saved files
├── results/            # Performance reports and visualizations
├── requirements.txt    # Python dependencies
├── README.md           # Project documentation
├── LICENSE             # Project license
├── .gitignore          # Ignored files and directories
```

---

## Dataset Preview

The dataset `heart.csv` contains 303 records with the following features:

| Column     | Description                                                                   |
| ---------- | ----------------------------------------------------------------------------- |
| `age`      | Age of the patient                                                            |
| `sex`      | Gender of the patient (1 = male, 0 = female)                                  |
| `cp`       | Chest pain type (0-3: different types of chest pain)                          |
| `trestbps` | Resting blood pressure (in mm Hg)                                             |
| `chol`     | Serum cholesterol in mg/dl                                                    |
| `fbs`      | Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)                         |
| `restecg`  | Resting electrocardiographic results (values 0, 1, 2)                         |
| `thalach`  | Maximum heart rate achieved                                                   |
| `exang`    | Exercise-induced angina (1 = yes, 0 = no)                                     |
| `oldpeak`  | ST depression induced by exercise relative to rest                            |
| `slope`    | The slope of the peak exercise ST segment                                     |
| `ca`       | Number of major vessels (0-3) colored by fluoroscopy                          |
| `thal`     | Thalassemia (3 = normal, 6 = fixed defect, 7 = reversible defect)             |
| `target`   | Target variable (1 = presence of heart disease, 0 = absence of heart disease) |


**Target Variable:**
- `Target`: Binary indicator of heart disease presence (1: Yes, 0: No).

---

##  Setup and Usage

### Prerequisites
- **Python 3.8+**
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

### Installation Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/blueberrygurl/Heart-Disease-Prediction.git
   cd Heart-Disease-Prediction
   ```


2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook for exploration:
   ```bash
   jupyter notebook
   ```

---


## 💌Contact

For questions or suggestions, contact me at: mohhiaya3@gmail.com
