# ☀ Solar Prediction ☀

## 📌 Introduction
The main objective for this case is to create a Regression Model capable of predicting efficiently solar radiation from a csv file. The csv file used for this project was taken from Kaggle and is available in this repository as (SolarPrediction.csv).

## 📖 Structure:
- **SolarPrediction.csv**: CSV file used.
- **solar_prediction.ipynb**: Jupyter Notebook file with data analysis and both models (Random Forest Regressor and Gradietn Boost Regressor)

## 🛠 Tools
- **Pandas**: Data manipulation
- **NumPy**: Data manipulation
- **Scipy**: Statistical test
- **Matplotlib**: Data and performance graphs
- **Seaborn**: Data and performance graphs
- **Scikit-learn**: Model training and metrics
  
## 🔄 Functions
Only two functions were created. One for model analysis showing up it's performance results (model_analysis) and another one for model comparison (model_comparison).

- **model_analysis(model)**
  
  It receives the variable were the model was saved and prints model's performance statistics and graphs.
- **model_comparison(model_1, model_2)**
  
  Receives both models and creates a graphic comparison between their metrics. For this case, it is setted to show up Random Forest and Gradient Boost for identification.

## ✨ Models
Two models were trained for this case, Random Forest Regressor and Gradient Boost Regressor. The model that showed up better results was Random Forest Regressor and was the final selected model.
