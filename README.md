

# 📈 Stock Price Prediction App

A full-stack web application that predicts future stock prices using a trained deep learning model (LSTM) and displays the results in an interactive frontend. The app uses FastAPI for the backend, TensorFlow for the ML model, MongoDB for storing prediction history, and React for the frontend.

---

## 🎯 Project Aim

The main goal of this project is to build an intelligent system that:
- Accepts a stock ticker symbol (e.g., AAPL, TSLA)
- Uses a deep learning model to predict future prices based on historical data
- Displays the results visually to the user
- Stores prediction history in MongoDB for auditing or analysis

This project is ideal for learning how to combine **machine learning** with **web development** in a real-world scenario.

---

## 🛠️ Tech Stack

### 🚀 Frontend
- **React.js**: User interface
- **Axios**: API calls to FastAPI backend
- **Tailwind CSS** : For UI styling and responsiveness

### 🔧 Backend
- **FastAPI**: REST API server
- **TensorFlow + Keras**: LSTM model for time series prediction
- **yfinance**: Download stock historical data
- **pydantic**: Input data validation

### 🗃️ Database
- **MongoDB (Atlas or Local)**: To store prediction history (stock, date, result)

---

## 🧠 How It Works

1. **User inputs a stock symbol** (like "AAPL") in the React frontend.
2. **Frontend sends a POST request** to the FastAPI backend.
3. **Backend downloads historical stock data** using `yfinance`.
4. **Data is preprocessed and fed into a trained LSTM model**.
5. **Prediction result is returned to frontend** and also saved in **MongoDB**.
6. **Frontend displays the predicted value and chart.**

---

## 📂 Folder Structure

