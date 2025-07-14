#  AI Crop Advisor
A Machine Learning project to recommend the **best crop** for farmers based on soil and weather conditions. It helps farmers make data-driven decisions to improve yield and profit.

## Dataset

Trained on `Crop_recommendation.csv`, which includes:

- Soil Nutrients: **Nitrogen (N)**, **Phosphorus (P)**, **Potassium (K)**
- Environmental Features: **Temperature**, **Humidity**, **Soil pH**, **Rainfall**
- Target Variable: **Recommended Crop**

## Models Used

-  Logistic Regression  
-  K-Nearest Neighbors (KNN)  
-  Decision Tree (**Best model**)

The Decision Tree model was chosen based on overall accuracy and stability.

##  How It Works

1. Performs data preprocessing and visual EDA.
2. Trains and compares multiple models.
3. Saves the **best model** and **LabelEncoder**.
4. Takes **user input** through console and gives **crop recommendation**.

##  Project Structure

AI_Crop_Advisor/
├── data/ # Dataset
│ └── Crop_recommendation.csv
│
├── models/ # Saved models
│ ├── best_model_DecisionTree.pkl
│ └── label_encoder.pkl
│
├── notebooks/ # Notebooks for EDA, training, and prediction
│ ├── data_preprocessing_01.ipynb
│ ├── Crop_Advisor_Model_Training.ipynb
│ └── Crop_Advisor_Predictor.ipynb
│
├── outputs/ # Graphs and comparison reports
│ └── model_accuracy_comparison.png
│
├── .gitignore
├── README.md
└── requirements.txt
