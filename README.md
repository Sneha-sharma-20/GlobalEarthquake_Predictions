# **Earthquake Magnitude Prediction**

## **Overview**
This project aims to predict earthquake magnitudes using machine learning techniques.  
By analyzing historical seismic data, the model leverages Random Forest Regression to deliver accurate predictions.  
Additionally, a classification model is employed to identify high-risk earthquakes, enabling proactive disaster management and resource allocation.  

The project evaluates its performance using metrics like Root Mean Squared Error (RMSE), Mean Squared Error (MSE), and classification metrics such as accuracy and confusion matrices.

---

## **Features**
- Predict earthquake magnitudes using regression models.  
- Classify earthquakes based on a critical magnitude threshold (e.g., ≥5.0 for high risk).  
- Visualize key insights such as feature importance and confusion matrices.  
- Evaluate model performance with robust metrics.  

---

## **Technologies Used**
- **Programming Language:** Python  
- **Libraries:**
  - `sklearn` for machine learning models and metrics  
  - `numpy` and `pandas` for data manipulation  
  - `matplotlib` and `seaborn` for visualization  

---

## **Dataset**
The dataset contains historical seismic data with features such as:
- Magnitude  
- Depth  
- Latitude and Longitude  
- Time of occurrence  

**Target Variable:** Magnitude of the earthquake  
The dataset is preprocessed to handle missing values, scale features, and ensure model readiness.

##**Key Results**
- **Regression Metrics:**

-Root Mean Squared Error (RMSE): e.g., 0.245
-Mean Squared Error (MSE): e.g., 0.06
-**Classification Metrics:**

-Accuracy: 97.37%
-Precision: 99.17%
-Recall: 96%
