# Employee Salary Prediction

This project is a machine learning application that predicts whether an employee earns more than $50K based on various demographic features. The application is built using Streamlit and utilizes a trained model to make predictions.

## Project Structure

```
employee-salary-prediction
├── app.py                # Streamlit application code
├── best_model.pkl        # Serialized best-performing model
├── data
│   └── adult 3.csv      # Dataset used for training
├── src
│   ├── preprocess.py     # Data preprocessing code
│   └── train.py          # Model training code
├── requirements.txt      # Project dependencies
└── README.md             # Project documentation
```

## Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd employee-salary-prediction
   ```

2. **Install the required packages:**
   It is recommended to create a virtual environment before installing the dependencies.
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Streamlit application:**
   ```bash
   streamlit run app.py
   ```

4. **Access the application:**
   Open your web browser and go to `http://localhost:8501` to access the application.

## Usage

- Input employee details such as age, education level, job role, hours worked per week, and years of experience in the sidebar.
- Click on the "Predict Salary Class" button to get the prediction.
- You can also upload a CSV file for batch predictions.

## Model Training

The model is trained using the dataset located in the `data` directory. The training process includes data preprocessing, model selection, and evaluation. The best model is saved as `best_model.pkl` for use in the Streamlit application.

## Dependencies

- pandas
- scikit-learn
- Streamlit

Ensure that all dependencies are installed to run the application successfully.