# Student-performance-Analysis


## **Project Overview**

This project focuses on analyzing student performance data to gain insights into factors that influence academic outcomes. The goal is to help educators and administrators identify key areas for improvement and make data-driven decisions to enhance student performance.

### **Objectives:**

- Analyze the relationship between various demographic, socio-economic, and academic factors with student performance.
- Explore trends and patterns in the data to uncover actionable insights.
- Predict student performance using machine learning models.

---

## **Datasets**

The dataset used in this project contains information on student demographics, parental background, study habits, and exam scores. You can use publicly available datasets such as:
- [UCI Student Performance Dataset](https://archive.ics.uci.edu/ml/datasets/student+performance)

**Attributes:**
- **Demographics**: Gender, Age, Nationality, etc.
- **Parental Info**: Parents' education level, occupation, etc.
- **Academic Info**: Previous grades, attendance, study hours, etc.
- **Performance Indicators**: Final exam scores, subject grades, etc.

---

## **Project Structure**

```
Student-Performance-Analysis/
│
├── data/                    # Dataset used in the analysis
│   ├── student-mat.csv
│   ├── student-por.csv
│
├── notebooks/               # Jupyter notebooks for analysis and model building
│   ├── 01_data_cleaning.ipynb
│   ├── 02_eda.ipynb
│   ├── 03_model_building.ipynb
│
├── src/                     # Source code for functions and scripts
│   ├── data_preprocessing.py
│   ├── performance_analysis.py
│   ├── model_training.py
│
├── results/                 # Results and output files (plots, reports, etc.)
│   ├── correlation_heatmap.png
│   ├── performance_report.txt
│
├── README.md                # Project documentation
├── requirements.txt         # List of dependencies
├── .gitignore               # Files to ignore in git repository
└── LICENSE                  # Project license
```

---

## **Installation and Setup**

To get started with the project, follow these steps:

### **1. Clone the Repository:**

```bash
git clone https://github.com/your-username/Student-Performance-Analysis.git
cd Student-Performance-Analysis
```

### **2. Set Up the Environment:**

Ensure you have Python installed (Python 3.7 or higher). Then, create a virtual environment and install the dependencies:

```bash
# Create a virtual environment
python -m venv venv

# Activate the virtual environment
# On Windows:
venv\Scripts\activate
# On Mac/Linux:
source venv/bin/activate

# Install the required dependencies
pip install -r requirements.txt
```

---

## **Exploratory Data Analysis (EDA)**

In the **EDA** step, we analyze the relationships between student demographics, parental background, and student performance. Key analyses include:

- Distribution of final grades.
- Correlation between study habits and performance.
- Impact of parental education on student outcomes.

---

## **Machine Learning Models**

We implemented machine learning models to predict student performance based on features such as study hours, parental education, and past academic performance.

### **Models Used:**
- **Linear Regression**: For predicting student exam scores.
- **Random Forest Classifier**: For predicting whether a student will pass or fail.
- **Support Vector Machine (SVM)**: For classifying student performance levels.

### **Model Evaluation:**
- **Accuracy**
- **Mean Squared Error (MSE)**
- **Confusion Matrix**
- **ROC-AUC Score**

---

## **Results and Insights**

- Students with higher parental education levels tend to perform better.
- Regular study habits and good attendance significantly improve performance.
- Certain socio-economic factors have a notable impact on student outcomes.

---

## **Usage**

To run the analysis or model training scripts, use the following commands:

```bash
# Run the data preprocessing pipeline
python src/data_preprocessing.py

# Perform exploratory data analysis
jupyter notebook notebooks/02_eda.ipynb

# Train and evaluate the machine learning model
python src/model_training.py
```

---

## **Contributing**

Contributions are welcome! If you would like to contribute to this project, please fork the repository and submit a pull request with your improvements.



