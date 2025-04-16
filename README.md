# Disease Prediction Web App

This is a machine learning-powered web application designed to predict diseases like **Diabetes**, **Heart Disease**, and **Parkinson's** based on user input. The web app utilizes pre-trained models and Streamlit for the frontend to provide users with quick and reliable predictions.

## Features

- **Diabetes Prediction**: Predict whether a person has diabetes based on various health indicators such as glucose level, blood pressure, and BMI.
- **Heart Disease Prediction**: Predict the likelihood of heart disease based on input features like age, sex, blood pressure, and cholesterol levels.
- **Parkinson's Disease Prediction**: Predict whether a person has Parkinson's disease based on speech features such as jitter and shimmer.

## Technologies Used

- **Python**: Programming language used to build the backend.
- **Streamlit**: Framework for building the web interface.
- **Scikit-learn**: Library for building machine learning models.
- **Pickle**: Library to load pre-trained models.

## Requirements

- Python 3.x
- Streamlit
- Scikit-learn
- Pickle

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/jiyanshuj/Prediction-of-Disease
    ```

2. **Navigate into the project directory**:
    ```bash
    cd Prediction-of-Disease
    ```

3. **Create and activate a virtual environment** (optional but recommended):

    - On Windows:
      ```bash
      python -m venv venv
      .\venv\Scripts\activate
      ```

    - On Mac/Linux:
      ```bash
      python -m venv venv
      source venv/bin/activate
      ```

4. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

5. **Run the application**:
    ```bash
    streamlit run app.py
    ```

    After running this command, the app will be available in your browser at `http://localhost:8501`.

## Usage

1. Select a prediction model from the sidebar:
   - **Diabetes Prediction**
   - **Heart Disease Prediction**
   - **Parkinson's Prediction**

2. Enter the required input features (e.g., age, glucose level, blood pressure, etc.) in the respective fields.

3. Click the "Test Result" button to get the prediction.

4. The app will display the diagnosis based on the selected model.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

- **Jiyanshu**
- LinkedIN: [https://www.linkedin.com/in/jiyanshu-jain/]
  GitHub: [https://github.com/jiyanshuj]
#
