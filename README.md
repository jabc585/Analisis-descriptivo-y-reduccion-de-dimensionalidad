#Heart Failure Clinical Records EDA with PCA
📋 Project Overview
This project performs an Exploratory Data Analysis (EDA) and Principal Component Analysis (PCA) on clinical records of heart failure patients. The dataset includes various clinical features and aims to identify patterns and risk factors associated with heart failure mortality.

🏥 Dataset Description
The dataset contains 299 patient records with the following variables:

age: Age of the patient (years)

anaemia: Presence of anemia (binary)

creatinine_phosphokinase: CPK enzyme level (mcg/L)

diabetes: Presence of diabetes (binary)

ejection_fraction: Percentage of blood leaving the heart per contraction (%)

high_blood_pressure: Presence of hypertension (binary)

platelets: Platelet count in blood (kiloplatelets/mL)

serum_creatinine: Serum creatinine level (mg/dL)

serum_sodium: Serum sodium level (mEq/L)

sex: Gender (binary: woman or man)

smoking: Smoking status (binary)

time: Follow-up period (days)

DEATH_EVENT: Target variable - whether the patient died during follow-up (binary)

🎯 Objectives
Perform comprehensive exploratory data analysis

Identify key clinical factors influencing heart failure mortality

Visualize relationships between variables

Conduct Principal Component Analysis to reduce dimensionality

Prepare data for predictive modeling

📊 Methodology
Data Loading & Initial Inspection

Import and examine dataset structure

Check for missing values and data types

Exploratory Data Analysis

Statistical summaries of numerical variables

Distribution analysis of categorical variables

Correlation analysis between features

Data Visualization

Histograms with KDE plots for numerical variables

Analysis of mean and median values

Comparative analysis between survival groups

Principal Component Analysis

Data standardization

PCA implementation

Visualization of principal components

🛠️ Technologies Used
Python 3

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Plotly

📈 Key Findings
Serum creatinine and ejection fraction identified as most significant risk factors

Age and time show important relationships with mortality

PCA successfully reduced dimensionality while preserving variance

🚀 How to Run
Clone the repository

Install required dependencies: pip install -r requirements.txt

Run the Jupyter notebook: jupyter notebook Proyecto_3_EDA.ipynb

📁 Repository Structure
text
├── Proyecto_3_EDA.ipynb  # Main analysis notebook
├── H.csv                 # Dataset (not included in repo)
├── requirements.txt      # Python dependencies
└── README.md            # Project documentation
⚠️ Note
The dataset file H.csv is not included in this repository due to privacy considerations. Users should obtain the dataset from the original source or contact the repository maintainer for access instructions.

📄 License
This project is for educational purposes. Please ensure proper attribution if using the code or methodology.

