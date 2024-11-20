
Fraud Detection and FastAPI Deployment:

Overview

This project aims to develop a fraud detection model using machine learning algorithms and deploy it through a FastAPI application. The goal is to predict fraudulent transactions based on the 
provided dataset, which includes features like transaction amount, time, and several other variables.

The fraud detection model leverages techniques to handle imbalanced data, and once trained, it is deployed using FastAPI for real-time predictions via a web service.

🚀 Project Features
Machine Learning Models:

Utilizes models such as Random Forest, Logistic Regression, and XGBoost to identify fraudulent transactions.

Achieved high accuracy and robustness even with imbalanced data using techniques like SMOTE and cross-validation.

FastAPI Deployment:

A RESTful API for real-time predictions.

Exposes endpoints that can receive transaction data and return fraud predictions.

End-to-End Pipeline:

Data preprocessing

Model training and evaluation

FastAPI deployment

Unbalanced Data Handling:

Addressed class imbalance through data resampling and performance metrics tailored for imbalanced datasets.

📊 Dataset

The dataset used for fraud detection includes the following features:

V1 to V28: Transaction features generated using PCA.

Amount: The transaction amount.

Time: The time of the transaction.

Class: Target variable (1 for fraud, 0 for non-fraud).

Data Preprocessing:

Data cleaning (handling missing values).

Feature scaling and normalization.

Addressing class imbalance.

⚙️ Installation & Setup

Prerequisites

Python 3.7+

Install the required libraries:

pip install -r requirements.txt

Running the API

Clone the repository:

git clone https://github.com/yourusername/fraud-detection-fastapi.git

cd fraud-detection-fastapi

Start the FastAPI server:

Copy code

uvicorn main:app --reload

The API will be running at http://127.0.0.1:8000.

🧪 Model Performance

The model achieved an accuracy of 97% using Random Forest Classifier. Precision, recall, and F1-score metrics were also optimized for imbalanced class distribution.

📝 Notes

The project includes an end-to-end solution for training, testing, and deploying the fraud detection model.

Future improvements can include adding additional models, fine-tuning, and handling more complex deployment scenarios such as cloud integration.

🔧 Technologies Used

Machine Learning: Random Forest, XGBoost, Logistic Regression

FastAPI: For building and deploying the API

SMOTE: For handling class imbalance

Pandas & Scikit-learn: For data manipulation and model training

Uvicorn: As an ASGI server to run the FastAPI app

🤝 Contributing

Feel free to fork the repository, submit issues, or send pull requests if you'd like to contribute to improving the project.

📬 Contact

For any inquiries or suggestions, please contact meryemabid2310@gmail.com.
