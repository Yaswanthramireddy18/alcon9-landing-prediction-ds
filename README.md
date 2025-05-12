# 🚀 Falcon 9 Landing Prediction (Capstone Project)

## 🧠 Project Overview
This project aims to predict whether the **first stage of the Falcon 9 rocket** will successfully land or not. The ability to recover and reuse rocket stages significantly reduces launch costs. **SpaceX** lists Falcon 9 launches at **$62 million**, while competitors charge upwards of **$165 million**.  
Knowing the likelihood of a successful landing can help estimate the **true cost of a launch** — a key advantage for competitors or clients in the growing commercial space sector.

As a **fictional data scientist at "Space Y"** (a competitor to SpaceX, founded by billionaire *Allon Musk*), you're tasked with using public data and machine learning to predict landing outcomes and estimate launch costs. This project is part of the IBM Data Science Professional Certificate.

> ✨ *Please note: This project and its scenario are fictional and were completed as part of an AI-generated educational exercise. The content is structured to resemble a real-world application, but is intended for learning purposes only.*

---

## 📚 Learning Objectives

- Manipulate and clean real-world launch data using Python and Pandas  
- Access and process JSON data from a REST API  
- Use web scraping to collect supplementary data from Wikipedia  
- Perform exploratory data analysis (EDA) using visual tools  
- Apply machine learning models to solve a binary classification problem  
- Build an interactive dashboard for predictions and insights  

---

## 🛰 Data Sources

- [SpaceX REST API](https://api.spacexdata.com/v4/)
- Wikipedia Falcon 9 Launch History pages
- Pre-cleaned datasets from Kaggle and provided materials

---

## 📈 Project Workflow

1. **Data Collection**  
   - Gathered using SpaceX’s public API  
   - Web scraping from Wikipedia tables for extra details  

2. **Data Wrangling & Preparation**  
   - Flattening nested JSON  
   - Handling nulls and missing values  
   - Filtering out irrelevant data (e.g., Falcon 1 launches)

3. **Exploratory Data Analysis (EDA)**  
   - Understanding how features like payload, orbit, and site affect landings  
   - Visualization using `matplotlib`, `seaborn`, and `plotly`

4. **Machine Learning Modeling**  
   - Models used: Logistic Regression, Random Forest, SVM, XGBoost  
   - Target: Predict if the rocket first stage will land (1) or not (0)  
   - Evaluated using Accuracy, F1 Score, and Confusion Matrix  

5. **Cost Estimation Logic**  
   - If landing = success ➝ estimated cost ≈ **$62M**  
   - If landing = failure ➝ estimated cost ≈ **$165M**

6. **Interactive Dashboard (Optional)**  
   - Built using `Streamlit` or `Plotly Dash`  
   - Input parameters, model predictions, and launch cost estimation

---

## 🧾 Key Features

- 🧠 Machine Learning-based prediction of Falcon 9 first-stage landing  
- 💰 Cost estimation based on landing outcome  
- 📊 Interactive data visualizations and insights  
- 🔍 Real-world data wrangling, modeling, and storytelling

---

## 🤝 Contributors

This capstone project was developed as part of the **IBM Data Science Professional Certificate**.  
I’m working as a **fictional data scientist** for the project scenario — this is an **AI-generated learning exercise** that simulates a real-world data science task.  

Special thanks to **Joseph Santarcangelo**, **Yan Luo**, and **Azim Hirjani**, the instructors who guided this learning journey.

---

## 📂 Project Structure

```
alcon9-landing-prediction-ds/
├── data/                   # Collected and cleaned datasets
├── notebooks/              # Jupyter notebooks for each project stage
├── models/                 # Trained model files (optional)
├── dashboard/              # Streamlit or Dash app (optional)
├── utils/                  # Helper scripts and functions
└── README.md               # Project documentation
```

---

## 💡 Final Thoughts

This project combines **real-world datasets**, **data wrangling**, and **machine learning** to solve a business-relevant problem in the commercial space sector. While fictional, the process reflects practical steps taken in real data science work.
