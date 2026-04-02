# DS_Capstone
Repository for Applied Data Science Capstone

## SpaceX Falcon 9 Landing Prediction

### Project Overview
The objective of this project is to build a prediction model which allows us to answer the key question: Will the first stage land successfully or not?

### Project/Repository Structure
* **Project_Report** - Project deliverables (pdf and pptx)  
* **01_jupyter-labs-spacex-data-collection-api-v2.ipynb** - Data Collection from SpaceX API, including part of Data Wrangling  
* **02_jupyter-labs-webscraping.ipynb** - Data Collection from Wikipedia  
* **03_labs-jupyter-spacex-Data wrangling.ipynb** - Data Wrangling and a part of EDA  
* **04_edadataviz.ipynb** - EDA visualizations, including Features Engineering (One-Hot Encoding)  
* **05_jupyter-labs-eda-sql-coursera_sqllite.ipynb** - EDA with SQL  
* **06_lab_jupyter_launch_site_location.ipynb** - Geospatial visual analytics with Folium  
* **07_spacex-dash-app_Submitted.py** - Interactive Launch Performance Dashboard with Plotly Dash  
* **08_SpaceX-Machine-Learning-Prediction-Part-5-v1.ipynb** - Predictive Analysis - Machine Learning Classification models with Scikit-Learn  
---
#### **Project Technical Optimization & Advanced Analysis**
* **09_SpaceX-Machine-Learning-Prediction-Part-5-v1_Enhanced.ipynb** - Technical enhancements beyond the baseline workflow::  
    * Class distribution: Analyzed class imbalance and implemented Class Weights to improve minority class recall  
    * Data leakeage: Corrected StandardScaler implementation to prevent data leakage (fit_transform on X_train, transform on X_test)  
    * Cross-Validation: Optimized CV strategy (k=[5, 10]) specifically for small dataset ($n=90$).  
    * Expanded Model Set: Integrated Ensemble Models (Random Forest and XGBoost)  
    * Advanced Evaluation: Utilized Classification Report for the best performing model (XGBClassifier)  
    * Included time measurement for Ensemble Models
