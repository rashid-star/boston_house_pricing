# 🏠 Boston House Price Prediction (ML Deployment Project)

A complete end-to-end Machine Learning project that predicts Boston house prices based on user input features.
This project includes model training, web deployment, Docker containerization, and live hosting on Render.

---

## 🚀 Live Demo

**Docker Deployment:**
https://boston-docker.onrender.com/

**Normal Deployment:**
https://boston-house-pricing-duay.onrender.com/

---

## 📌 Project Overview

This project predicts house prices using Linear Regression based on various housing features such as crime rate, number of rooms, pollution level, and more.

It demonstrates a complete ML workflow:

* Data preprocessing
* Model training
* Model serialization
* Web app integration
* Docker containerization
* Cloud deployment

---

## 🧠 Tech Stack

* Python
* Scikit-learn
* Pandas & NumPy
* Flask
* HTML/CSS
* Docker
* Render (Cloud deployment)
* Gunicorn

---

## ⚙️ ML Workflow

1. Data cleaning and preprocessing
2. Feature selection
3. Model training using Linear Regression
4. Model evaluation (R² score)
5. Saving model using Pickle
6. Web app created with Flask
7. User input → prediction → output
8. Deployment on Render
9. Docker container deployment

---

## 📂 Project Structure

```
boston_house_pricing/
│
├── app.py
├── model.pkl
├── scaler.pkl
├── requirements.txt
├── Dockerfile
├── templates/
│   └── home.html
└── README.md
```

---

## 💻 How to Run Locally

### 1. Clone repo

```
git clone https://github.com/yourusername/boston_house_pricing.git
cd boston_house_pricing
```

### 2. Install requirements

```
pip install -r requirements.txt
```

### 3. Run app

```
python app.py
```

Open browser:

```
http://127.0.0.1:5000
```

---

## 🐳 Run Using Docker

### Build image

```
docker build -t boston-app .
```

### Run container

```
docker run -p 10000:10000 boston-app
```

---

## 🌍 Deployment

This project is deployed on Render using:

* Normal Python deployment
* Docker container deployment

---

## 📊 Input Features Guide

| Feature    | Description                      |
| ---------- | -------------------------------- |
| Crime Rate | Crime rate in area               |
| Rooms      | Average number of rooms          |
| Age        | Age of house                     |
| Distance   | Distance from employment centers |
| Tax        | Property tax rate                |
| LSTAT      | Lower income population %        |

*(Values are demo ranges for ML prediction)*

---

## 🎯 Project Purpose

This project was built to demonstrate:

* End-to-end ML deployment
* Flask integration
* Docker usage
* Cloud deployment
* Real portfolio project for ML roles

---

## 👨‍💻 Author

**Mohammad Rashid**
Machine Learning & AI Enthusiast

---

## ⭐ If you like this project

Give it a star on GitHub.
