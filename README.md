# 🌾 TerraMind AI - Crop Yield Prediction System

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.11-blue?logo=python">
  <img src="https://img.shields.io/badge/TensorFlow-Deep%20Learning-orange?logo=tensorflow">
  <img src="https://img.shields.io/badge/Streamlit-Web%20App-red?logo=streamlit">
  <img src="https://img.shields.io/badge/License-MIT-green">
</p>

An end-to-end **Deep Learning Crop Yield Prediction System** built using **TensorFlow, Scikit-learn, and Streamlit**. The application predicts agricultural crop production based on geographical, seasonal, and cultivation features using an Artificial Neural Network (ANN).

---

# 🚀 Live Demo

🔗 **Streamlit App:** *(Add your deployed app link here)*

---

# 📖 Project Overview

Agriculture plays a vital role in food security and economic development. Accurate crop yield prediction helps farmers, researchers, and policymakers make informed decisions regarding crop planning, resource allocation, and production management.

This project uses an **Artificial Neural Network (ANN)** to estimate crop production using agricultural features such as:

- 🌍 State
- 🏙 District
- 📅 Crop Year
- 🌦 Season
- 🌱 Crop
- 📏 Cultivation Area

The trained model is deployed as an interactive **Streamlit** web application for real-time predictions.

---

# ✨ Features

- 🌾 Crop Yield Prediction using ANN
- 📍 State & District Selection
- 🌱 Crop & Season Selection
- 📅 Crop Year Input
- 📏 Area-based Prediction
- ⚡ Real-Time Prediction
- 📊 Interactive Dashboard
- 📈 Visual Analytics
- 🎨 Modern Streamlit UI
- ☁️ Streamlit Cloud Deployment

---

# 🧠 Machine Learning Pipeline

```text
Raw Input
     │
     ▼
Data Preprocessing
     │
     ▼
Column Transformer
     │
     ▼
One-Hot Encoding
     │
     ▼
Feature Scaling
     │
     ▼
Artificial Neural Network
     │
     ▼
Yield Prediction
```

---

# 🏗 Model Architecture

```text
Input Layer (811 Features)
        │
        ▼
Dense Layer (ReLU)
        │
        ▼
Batch Normalization
        │
        ▼
Dropout Layer
        │
        ▼
Output Layer (Linear)
```

---

# 🛠 Tech Stack

| Category | Technology |
|----------|------------|
| Language | Python |
| Deep Learning | TensorFlow, Keras |
| Machine Learning | Scikit-learn |
| Data Processing | Pandas, NumPy |
| Visualization | Plotly |
| Deployment | Streamlit |
| Serialization | Joblib |

---

# 📂 Project Structure

```text
crop_yield_production/
│
├── app.py
├── requirements.txt
├── Crop_ann.keras
├── preprocessor.pkl
├── y_scaler.pkl
├── README.md
├── .gitignore
│
├── notebooks/
│   └── model_training.ipynb
│
└── images/
    ├── home.png
    ├── prediction.png
    └── analytics.png
```

---

# 📊 Dataset Features

| Feature | Description |
|----------|-------------|
| State_Name | State Name |
| District_Name | District Name |
| Crop_Year | Year of Cultivation |
| Season | Growing Season |
| Crop | Crop Name |
| Area | Cultivation Area (Hectares) |

### 🎯 Target Variable

```
Production
```

---

# 📈 Model Performance

| Metric | Score |
|---------|------:|
| R² Score | 94.6% |
| Model Type | Artificial Neural Network |
| Loss Function | Mean Squared Error |
| Optimizer | Adam |

---

# ⚙ Installation

Clone the repository

```bash
git clone https://github.com/your-username/crop_yield_production.git
```

Go to the project folder

```bash
cd crop_yield_production
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
streamlit run app.py
```

---

# 📷 Application Screenshots

## 🏠 Home Page

> Add screenshot here

```
images/home.png
```

---

## 🌾 Prediction Page

> Add screenshot here

```
images/prediction.png
```

---

## 📊 Analytics Dashboard

> Add screenshot here

```
images/analytics.png
```

---

# 💡 Future Enhancements

- 🌦 Weather API Integration
- 🌱 Soil Analysis
- 🛰 Satellite Data Support
- 🤖 Fertilizer Recommendation
- 📈 Historical Trend Analysis
- 📱 Mobile Application
- ☁ Multi-Crop Prediction
- 📊 Explainable AI (SHAP)

---

# 📚 Learning Outcomes

This project helped me gain practical experience in:

- Data Preprocessing
- Feature Engineering
- One-Hot Encoding
- Feature Scaling
- Artificial Neural Networks
- TensorFlow & Keras
- Model Serialization
- Streamlit Deployment
- Interactive Dashboard Development

---

# 🤝 Contributing

Contributions are welcome.

1. Fork this repository
2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Added new feature"
```

4. Push to GitHub

```bash
git push origin feature-name
```

5. Create a Pull Request

---

# 📄 License

This project is licensed under the **MIT License**.

---

# 👨‍💻 Author

## K Chintu

**Data Science | Machine Learning | Deep Learning Enthusiast**

📧 Email: *your-email@example.com*

💼 LinkedIn: https://linkedin.com/in/your-profile

💻 GitHub: https://github.com/your-github

---

# ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.

It motivates me to build and share more Machine Learning and Deep Learning projects.

---

<p align="center">
Made with ❤️ using TensorFlow, Scikit-learn and Streamlit
</p>
