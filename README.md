# Student Performance Prediction using ANN

## Project Overview
This project uses an Artificial Neural Network (ANN) to predict students' final mathematics grades based on academic and study-related features.

## Dataset
Student Performance Data Set by UCI, obtained from Kaggle.

Dataset: https://www.kaggle.com/dskagglemt/student-performance-data-set

## Technologies Used
- Python
- Google Colab
- TensorFlow/Keras
- Pandas and NumPy
- Matplotlib
- Scikit-learn

## Input Features
- Study time
- Previous failures
- Absences
- First-period grade (G1)
- Second-period grade (G2)

## Target Variable
Final mathematics grade (G3), ranging from 0 to 20.

## Methodology
1. Load and explore the dataset.
2. Select input features and the target variable.
3. Split data into training and testing sets.
4. Standardize input features.
5. Build an ANN with two hidden layers.
6. Train the model.
7. Evaluate using MAE, MSE, RMSE and R².
8. Visualize training loss and predicted versus actual grades.
9. Predict a new student's final grade.

## How to Run
1. Open the `.ipynb` notebook in Google Colab.
2. Download the dataset from the Kaggle link above.
3. Upload `student-mat.csv` when prompted.
4. Run the notebook cells in order.

## Disclaimer
This project is for educational purposes. Predictions are estimates and should not be treated as definitive assessments of student ability.
