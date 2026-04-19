# LA Crime Intelligence & Prediction Engine 🚔

A machine learning project designed to analyze and predict crime types across Los Angeles using over **1 million rows** of historical data (2020-Present).

## 🚀 Overview
This repository contains a full data science pipeline, from exploratory data analysis to a tuned predictive model. The goal is to identify patterns in criminal activity and predict the most likely crime type based on location, time, and demographics.

## 📊 Key Results
* **Data Scale:** Processed and cleaned a dataset of **1,000,000+ records**.
* **Model Accuracy:** Achieved a validated accuracy of **33.78%** using an optimized Random Forest Classifier.
* **Optimization:** Utilized `GridSearchCV` to find the best hyperparameters (`max_depth: 15`, `n_estimators: 100`) while managing significant memory constraints.
* **Feature Importance:** Identified that **Location (Premise)** and **Time of Day (Hour)** are the strongest predictors of crime categories.

## 🛠️ Technical Stack
- **Language:** Python
- **Environment:** Jupyter Notebook / Anaconda
- **Libraries:** Pandas, Scikit-Learn, Seaborn, Matplotlib, Joblib
- **Techniques:** Hyperparameter Tuning, Label Encoding, Geospatial Visualization

## 📂 Project Structure
- `dataanalytics.ipynb`: Full analysis, data cleaning, and model training steps.
- `crime_label_encoder.pkl`: The saved encoder used to translate categorical data for the model.
- `README.md`: Project documentation.

## ⚠️ Important Note on the Model
The final trained Random Forest model (`la_crime_predictor_best.pkl`) is approximately **1.45 GB** in size, which exceeds GitHub's file storage limits. 
- The model is **excluded** from this repository to ensure stability.
- You can recreate the model by running the `dataanalytics.ipynb` notebook locally.
- A cloud download link for the pre-trained model is available upon request.

## 📜 License
This project is licensed under the **MIT License** - see the LICENSE file for details.

---
**Developed by Arinda Deogracious** *Data Science & AI Student | Founder-Builder*
