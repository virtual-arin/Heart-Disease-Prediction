# Heart Disease Prediction

## Description
The **Heart Disease Prediction** is a machine learning-based web application that predicts the likelihood of a person having heart disease based on their medical attributes. It utilizes a pre-trained Logistic Regression model developed after thorough exploratory data analysis, data cleaning, and feature engineering. Users can interact with a simple and intuitive UI to input details like age, cholesterol, resting blood pressure, max heart rate, and chest pain type to get an instant prediction.

## Technologies Used
* Python
* Streamlit
* Pandas
* NumPy
* Scikit-Learn
* Joblib
* Matplotlib
* Seaborn
* Jupyter Notebook

## How to Run
1. Ensure you have Python installed on your system.
2. Install the required libraries using: `pip install pandas streamlit joblib scikit-learn`
3. Make sure the model files (`Logistic-Regression.pkl`, `scaler.pkl`, and `columns.pkl`) are in the same directory as `app.py`.
4. Run the Streamlit app using the command: `streamlit run app.py`

## Future Scope
* **Model Optimization**: Experiment with and integrate more complex algorithms (e.g., Random Forest, XGBoost, or Neural Networks) to potentially improve the accuracy score (currently ~86.4%).
* **Expanded Dataset**: Train the model on a larger, more diverse medical dataset to improve generalizability and reduce potential biases.
* **Detailed Health Insights**: Provide users with a detailed health report and lifestyle recommendations based on the specific inputs contributing to their risk score.
* **User Authentication**: Add a login system for users to save their history and track their heart health predictions over time.