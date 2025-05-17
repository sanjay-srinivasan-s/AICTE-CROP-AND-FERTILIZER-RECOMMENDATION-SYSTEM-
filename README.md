# AICTE-CROP-AND-FERTILIZER-RECOMMENDATION-SYSTEM-
# Crop and Fertilizer Recommendation System 🌾🧪

This project provides a machine learning-based system for recommending the best crop to plant and the appropriate fertilizer to use based on soil and weather conditions.

## 🚀 Project Features
- **Crop Recommendation**: Predicts the most suitable crop to cultivate based on input features like Nitrogen, Phosphorus, Potassium, temperature, humidity, pH, and rainfall.
- **Fertilizer Recommendation**: Suggests the best fertilizer based on crop needs and soil conditions.

## 📁 Project Structure

📦 Crop_Prediction.ipynb - Jupyter notebook for crop recommendation
📦 Fertilizer_Recommendation.ipynb - Jupyter notebook for fertilizer recommendation
📂 crop_model.sav - Trained model for crop prediction
📂 crop_scaler.sav - Scaler used for crop data preprocessing
📂 fertilizer_model.sav - Trained model for fertilizer prediction
📂 fertilizer_scaler.sav - Scaler used for fertilizer data preprocessing
📂 Crop_recommendation.csv - Dataset used for training crop model
📂 Fertilizer Prediction.csv - Dataset used for training fertilizer model

markdown
Copy
Edit

## 📊 Datasets
- `Crop_recommendation.csv`: Contains features like N, P, K, temperature, humidity, pH, rainfall, and target crop.
- `Fertilizer Prediction.csv`: Contains data for fertilizer recommendations based on soil conditions.

## 🛠️ Requirements
Install the dependencies using:

pip install -r requirements.txt
requirements.txt example:

numpy
pandas
scikit-learn
matplotlib
seaborn

## 📌 How to Use
Crop Recommendation
Open Crop_Prediction.ipynb in Jupyter Notebook.

Run the notebook to load data, preprocess, train, and test the model.

Use the trained model (crop_model.sav) and scaler (crop_scaler.sav) for predictions.

Fertilizer Recommendation
Open Fertilizer_Recommendation.ipynb.

Follow similar steps to train and evaluate the fertilizer model.
