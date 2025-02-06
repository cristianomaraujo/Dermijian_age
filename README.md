# 📊 Machine Learning for Dental Age Estimation  

## 📝 Overview  
This project explores the application of **machine learning models** for **dental age estimation**, comparing their predictive performance against the **Demirjian method**. Various regression models were trained and evaluated, with **Gradient Boosting (GB) and Random Forest (RF)** emerging as the most accurate approaches.  

## 📈 Key Findings  
- **ML models achieved predictive errors below 1.5 years**, demonstrating high accuracy.  
- **Gradient Boosting and Random Forest** had the best performance:  
  - **MAE**: 0.75 (95% CI: [0.66 – 0.85])  
  - **RMSE**: 0.92 (95% CI: [0.81 – 1.05])  
- These models significantly outperformed **Demirjian’s method** (MAE = 1.34, RMSE = 1.63).  
- The results highlight the **limitations of linear regression** in capturing **nonlinear relationships** in dental age prediction.  

## 🔬 Methodology  
- **Dataset**: Lateral cephalometric radiographs annotated for dental age.  
- **Preprocessing**: Data cleaning, feature selection, and normalization.  
- **Models Used**:  
  - Gradient Boosting Regressor  
  - Random Forest Regressor  
  - Support Vector Regression (SVR)  
  - K-Nearest Neighbors (KNN)  
  - Multi-Layer Perceptron (MLP)  
  - Decision Tree (DT)  
  - Linear Regression (baseline)  
- **Evaluation Metrics**: Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).  
- **Cross-Validation**: Performed to ensure model generalizability.  
