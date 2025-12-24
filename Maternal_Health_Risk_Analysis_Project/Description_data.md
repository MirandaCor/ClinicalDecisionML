The Maternal Health Risk Dataset is a real-world dataset sourced from rural clinics and hospitals in Bangladesh via IoT-based monitoring systems. It is publicly available through the UCI Machine 
Learning Repository and is commonly used for maternal risk classification research in low-resource healthcare settings.

Features
Age SystolicBP (Systolic blood pressure) 
DiastolicBP (Diastolic blood pressure) 
BS (Blood Sugar level) 
BodyTemp (Body temperature in °F) 
HeartRate (Beats per minute)

Target
RiskLevel: Binary classification (1 = high risk, 0 = low risk)
For this project, you'll work with a modified version of this dataset, called Maternal_Health_Risk_Data_Set_Modified.csv

Activities

1️- Prepare and clean the dataset
Load and clean the dataset, handle missing values, and normalize it for modeling.
2️- Build and evaluate a supervised patient risk scoring model Train a supervised model to predict patient risk, evaluate its performance, and save the trained model. 
3️- Develop and assess a dense neural network model Build and train a dense neural network for the same prediction task and save the model. 
4️- Create and test a Gradio-based web application Create a web app for doctors to input patient data and get instant risk predictions using your trained models
