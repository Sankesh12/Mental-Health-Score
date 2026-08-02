# 🧠 Student Mental Health Score Prediction

### An End-to-End Machine Learning Project for Predicting Student Mental Health Score using Social Media Usage, Lifestyle Habits, and Academic Information.

![Python](https://img.shields.io/badge/Python-3.13-blue?style=for-the-badge\&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge\&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-013243?style=for-the-badge\&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557C?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-4C72B0?style=for-the-badge)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?style=for-the-badge\&logo=scikitlearn)
![FastAPI](https://img.shields.io/badge/FastAPI-Backend-009688?style=for-the-badge\&logo=fastapi)
![Joblib](https://img.shields.io/badge/Joblib-Model%20Serialization-success?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-Frontend-E34F26?style=for-the-badge\&logo=html5)
![CSS3](https://img.shields.io/badge/CSS3-Styling-1572B6?style=for-the-badge\&logo=css3)
![JavaScript](https://img.shields.io/badge/JavaScript-Interactive-F7DF1E?style=for-the-badge\&logo=javascript)

---

# 📌 About the Project

- This project predicts a student's **Mental Health Score (0–10)** based on social media usage, academic performance, daily habits, and lifestyle factors.

- It is more than just a machine learning notebook. The project demonstrates a complete end-to-end machine learning workflow including data preprocessing, exploratory data analysis, feature engineering, model training, regression model comparison, evaluation, REST API development using FastAPI, and an interactive frontend developed with HTML, CSS, and JavaScript.

- The objective of this project is to show how machine learning can help analyze factors affecting student mental well-being and provide data-driven insights for educational institutions, researchers, and developers.

---

# ✨ Features

* 📊 Exploratory Data Analysis (EDA)

* 🧹 Data Cleaning and Preprocessing

* 🔄 Categorical Feature Encoding

* 🤖 Trained Multiple Machine Learning Models

* 📈 Regression Model Performance Comparison

* 🌳 Feature Analysis

* 🎯 Student Mental Health Score Prediction

* ⚡ REST API using FastAPI

* 💻 Interactive HTML, CSS & JavaScript Frontend

* 💾 Model Serialization using Joblib

* 🚀 Deployed on Vercel

---

# 🧪 Model Performance

Three regression models were trained and compared before selecting the final model.

| Model                         | Accuracy (R² Score) | Training R² |       MAE |      RMSE |
| ----------------------------- | ------------------: | ----------: | --------: | --------: |
| **Linear Regression**         |             **73%** |       0.724 |     0.536 |     0.676 |
| **Random Forest (Default)** ✅ |             **87%** |   **0.981** | **0.347** | **0.464** |
| **Random Forest (Tuned)**     |             **86%** |       0.955 |     0.369 |     0.487 |

### ✅ Final Model

**Random Forest Regressor (Default)**

It achieved the highest **R² Score (87.76%)**, along with the lowest MAE and RMSE, making it the most accurate and reliable model for predicting students' mental health scores on unseen data.

---

# 🛠️ Tech Stack

| Layer                | Technology                       |
| -------------------- | -------------------------------- |
| Programming Language | Python                           |
| Data Analysis        | Pandas, NumPy                    |
| Data Visualization   | Matplotlib, Seaborn              |
| Machine Learning     | Scikit-Learn                     |
| Models               | Linear Regression, Random Forest |
| Backend API          | FastAPI                          |
| Frontend             | HTML, CSS, JavaScript            |
| Model Serialization  | Joblib                           |

---

# 📂 Project Structure

```text
Student_Mental_Health_Score_Prediction/

│── model.pkl
│── mental_health_score.ipynb
│── main.py
│── index.html
│── style.css
│── script.js
│── Student Social Media And Mental Health Impact.csv
│── requirements.txt
│── README.md
```

---

# ⚙️ How It Works

1. Load the Student Social Media & Mental Health dataset.

2. Perform data cleaning and preprocessing.

3. Encode categorical variables.

4. Split the dataset into training and testing sets.

5. Train Linear Regression and Random Forest models.

6. Compare model performance using regression metrics.

7. Select the best-performing Random Forest model.

8. Save the trained model using Joblib.

9. Build a FastAPI backend for serving predictions.

10. Create an interactive frontend using HTML, CSS, and JavaScript.

11. User enters personal, academic, and lifestyle information.

12. The API predicts a **Mental Health Score (0–10)** instantly.

---

# 🚀 Run Locally

Clone the repository

```bash
git clone https://github.com/Sankesh12/Student_Mental_Health_Score_Prediction.git

cd Student_Mental_Health_Score_Prediction
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the FastAPI server

```bash
uvicorn main:app --reload
```

Open the frontend

```text
Open index.html in your browser
```

---

# 📊 Application Inputs

The application predicts mental health score using the following student information:

* Age

* Gender

* Country

* Academic Level

* Most Used Social Media Platform

* Purpose of Social Media Usage

* Average Daily Usage Hours

* Daily Phone Unlocks

* Study Hours

* Physical Activity Hours

* Sleep Hours Per Night

* Stress Level

---

# 📈 Prediction Output

The application displays

* 🧠 Predicted Mental Health Score (0–10)

* 📊 Wellness Indicator

* ⚡ Instant Prediction via FastAPI

Example

```text
Predicted Mental Health Score : 8.42 / 10
```

---

# 📊 Exploratory Data Analysis

The project includes

* Dataset Overview

* Statistical Summary

* Missing Value Analysis

* Duplicate Record Check

* Correlation Heatmap

* Mental Health Score Distribution

* Social Media Usage Analysis

* Stress Level Analysis

* Sleep Hours Distribution

* Study Hours Analysis

* Physical Activity Analysis

---

# 🌳 Feature Analysis

The model learns patterns from several important factors influencing student mental health.

Important features include:

* Stress Level

* Sleep Hours Per Night

* Average Daily Social Media Usage

* Physical Activity Hours

* Study Hours

* Daily Phone Unlocks

* Academic Level

* Most Used Platform

---

# 📈 Regression Evaluation Metrics

The model was evaluated using standard regression metrics:

* R² Score

* Mean Absolute Error (MAE)

* Root Mean Squared Error (RMSE)

These metrics demonstrate that the Random Forest model provides strong predictive performance and generalizes well to unseen student data.

---

# 💼 Key Insights

The analysis provides several valuable insights:

* Higher stress levels are associated with lower mental health scores.

* Students with sufficient sleep generally achieve better mental health scores.

* Excessive social media usage may negatively impact overall mental well-being.

* Physical activity contributes positively to mental wellness.

* Balanced study habits are associated with healthier mental health outcomes.

These insights can help educational institutions better understand student well-being and support data-driven decision making.

---

# 🧠 What I Learned

* Performing Exploratory Data Analysis (EDA)

* Data Cleaning and Preprocessing

* Feature Engineering

* Training and Comparing Regression Models

* Evaluating Regression Models

* Building REST APIs using FastAPI

* Saving and Loading Machine Learning Models

* Integrating Machine Learning with Frontend Applications

* Deploying Machine Learning Projects

---

# 🔮 Future Improvements

* Hyperparameter Optimization

* Cross Validation

* Pipeline Implementation

* Explainable AI (SHAP)

* Feature Selection

* Docker Deployment

* Cloud Deployment

* User Authentication

* Model Monitoring

---

# ⚠️ Disclaimer

This project is developed for educational and research purposes. The predicted mental health score is generated using historical data and machine learning techniques. It should not be considered a clinical diagnosis or a substitute for professional mental health advice.

---

# 📬 Connect With Me

If you found this project helpful, feel free to connect with me or provide your feedback.

<p align="left">

<a href="https://www.linkedin.com/in/sankeshlal/" target="_blank">
<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="https://github.com/Sankesh12" target="_blank">
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<a href="mailto:sankesh.lal12@gmail.com">
<img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

</p>

---

⭐ **If you found this project useful, consider giving it a star on GitHub. It motivates me to build and share more machine learning projects!**
