# Insurance_Premium_Prediction-ML
\

This project is a simple Machine Learning application that predicts outcomes based on **Height and Weight data**.  
It demonstrates the complete ML workflow including data preprocessing, model training, evaluation, and model saving using pickle.

---

## Project Overview

The goal of this project is to:
- Load height and weight data
- Perform data preprocessing
- Train a machine learning model
- Save the trained model as a `.pkl` file
- Use the saved model for predictions

This project is beginner-friendly and suitable for academic submission and resume projects.



## Project Structure

├── MyProject.ipynb # Jupyter Notebook with full ML code
├── dataset.xlsx # Dataset (Height & Weight data)
├── rf_model.pkl # Trained Machine Learning model
├── README.md # Project documentation



---

##  Machine Learning Workflow

1. Data Collection (Excel file)
2. Data Exploration & Cleaning
3. Feature Selection
4. Model Training
5. Model Evaluation
6. Model Serialization using Pickle
7. Prediction using saved model

---

##  Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Pickle

---

##  Dataset Details

- **Input Features:** Height, Weight  
- **Target Variable:** Depends on the prediction goal (classification or regression)

Dataset is stored in `.xlsx` format for easy understanding and modification.

---

##  How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/prajakta421/Insurance_Premimum_Prediction.git

2. Open the Google Colab:

jupyter notebook MyProject.ipynb


3. Run all cells step by step.


import pickle

with open('rf_model.pkl', 'rb') as file:
    model = pickle.load(file)

prediction = model.predict([[height, weight]])
print(prediction)


