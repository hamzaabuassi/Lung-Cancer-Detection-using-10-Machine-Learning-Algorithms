# 🫁 Lung Cancer Prediction using Machine Learning

This project focuses on predicting lung cancer presence using machine learning techniques based on survey data.

## 📊 Dataset
- Source: Lung Cancer Survey Dataset
- Features include: age, smoking habits, anxiety, yellow fingers, peer pressure, gender, etc.

## 🛠️ Tools & Libraries
- Python, Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn
- imbalanced-learn (SMOTE)

## 📈 Exploratory Data Analysis (EDA)
- Violin plots to show relationships between smoking, age, gender, and lung cancer.
- Heatmap for cancer distribution by gender.
- Histograms, scatter plots, and bar plots for visual insight into feature distributions.

## 🧠 Machine Learning Models
Ten models were evaluated:
- Logistic Regression
- AdaBoost
- LDA
- K-Nearest Neighbors
- MLP (Neural Network)
- Naive Bayes
- Decision Tree
- Random Forest
- Gradient Boosting
- SVM

## ⚖️ Data Processing
- One-hot encoding for categorical variables
- SMOTE for class balancing
- Standard scaling for model input

## 🏆 Results
| Model               | Accuracy | Precision | Recall | F1 Score |
|--------------------|----------|-----------|--------|----------|
| Logistic Regression| 0.9722   | 0.9811    | 0.9630 | 0.9720   |
| AdaBoost           | 0.9630   | 0.9808    | 0.9444 | 0.9623   |
| LDA                | 0.9537   | 0.9804    | 0.9259 | 0.9524   |
| KNN                | 0.9444   | 0.9615    | 0.9259 | 0.9434   |
| MLP                | 0.9444   | 0.9800    | 0.9074 | 0.9423   |

## 📌 Conclusion
- Logistic Regression achieved the highest F1 score of **0.9720**
- Dataset balancing and proper preprocessing significantly improved model performance

## 👤 Author
**Hamza Abuassi**  
