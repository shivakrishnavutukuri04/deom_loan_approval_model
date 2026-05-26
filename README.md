# deom_loan_approval_model
This is a basic Machine Learning project built using the K-Nearest Neighbors (KNN) Classifier to predict loan approval status.
# Loan Approval Prediction using KNN

This is a basic Machine Learning project built using the K-Nearest Neighbors (KNN) Classifier to predict loan approval status.

The main purpose of this project is to understand the basic Machine Learning pipeline, including:

* Data preprocessing
* Encoding
* Feature scaling
* Train-test splitting
* Model training
* Prediction

This project is beginner-friendly and focuses on learning how a classification model works in a real-world dataset using Scikit-learn.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn

## Algorithm Used

* KNN Classifier

## Goal

To understand the end-to-end workflow of a simple Machine Learning classification project.


Basic Steps to Build & Deploy a Streamlit Project

# Streamlit Project Setup & Deployment

## Step 1: Create Project Folder
```bash
mkdir loan_approval_project
cd loan_approval_project


Step 2: Create Virtual Environment
python -m venv venv
Activate Environment
Windows
venv\Scripts\activate
Mac/Linux
source venv/bin/activate
Step 3: Install Required Libraries
pip install streamlit pandas numpy scikit-learn
Step 4: Create Project Files
loan_approval_project/
│
├── app.py
├── model.pkl
├── requirements.txt
└── dataset.csv
Step 5: Train and Save Model

Train the KNN model and save it using Pickle.

import pickle

pickle.dump(model, open('model.pkl', 'wb'))
Step 6: Run Streamlit App
streamlit run app.py
Step 7: Create requirements.txt
pip freeze > requirements.txt
Step 8: Upload Project to GitHub
Initialize Git
git init
Add Files
git add .
Commit Files
git commit -m "Initial commit"
Connect GitHub Repository
git remote add origin YOUR_GITHUB_REPO_LINK
Push Code
git push -u origin main
Step 9: Deploy Streamlit App
Open Streamlit Cloud
https://share.streamlit.io
Login using GitHub
Click New App
Select:
GitHub Repository
Branch
app.py
Click Deploy

Your Streamlit application will be live with a public URL.

