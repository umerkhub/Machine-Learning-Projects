
# 🪨 Rock vs Mine Prediction using Machine Learning

📌 Project Overview
This project focuses on building a supervised machine learning model to classify sonar signals as either a **rock** or a **mine**. The model helps in underwater object detection using sonar data.

## 🛠️ Technologies & Libraries Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

## 📊 Problem Statement
Using 60 numeric attributes representing energy levels returned by sonar signals, we aim to predict whether the object is a Rock (R) or Mine (M).

## 📂 Project Structure

    ├── sonar.csv                        # Dataset file
    ├── Rock_VS_Mine_Prediction.ipynb   # Main notebook
    └── README.md                        # Project summary

## 🔍 Workflow
1. **Data Loading & Exploration**  
   - Checked shape, data types, null values  
   - Count plot of label distribution  

2. **Data Preprocessing**  
   - Label encoding (R=0, M=1)  

3. **Model Building**  
   - Used Logistic Regression for classification  
   - Split dataset into train/test sets (0.8/0.2)

4. **Evaluation Metrics**  
   - Accuracy Score  
   - Confusion Matrix  
   - Classification Report

## 📈 Visualizations

- Class distribution using `seaborn.countplot()`
- Confusion Matrix with `sns.distplot()`

## ✅ Results
**Model Used**: Logistic Regression  
**Test Accuracy**: ~83%  
**Conclusion**: Model is reasonably accurate and effective for classifying sonar signals.


## 🧠 Future Improvements
- Try ensemble models like Random Forest or Gradient Boosting  
- Apply dimensionality reduction (PCA) for performance  
- Create a user interface for input and prediction  



## 📌 Key Skills Applied
`Supervised Learning` • `Classification` • `Data Preprocessing` • `Model Evaluation` • `Logistic Regression` • `Scikit-learn` • `Data Visualization`


## 👨‍💻 Author

**Umer Khan**  

