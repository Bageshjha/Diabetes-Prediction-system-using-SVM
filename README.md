# Diabetes-Prediction-system-using-SVM
This project is a machine learning model to predict whether a person is diabetic based on specific medical data inputs. It utilizes a Support Vector Machine (SVM) for classification, trained on the Pima Indian Diabetes dataset. The project includes model training, evaluation, and a user input system to allow for predictions based on new inputs.
#Dataset
The dataset used for this project is the Pima Indian Diabetes dataset, which contains several medical predictor variables and one target variable Outcome indicating if the patient has diabetes (1) or not (0).
#Model
Support Vector Machine (SVM) with a linear kernel is used to train the model.
The dataset is split into training and testing sets, with 80% of the data used for training and 20% for testing.
Data is standardized using StandardScaler to ensure that all features contribute equally to the model's performance.
#Evaluation
The model is evaluated based on accuracy metrics for both training and testing data:
Training Accuracy: Measures how well the model fits the training data.
Testing Accuracy: Measures the model's generalization on unseen data

#Predictive System
The predictive system allows for manual input of medical data to determine if the individual is likely to be diabetic or not. Sample inputs include:

Number of pregnancies
Glucose level
Blood pressure
BMI
Diabetes Pedigree Function
Age
The system standardizes the inputs and provides a prediction based on the trained model.

#User Input System
In addition to a predictive system for hardcoded input, the project features a user input system that accepts real-time input from users and provides predictions:

