# Credit Card Fraud Detection using Machine Learning
Credit Card Fraud is rising everyday and designing systems that detect fraud is becoming more important each and every day. This project explores the use of Machine Learning to detect fraudulent transactions from a dataset of labelled credit card transactions.
# Data Source 💽
The dataset "Credit Card Fraud Detection" was sourced from Kaggle, which hosts various datasets and resources for Data Science and Machine Learning. The dataset can be accesed here https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud.
# Preprocessing 🔀
The dataset contained various missing values, which were imputed using the Simple Imputer module in scikit-learn, a popular machine learning python package. The values were scaled to reduce bias due to scale. The data was split into training and testing sets.
# Training 📈
Machine Learning algorithms like Logistic Regression, Support Vector Machine(Support Vector Classifier in this case), K-Nearest Neighbours and Ensemble Methods like AdaBoost,GradientBoost,Random Forest, Extreme Gradient Boost(XGBoost) and CatBoost all available in the scikit-learn package were used in this project.The models were trained on the training data and were tested on the testing set.
# Evaluation 🔬
The predictions of the ML models were evaluated using various evaluation metrics like Accuracy Score, Precision, Recall, F1-Score, AUC_ROC Score. The AUC-ROC curve is used in machine learning to evaluate how well a binary classification model distinguishes between classes (positive vs. negative), offering a threshold-independent view of performance by plotting True Positive Rate (TPR) vs. False Positive Rate (FPR) at various thresholds, making it great for imbalanced data as in our project where accuracy fails, showing overall model separability. Based on AUC_ROC Score Ensemble Models which combine many individual classifiers to give a single more robust prediction perform comparatively better.
# Interpretation of Results 📊
The results were interpreted using LIME (Local Interpretable Model-Agnostic Explanations) and SHAP (SHapley Additive exPlanations).

