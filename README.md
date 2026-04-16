London House Price Prediction (End-to-End ML + ANN)

Project Overview
This project predicts London house prices using machine learning and deep learning models. It includes full pipeline from data preprocessing to ANN-based regression.



 Tech Stack
  Python
  Pandas, NumPy
  Scikit-learn
  TensorFlow / Keras
  XGBoost
  Matplotlib, Seaborn

Workflow

 1.Data Preprocessing
   Missing value handling
   Outlier removal
   Label encoding & one-hot encoding
   Feature engineering (date-based features)

 2.Exploratory Data Analysis
   Correlation heatmap
   Distribution plots
   Boxplots for outlier detection

 3.Machine Learning Models
   Linear Regression
   KNN Regressor
   Decision Tree
   Gradient Boosting
   XGBoost

 4.Hyperparameter Tuning
   RandomizedSearchCV applied on Gradient Boosting

 5.Deep Learning Model (ANN)
   Dense layers with ReLU activation
   Dropout (0.4) for regularization
   EarlyStopping used to prevent overfitting



 Results
 Best MAE: ~94,000
 ANN shows stable generalization with dropout regularization
 Model comparison performed between ML & DL approaches



 Key Insight
Tree-based models (GB, XGB) performed strongly, but ANN provided competitive results after proper tuning.

