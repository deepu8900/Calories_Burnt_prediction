# Calories_Burnt_prediction
🏋️‍♂️ Calorie Burnt Prediction

This project predicts the number of calories burnt during exercise based on user features such as gender, age, height, weight, duration, and heart rate.
The project uses Machine Learning models to learn from past data and make accurate predictions.

📌 Features

Preprocessing of dataset (handling categorical data, encoding gender).

Exploratory Data Analysis (EDA) with heatmaps and visualizations.

Feature scaling and train-test split.

Machine Learning model training & evaluation.

Performance metrics (Mean Absolute Error, Accuracy checks).

📂 Dataset

The dataset includes:

Gender: Male/Female

Age: Age of the person

Height: Height in cm

Weight: Weight in kg

Duration: Duration of exercise (minutes)

Heart Rate: Measured during workout

Body Temp: Temperature after exercise

Calories: Target value (calories burnt)

⚙️ Tech Stack

Python 3.10+

Libraries:

pandas – data manipulation

numpy – numerical operations

matplotlib, seaborn – data visualization

scikit-learn – machine learning (Label Encoding, train-test split, regression models, evaluation metrics)

🚀 Steps in Notebook

Load & Explore Data – Check missing values, data info, summary statistics.

Data Preprocessing – Encode categorical features (Gender), normalize numeric columns.

Exploratory Data Analysis (EDA) – Correlation heatmap, feature distributions.

Model Training – Train ML model (e.g., Linear Regression, Random Forest, etc.).

Evaluation – Calculate Mean Absolute Error (MAE) to measure accuracy.

Example result: MAE ≈ 0.59 (very good performance compared to target scale).

📊 Example Output

Correlation Heatmap


Model Performance

Mean Absolute Error: 0.5868

🏁 How to Run

Clone the repository

git clone https://github.com/your-username/calorie-burnt-prediction.git
cd calorie-burnt-prediction


Install dependencies

pip install -r requirements.txt


Open Jupyter Notebook

jupyter notebook Calorie_Burnt_Prediction.ipynb

📌 Future Improvements

Try advanced ML models (XGBoost, LightGBM).

Deploy as a Flask / FastAPI web app.

Build an interactive Streamlit dashboard for calorie prediction.
