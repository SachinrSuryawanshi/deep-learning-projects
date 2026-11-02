# Customer Churn Prediction using Artificial Neural Network (ANN)

## About the Project

This project uses an Artificial Neural Network (ANN) to predict whether a customer is likely to leave a bank or continue using its services.

The model is trained on customer information and uses the learned patterns to classify customers into two categories: churn or not churn.

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- TensorFlow / Keras
- Scikit-learn
- Streamlit
- Joblib / Pickle

## Project Structure

```text
01-ANN/
│
├── app.py
├── ann_implementation.ipynb
├── Churn_Modelling.csv
├── model.h5
├── label.pkl
├── scaler.pkl
├── onehot_encoder_geo.pkl
├── requirements.txt
├── logs/
└── README.md
```

## Project Workflow

1. **Data Loading:** Load the customer churn dataset using Pandas.
2. **Data Preprocessing:** Handle categorical variables and prepare the dataset for training.
3. **Feature Scaling:** Apply feature scaling to bring numerical features into a suitable range.
4. **Model Building:** Build an Artificial Neural Network using TensorFlow and Keras.
5. **Model Training:** Train the ANN model using the prepared dataset.
6. **Model Evaluation:** Evaluate the model's performance on test data.
7. **Model Saving:** Save the trained model and preprocessing objects.
8. **Web Application:** Use Streamlit to create an interface for making customer churn predictions.

## How to Run the Project

### 1. Clone the Repository

```bash
git clone <your-repository-url>
```

### 2. Navigate to the Project Folder

```bash
cd deep-learning-projects/01-ANN
```

### 3. Create a Virtual Environment

```bash
python -m venv .venv
```

### 4. Activate the Virtual Environment

**Windows:**

```bash
.venv\Scripts\activate
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

### 6. Run the Streamlit Application

```bash
streamlit run app.py
```

The application will open in your browser, where you can enter customer details and get a churn prediction.

## Model Artifacts

The following files are saved for making predictions:

- `model.h5` – Trained ANN model.
- `scaler.pkl` – Feature scaling object.
- `onehot_encoder_geo.pkl` – One-hot encoder for geographical information.
- `label.pkl` – Saved label preprocessing object.

## Objective

The objective of this project is to apply deep learning concepts to a real-world classification problem and understand how an Artificial Neural Network can be used for customer churn prediction.

## Author

**Sachin Suryawanshi**