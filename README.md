🌱 TerraMind AI – Crop Yield Prediction System

An end-to-end Deep Learning web application that predicts agricultural crop yield using an Artificial Neural Network (ANN) model. Built with TensorFlow, Scikit-learn, and Streamlit for real-time predictions.

🚀 Live Demo

🔗 Demo: (https://cropyeildappuction-jj5xxghadgbjexysyasxsa.streamlit.app/)

📌 Project Overview

Agriculture plays a crucial role in ensuring food security and economic stability. Predicting crop yield accurately helps farmers, researchers, and policymakers make informed decisions regarding crop planning and resource allocation.

This project uses a Deep Learning Artificial Neural Network (ANN) to estimate crop production based on various agricultural parameters such as:

State
District
Crop Year
Season
Crop Type
Cultivation Area

The application provides instant predictions through an interactive Streamlit interface.

🎯 Features
🌾 Crop Yield Prediction using ANN
📍 State & District Selection
🌱 Crop & Season Selection
📅 Crop Year Input
📏 Area-based Prediction
📊 Interactive Dashboard
📈 Analytics Visualization
⚡ Real-time Predictions
🎨 Modern Responsive UI
☁️ Streamlit Cloud Deployment
🧠 Machine Learning Pipeline
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
      │
      ▼
Inverse Scaling
      │
      ▼
Final Crop Yield
🛠️ Technologies Used
Category	Technology
Programming Language	Python
Deep Learning	TensorFlow / Keras
Machine Learning	Scikit-learn
Data Analysis	Pandas, NumPy
Visualization	Plotly
Web Framework	Streamlit
Model Serialization	Joblib
Deployment	Streamlit Community Cloud
📂 Project Structure
Crop_Yield_Prediction/
│
├── app.py
├── requirements.txt
├── Crop_ann.keras
├── preprocessor.pkl
├── y_scaler.pkl
│
├── notebooks/
│     └── model_training.ipynb
│
├── images/
│     └── app_preview.png
│
├── README.md
│
└── .gitignore
📊 Dataset Features
Feature	Description
State_Name	Name of the State
District_Name	Name of the District
Crop_Year	Year of Cultivation
Season	Growing Season
Crop	Crop Name
Area	Cultivation Area (Hectares)
Target Variable
Production
🧠 Deep Learning Model

Model Type:

Artificial Neural Network (ANN)

Architecture

Input Layer

↓

Dense Layer (ReLU)

↓

Batch Normalization

↓

Dropout

↓

Output Layer (Linear)

Loss Function

Mean Squared Error (MSE)

Optimizer

Adam

Evaluation Metrics

R² Score
RMSE
MAE
💻 Installation

Clone the repository

git clone https://github.com/yourusername/Crop_Yield_Prediction.git

Move into project folder

cd Crop_Yield_Prediction

Install dependencies

pip install -r requirements.txt

Run the application

streamlit run app.py
⚙️ Requirements
streamlit
tensorflow
keras
numpy
pandas
plotly
scikit-learn
joblib
h5py
📈 Model Workflow
User Input

↓

Preprocessor (.pkl)

↓

Feature Encoding

↓

Scaling

↓

ANN Model (.keras)

↓

Prediction

↓

Inverse Scaling

↓

Final Yield Output
📸 Application Preview

(Add screenshots here)

Example:

images/home.png

images/prediction.png

images/dashboard.png
🎯 Future Improvements
Weather API Integration
Soil Quality Analysis
Fertilizer Recommendation
Multi-Crop Prediction
Satellite Data Integration
Farmer Recommendation System
Mobile Application
Model Explainability using SHAP
Historical Trend Analysis
📚 Learning Outcomes

Through this project, I learned:

Data Preprocessing
Feature Engineering
One-Hot Encoding
Feature Scaling
Artificial Neural Networks
Hyperparameter Tuning
TensorFlow/Keras
Model Serialization
Streamlit Deployment
Interactive Dashboard Development
🤝 Contributing

Contributions, issues, and feature requests are welcome.

Feel free to fork the repository and submit a pull request.

📄 License

This project is licensed under the MIT License.

👨‍💻 Author

K Chintu

Data Science | Machine Learning | Deep Learning Enthusiast

💼 LinkedIn: (Add your LinkedIn profile)
💻 GitHub: (Add your GitHub profile)
⭐ If you like this project

Please consider giving this repository a ⭐ Star on GitHub. It motivates me to build and share more Machine Learning and AI projects.
