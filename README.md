## ❤️ Heart Risk Level Analysis using Machine Learning

This project aims to predict the risk of heart disease using machine learning techniques. By analyzing key medical attributes such as chest pain type, heart rate, and ECG-related features, the model classifies patients into different risk levels. This helps in identifying potential heart conditions at an early stage.

## 📊 Dataset

The project uses the Heart Disease dataset from Kaggle, which contains patient health records with multiple medical attributes.
The dataset was cleaned by removing duplicate entries and transforming the target variable into multiple risk categories for better classification.

## ⚙️ Data Preprocessing

To improve model performance, several preprocessing steps were applied.
The dataset was balanced using SMOTE to handle class imbalance. Feature scaling was performed using StandardScaler to normalize the data. Important features such as chest pain type, maximum heart rate, ST depression, and exercise-induced angina were selected based on their relevance.

## 🤖 Model Development

Two machine learning models were implemented: Random Forest Classifier and Logistic Regression.
The models were trained and tested using different train-test splits (70:30, 75:25, 80:20) to evaluate their performance under varying data distributions.

## 📈 Results and Performance

The models were evaluated using accuracy, precision, recall, and F1-score.
The Random Forest model performed better overall, achieving a maximum accuracy of 85%, while Logistic Regression achieved up to 82% accuracy.
Random Forest showed better balance across all evaluation metrics.

## 🛠️ Technologies Used
- Python
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Seaborn

## 🔮 Future Improvements
- Add Deep Learning models
- Handle class imbalance better
- Deploy as a web/app interface
- Include real-time patient data

## 🎯 Conclusion

This project demonstrates how machine learning can be effectively used for heart disease risk prediction. With proper preprocessing and model selection, it is possible to achieve reliable performance and gain useful insights from healthcare data.
