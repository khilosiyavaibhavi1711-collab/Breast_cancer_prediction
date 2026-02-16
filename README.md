# 🩺 Breast Cancer Diagnostic Assistant

This project is an end-to-end Machine Learning solution designed to assist in the classification of breast cancer tumors. It features a trained **Logistic Regression** model and an interactive **Streamlit** web dashboard for real-time predictions.

## 🚀 Live Demo
[Insert your Streamlit Cloud Link Here]

## ✨ Key Features
- **Interactive Dashboard:** Adjust clinical measurements using sliders to see real-time AI analysis.
- **Radar Chart Visualization:** Visualizes tumor characteristics (Radius, Texture, Area, etc.) using Plotly.
- **High Accuracy:** Achieved ~98% accuracy on the Wisconsin Diagnostic Breast Cancer (WDBC) dataset.
- **Confidence Scoring:** The model provides a probability percentage for its prediction.

## 🛠️ Technology Stack
- **Language:** Python 3.x
- **Libraries:** Scikit-Learn, Pandas, NumPy, Plotly, Streamlit
- **Model:** Logistic Regression (Standardized via StandardScaler)

## 📁 Project Structure
- `app.py`: The Streamlit web application code.
- `Breast_Cancer_Prediction_test.ipynb`: The research, EDA, and model training notebook.
- `cancer_model.pkl`: The saved Logistic Regression model.
- `scaler.pkl`: The saved StandardScaler object for data normalization.
- `features.pkl`: The saved list of feature names to ensure data consistency.
- `requirements.txt`: List of dependencies for deployment.

## ⚙️ How to Run Locally
1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/breast-cancer-prediction.git](https://github.com/your-username/breast-cancer-prediction.git)
