# 🎯 Student Score Predictor

An end-to-end Machine Learning web application that predicts a student's **Math Score** based on various personal, educational, and socio-economic factors. This project demonstrates the complete machine learning lifecycle—from data preprocessing and model training to deployment using a user-friendly web interface.

---

## 📌 Overview

The Student Score Predictor helps estimate a student's mathematics score by analyzing several input features such as gender, parental education, lunch type, test preparation course, and reading & writing scores.

The project follows a complete Machine Learning pipeline including:

* Data Collection
* Data Preprocessing
* Feature Engineering
* Model Training
* Model Evaluation
* Model Selection
* Web Application Deployment

---

## 🚀 Features

* 📊 Predicts student math scores instantly
* 🤖 Uses Machine Learning regression algorithms
* 🧹 Automated data preprocessing pipeline
* 📈 Compares multiple ML models and selects the best one
* 🌐 Simple and interactive web interface
* 💾 Saves trained model for future predictions

---

## 🛠️ Tech Stack

### Programming Language

* Python

### Machine Learning

* Scikit-learn
* CatBoost
* XGBoost
* Random Forest
* Decision Tree
* Gradient Boosting
* Linear Regression
* AdaBoost

### Data Processing

* Pandas
* NumPy

### Visualization

* Matplotlib
* Seaborn

### Web Framework

* Flask

### Model Serialization

* Pickle

### Others

* HTML
* CSS
* Git
* GitHub

---

## 📂 Project Structure

```text
score-predictor/
│
├── artifacts/
│   ├── model.pkl
│   ├── preprocessor.pkl
│
├── notebook/
│   ├── EDA.ipynb
│   ├── Model_Training.ipynb
│
├── src/
│   ├── components/
│   │   ├── data_ingestion.py
│   │   ├── data_transformation.py
│   │   ├── model_trainer.py
│   │
│   ├── pipeline/
│   │   ├── prediction_pipeline.py
│   │
│   ├── exception.py
│   ├── logger.py
│   ├── utils.py
│
├── templates/
│   └── home.html
│
├── app.py
├── requirements.txt
├── setup.py
└── README.md
```

---

## 📊 Dataset

The project uses the **Students Performance Dataset**, which contains information about students' backgrounds and academic performance.

### Input Features

* Gender
* Race/Ethnicity
* Parental Level of Education
* Lunch Type
* Test Preparation Course
* Reading Score
* Writing Score

### Target Variable

* Math Score

---

## ⚙️ Machine Learning Workflow

1. Data Ingestion
2. Data Cleaning
3. Feature Encoding
4. Data Transformation
5. Train-Test Split
6. Model Training
7. Model Evaluation
8. Best Model Selection
9. Model Serialization
10. Prediction using Flask Web App

---

## 📈 Models Evaluated

The following regression models were compared:

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor
* Gradient Boosting Regressor
* AdaBoost Regressor
* XGBoost Regressor
* CatBoost Regressor

The best-performing model was selected based on evaluation metrics.

---

## 📏 Evaluation Metrics

* R² Score
* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)

---

## 💻 Installation

Clone the repository

```bash
git clone https://github.com/VishnuVardhan1230/score-predictor.git
```

Move into the project directory

```bash
cd score-predictor
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
python app.py
```

Open your browser

```text
http://127.0.0.1:5000
```

---

## 🎯 How It Works

1. Open the application.
2. Enter the required student information.
3. Click the **Predict** button.
4. The trained model estimates the student's Math Score.
5. The predicted score is displayed instantly.

---

## 📸 Screenshots

Add screenshots of:

* Home Page
* Prediction Form
* Prediction Result

Example:

```text
screenshots/
├── home.png
├── prediction.png
├── result.png
```

---

## 🎓 Learning Outcomes

Through this project, I gained hands-on experience in:

* Data preprocessing
* Feature engineering
* Machine Learning model development
* Model comparison and evaluation
* Building reusable ML pipelines
* Flask web application development
* Model deployment concepts
* Git and GitHub version control

---

## 🔮 Future Improvements

* Deploy on Render or Railway
* Add user authentication
* Store prediction history
* Improve UI with Bootstrap or React
* Add data visualization dashboard
* Enable batch predictions using CSV uploads

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Added new feature"
```

4. Push your branch

```bash
git push origin feature-name
```

5. Create a Pull Request

---

## 👨‍💻 Author

**Vishnu Vardhan**

GitHub: https://github.com/VishnuVardhan1230

---

## ⭐ Support

If you found this project helpful, please consider giving it a ⭐ on GitHub.

It motivates me to build and share more Machine Learning projects.
