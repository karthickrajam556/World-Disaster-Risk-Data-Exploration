# World-Disaster-Risk-Data-Exploration

# 🌍 Week 1 Project – Climate Risk and Disaster Management

## 📌 Project Title
**Data Exploration of the World Risk Index for Climate Risk and Disaster Management**


## 📖 Project Overview
This project focuses on exploring the **World Risk Index dataset**, which measures the exposure, vulnerability, susceptibility, coping capabilities, and adaptive capacities of countries facing natural hazards.  
The aim of this project is to understand the structure of the dataset, perform basic exploratory analysis, and prepare the foundation for deeper insights into climate risk and disaster management.


## 🗂️ Dataset
- **Name:** World Risk Index (WRI)  
- **Source:** Kaggle (Global Disaster Risk Index dataset)  
- **Rows:** ~1917  
- **Columns:** 12  
- **Key Features:**  
  - Region (Country/Location)  
  - World Risk Index (WRI)  
  - Exposure  
  - Vulnerability  
  - Susceptibility  
  - Lack of Coping Capabilities  
  - Lack of Adaptive Capacities  
  - Year  
  - Risk Categories  


## 🔎 Steps Performed
1. Imported necessary Python libraries (`pandas`, `numpy`, etc.).  
2. Loaded the dataset (`world_risk_index.csv`) into a Pandas DataFrame.  
3. Explored the dataset using:  
   - `.info()` → Checked column names, datatypes, and structure.  
   - `.describe()` → Summarized numerical statistics.  
   - `.isnull().sum()` → Identified missing values.  
4. Handled missing values by filling them with column means.  
5. Cleaned column names (removed leading/trailing spaces).  
6. Documented analysis flow with clear markdown headings.  


## 💡 Improvisations Done
- Handled missing values to improve dataset usability.  
- Cleaned column names for better readability and coding efficiency.  
- Structured the notebook for easy step-by-step understanding.  
- Added markdown explanations alongside outputs for clarity.  


## 📂 Repository Structure
├── AIML_Intern_Week1.ipynb # Jupyter Notebook with analysis
├── world_risk_index.csv # Dataset
└── README.md # Project documentation


