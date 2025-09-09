# Estimation of Obesity Levels Based on Eating Habits and Physical Condition

This repository contains a machine learning project that predicts obesity levels in individuals using their eating habits and physical condition data. The model leverages data from Mexico, Peru, and Colombia and classifies each individual into seven categories—ranging from Insufficient Weight to Obesity Type III.

## 🎯 Objective

- Develop an accurate machine learning model for obesity level prediction
- Identify key predictors from lifestyle and physical data
- Enable personalized obesity risk assessment and planning
- Raise awareness of health risks linked to obesity

## 📊 Dataset

- Size: 2,111 entries, ages 14–61
- 17 attributes:
  - **Demographics:** Gender, Age, Height, Weight
  - **Dietary Habits:** Frequency of high-calorie and vegetable consumption, Main meals count, Food between meals, Daily water intake, Alcohol consumption
  - **Lifestyle:** Monitoring calories, Physical activity, Tech device time, Transportation mode, Smoking status, Family history of overweight
- **Target:** Obesity Level (7 classes)

## ⚙️ Methodology

1. **EDA:** Distribution and feature exploration
2. **Preprocessing:**
   - Handle missing values
   - Outlier treatment (Age, Height, Weight)
   - Categorical encoding
   - Feature scaling
3. **Model Training:** Split: 80% train / 20% test; algorithms used:
   - Logistic Regression
   - Decision Tree
   - K-Nearest Neighbors
   - Support Vector Classifier
   - Random Forest
4. **Evaluation:** Accuracy, Precision, Recall, F1-Score
5. **Hyperparameter Tuning:** Top models refined

## 🛠️ Tools & Technologies

- Python (Jupyter Notebook + Anaconda)
- Power BI (Dashboarding)
- Scikit-learn (ML models)

## ✨ Results

| Model                   | Initial Accuracy | Accuracy After Tuning |
|-------------------------|-----------------|-----------------------|
| Logistic Regression     | 0.91            | **0.96**              |
| Decision Tree           | 0.79            | NA                    |
| Support Vector Classifier| 0.90           | NA                    |
| K-Nearest Neighbors     | 0.73            | NA                    |
| Random Forest           | 0.96            | **0.96**              |

- **Top Performers:** Logistic Regression & Random Forest
