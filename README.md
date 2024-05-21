##AnomaData (Automated Anomaly Detection for Predictive Maintenance)
Description
AnomaData is a Streamlit application designed for automated anomaly detection in predictive maintenance tasks. It enables users to explore data, train machine learning models, and make predictions based on input features, streamlining the process of identifying anomalies in maintenance data.

Features
Data Viewer: Browse the dataset and inspect the first 100 rows.
Model Training: Train machine learning models using various algorithms, including Random Forest, Logistic Regression, XGBoost, LightGBM, and CatBoost.
Final Prediction: Input features to predict whether the data represents normal conditions or an anomaly.
Installation
Clone the repository:

bash
Copy code
git clone <repository_url>
cd AnomaData
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Run the Streamlit application:

bash
Copy code
streamlit run app.py
Usage
Select the desired option from the navigation sidebar:

Home: Welcome page.
Data Viewer: Inspect the dataset.
Model Training: Train machine learning models with selected algorithms.
Final Prediction: Make predictions by entering input features.
Follow the instructions on each page to interact with the application.

Dataset
The dataset used in this project is stored in AnomaData (1).xlsx.
Models
Trained machine learning models are saved as .sav files.
Contributing
We welcome pull requests and feedback. For major changes, please open an issue first to discuss what you would like to change.
