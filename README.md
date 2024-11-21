# Gas Purchase Predictor

The **Gas Purchase Predictor** is a Python-based machine learning application designed to predict the next gas purchase date for customers based on historical data and behavior. It features both a web interface and REST API, making it easy to use and integrate with external systems like a CRM.

## Features

- **Prediction Model**: Predicts the number of days until a customer's next gas purchase.
- **Web Interface**: User-friendly HTML form to input data and view predictions.
- **REST API**: Supports external systems to send and receive prediction data via HTTP.
- **Cylinder Weight Selection**: Provides predefined options (6kg, 13kg, 50kg) for accuracy and compliance.
- **Enhanced Insights**: Displays customer location and selected cylinder weight with prediction results.

## Technologies Used

- **Programming Language**: Python
- **Framework**: Flask (for web and REST API functionalities)
- **Machine Learning Library**: Scikit-learn
- **Data Manipulation**: Pandas, NumPy
- **Model Persistence**: Joblib
- **Frontend**: HTML, CSS
- **API Testing**: Postman

## Setup Instructions

### Prerequisites

1. Python 3.8 or higher.
2. Git for version control.
3. A virtual environment tool (like `venv`).

### Installation Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/bravonokoth/gas_purchase_predictor.git
   cd gas_purchase_predictor
