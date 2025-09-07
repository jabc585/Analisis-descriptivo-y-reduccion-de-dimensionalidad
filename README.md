# Heart Failure Clinical Records EDA with PCA

## 📋 Project Overview
This project performs an Exploratory Data Analysis (EDA) and Principal Component Analysis (PCA) on clinical records of heart failure patients. The dataset includes various clinical features and aims to identify patterns and risk factors associated with heart failure mortality.

## 🏥 Dataset Description
The dataset contains 299 patient records with the following variables:

| Variable Name | Role | Type | Demographic | Description | Units | Missing Values |
|---------------|------|------|-------------|-------------|-------|---------------|
| age | Feature | Integer | Age | Patient age | years | no |
| anaemia | Feature | Binary |  | Decrease of red blood cells or hemoglobin |  | no |
| creatinine_phosphokinase | Feature | Integer |  | Level of CPK enzyme in blood | mcg/L | no |
| diabetes | Feature | Binary |  | Indicates if patient has diabetes |  | no |
| ejection_fraction | Feature | Integer |  | Percentage of blood expelled from heart per contraction | % | no |
| high_blood_pressure | Feature | Binary |  | Indicates if patient has hypertension |  | no |
| platelets | Feature | Continuous |  | Platelets in blood | kiloplatelets/mL | no |
| serum_creatinine | Feature | Continuous |  | Level of serum creatinine in blood | mg/dL | no |
| serum_sodium | Feature | Integer |  | Level of serum sodium in blood | mEq/L | no |
| sex | Feature | Binary | Sex | Woman or man |  | no |
| smoking | Feature | Binary |  | Indicates if patient smokes |  | no |
| time | Feature | Integer |  | Patient follow-up time | days | no |
| DEATH_EVENT | Target | Binary |  | Indicates if patient died during follow-up |  | no |

## 🎯 Objectives
1. Perform comprehensive exploratory data analysis
2. Identify key clinical factors influencing heart failure mortality
3. Visualize relationships between variables
4. Conduct Principal Component Analysis to reduce dimensionality
5. Prepare data for predictive modeling

## 📊 Methodology
1. **Data Loading & Initial Inspection**
   - Import and examine dataset structure
   - Check for missing values and data types

2. **Exploratory Data Analysis**
   - Statistical summaries of numerical variables
   - Distribution analysis of categorical variables
   - Correlation analysis between features

3. **Data Visualization**
   - Histograms with KDE plots for numerical variables
   - Analysis of mean and median values
   - Comparative analysis between survival groups

4. **Principal Component Analysis**
   - Data standardization
   - PCA implementation
   - Visualization of principal components

## 🛠️ Technologies Used
- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Plotly

## 📈 Key Findings
- Serum creatinine and ejection fraction identified as most significant risk factors
- Age and time show important relationships with mortality
- PCA successfully reduced dimensionality while preserving variance

## 🚀 How to Run
1. Clone the repository
2. Install required dependencies: `pip install -r requirements.txt`
3. Run the Jupyter notebook: `jupyter notebook Proyecto_3_EDA.ipynb`

## 📁 Repository Structure
```
├── Proyecto_3_EDA.ipynb  # Main analysis notebook
├── H.csv                 # Dataset (not included in repo)
├── requirements.txt      # Python dependencies
└── README.md            # Project documentation
```

## ⚠️ Note
The dataset file `H.csv` is not included in this repository due to privacy considerations. Users should obtain the dataset from the original source or contact the repository maintainer for access instructions.

## 📄 License
This project is for educational purposes. Please ensure proper attribution if using the code or methodology.
