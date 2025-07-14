AI Crop Advisor



A machine learning project to recommend the "best crop" for farmers based on soil and weather data.



Dataset

Trained on `Crop\_recommendation.csv`, which includes:

\- Nitrogen (N), Phosphorus (P), Potassium (K)

\- Temperature, Humidity, pH

\- Rainfall



&nbsp;Models Used

\- Logistic Regression

\- K-Nearest Neighbors (KNN)

\- Decision Tree ( Best Model)



How It Works

1\. Trains and compares multiple models.

2\. Saves the best model + label encoder.

3\. Accepts user input and gives crop recommendation.

&nbsp;

Project Structure

AI\_Crop\_Advisor/

├── data/

│   └── Crop\_recommendation.csv

├── models/

│   └── best\_model\_DecisionTree.pkl

│   └── label\_encoder.pkl

├── notebooks/

│   └── data\_preprocessing\_01.ipynb

│   └── Crop\_Advisor\_Model\_Training.ipynb

│   └── Crop\_Advisor\_Predictor.ipynb

├── outputs/

│   └── model\_accuracy\_comparison.png

├── README.md

├── .gitignore        



