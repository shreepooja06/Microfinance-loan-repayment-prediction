# Microfinance-loan-repayment-prediction
A machine learning-based system that predicts whether a borrower will repay a microfinance loan within 5 days. The project includes data preprocessing, model training, evaluation, and a Streamlit web app for real-time prediction to support microfinance institutions in reducing default risk.
This project predicts whether a borrower will repay a microfinance loan within 5 days using Machine Learning.  
It helps microfinance institutions reduce loan default risks and make informed lending decisions.

---

## Features
- User-friendly Streamlit web interface
- Loan repayment prediction based on borrower input
- Dataset visualization and insights
- Comparison of multiple ML models (Precision, Recall, Log Loss)

---

## Technologies Used
- Python
- Streamlit
- Pandas, NumPy
- Scikit-Learn
- XGBoost
- LightGBM
- Matplotlib, Seaborn

---

## REQUIREMENTS TO RUN THIS PROJECT:
Python (Version 3.8 or above)
Required Python Libraries:
   - streamlit
   - pandas
   - numpy
   - matplotlib
   - seaborn
   - scikit-learn
   - xgboost
   - lightgbm

Dataset File (CSV)
   The dataset used must be placed in the project folder.

----------------------------------------------------------
## INSTALLATION STEPS:
Step 1: Install Python in your system (if not already installed)

Step 2: Open Command Prompt or Terminal in the project folder.

Step 3: Install all required libraries by running the command:
       pip install -r requirements.txt
   (If requirements.txt is not provided, install manually using:
       pip install streamlit pandas numpy matplotlib seaborn scikit-learn xgboost lightgbm)

Step 4: Make sure the dataset path inside the code is correct.
   Currently the code uses:
       D:/microfinance_app/Micro-credit-Data-file.csv
   If your dataset is stored in another location, change this line in code:
       file_path = "D:/microfinance_app/Micro-credit-Data-file.csv"
   to:
       file_path = "your_dataset_path_here.csv"

Step 5: Save changes (if dataset path was edited)

----------------------------------------------------------
## HOW TO RUN THE PROJECT:
Step 1: Open Command Prompt / Terminal.
Step 2: Navigate to the project folder using the command:
       cd <Your Project Folder Path>

Step 3: Run the Streamlit Application using:
       streamlit run <filename>.py
   Example:
       streamlit run app.py
       (Replace app.py with your actual python file name)

Step 4: The application will open automatically in your default web browser.

----------------------------------------------------------
## PROJECT INTERFACE FEATURES:
Home Page - Overview of the project
About Page - Purpose and objective of the project
Prediction - User inputs borrower details and sees repayment prediction
Results - Shows dataset view, heatmap, and model performance comparison
Contact - Project member details

----------------------------------------------------------
## NOTES:
Ensure dataset CSV file location is correct before running.
Make sure images used in Home/About/Contact pages are available in the correct path.
Use stable internet connection if using online libraries.

----------------------------------------------------------
## PROJECT DEVELOPERS:
POOJASHREE K
PRAISY V

## GUIDED BY: Mrs.M.C.VINMATHI

## DEMO VIDEO
https://drive.google.com/file/d/1bDxpy_6e2W8fSbi0bKMFWBPXwcIsKG26/view?usp=drive_link
