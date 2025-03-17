# End to end Machine Learning Project

# Student Performance Prediction (Math Score)

This project predicts students' math scores based on various input features. It evaluates multiple regression algorithms and selects the best-performing model for deployment.

## Dataset & Features
The model is trained on a dataset containing the following features:
- `gender`
- `race_ethnicity`
- `parental_level_of_education`
- `lunch`
- `test_preparation_course`
- `reading_score`
- `writing_score`

## Implementation
The project follows a **modular programming** approach, ensuring clean and maintainable code. The workflow includes:
1. **Data Preprocessing** - Handling missing values, encoding categorical features, and feature scaling.
2. **Model Evaluation** - Testing multiple regression algorithms.
3. **Best Model Selection** - Choosing **Linear Regression** as the final model due to its highest accuracy of **87.8%**.
4. **Deployment** - The trained model is deployed using **Render**.

## Model Evaluation
The following regression algorithms were tested:
- **Linear Regression** (Best Model: **87.8% accuracy**)
- Decision Tree Regression
- Random Forest Regression
- XGBoost Regression
- CatBoost Regression

## Project Structure
```
ML-Project/
│── artifacts/
│── catboost_info/
│── logs/
│── ML_Project.egg-info/
│── notebook/
│── src/
│── templates/
│── venv/
│── .gitignore
│── app.py
│── README.md
│── requirements.txt
│── setup.py
```

## Deployment
The model is deployed using **Render**.

## Installation & Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/ML-Project.git
   ```
2. Navigate to the project folder:
   ```sh
   cd ML-Project
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Run the application:
   ```sh
   python app.py
   ```

## Author
Piyush Kumar

## Credits
This project was inspired by Krish Naik's tutorials on machine learning and deployment. His content provided valuable insights into model selection and deployment strategies.i learned various concepts while implementing this end to end project..

---
This project provides an efficient and reliable way to predict students' math performance based on key demographic and academic factors.

