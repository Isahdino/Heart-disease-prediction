# Heart-disease-prediction
Machine learning project for predicting heart disease using the UCI dataset
# Heart Disease Prediction Using Machine Learning

This project implements a machine learning model to predict the presence of heart disease based on patient medical data. The model helps classify whether a patient is likely to have heart disease or not using features like age, cholesterol, blood pressure, and more.

---

##  Project Overview

- **Objective:** Build a supervised learning model to predict heart disease.
- **Dataset:** Heart Disease dataset with various medical attributes.
- **Model Used:** Random Forest Classifier.
- **Tools & Libraries:** Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Jupyter Notebook.

---

## 📊 Dataset Details

The dataset contains the following key features:

| Feature Name | Description                         |
|--------------|-----------------------------------|
| age          | Age of the patient                |
| sex          | Gender (1 = male; 0 = female)    |
| cp           | Chest pain type                   |
| trestbps     | Resting blood pressure (mm Hg)   |
| chol         | Serum cholesterol (mg/dl)         |
| fbs          | Fasting blood sugar > 120 mg/dl  |
| restecg      | Resting electrocardiographic results |
| thalach      | Maximum heart rate achieved       |
| exang        | Exercise-induced angina (1 = yes; 0 = no) |
| oldpeak      | ST depression induced by exercise relative to rest |
| slope        | Slope of the peak exercise ST segment |
| ca           | Number of major vessels colored by fluoroscopy |
| thal         | Thalassemia (3 = normal; 6 = fixed defect; 7 = reversible defect) |
| target       | Heart disease presence (1 = yes; 0 = no) |

---

## 🔧 How It Works

1. Load and inspect the dataset.
2. Handle any missing values (if present).
3. Visualize feature correlations using heatmaps.
4. Split data into features (X) and target (y).
5. Scale features using `StandardScaler` for better model performance.
6. Train a Random Forest Classifier.
7. Evaluate the model with accuracy score, confusion matrix, and classification report.

---

## 📈 Model Performance

- Accuracy: Typically above 80% on the test set.
- Confusion matrix and classification reports provide detailed performance metrics.

---

## 📁 Project Structure
heart-disease-prediction/
│
├── heart-disease.csv # Dataset file
├── heart_disease_prediction.py # Main Python script with model training and evaluation
├── README.md # Project overview and instructions

---

## How to Run
1. Make sure you have Python installed (preferably 3.7+).
2. Install dependencies:
3. Place `heart-disease.csv` in the project folder.
4. Run the script:

---

## Results
- Accuracy: 83% (varies depending on data split)
- Confusion matrix and classification report printed in the console.
- Feature importance chart visualizes the impact of each feature.

## Future Improvements
- Experiment with other classifiers like Logistic Regression and SVM.
- Use hyperparameter tuning to improve model performance.
- Perform cross-validation for more robust evaluation.
- Add a web interface or deploy as a web app.

---

# 3. requirements.txt (for dependencies)
pandas
numpy
matplotlib
seaborn
scikit-learn

## 📬 Contact
Created by **Isah Yusuf Dino**  
Email: isahdino85@gmail.com 
