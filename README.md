# Heart_Disease_Prediction_Using_ML

## Project Overview
This project predicts the likelihood of heart disease in individuals using machine learning models. It uses clinical and demographic data to train models that can help identify high-risk patients for early intervention.

## Features
- Data preprocessing (handling missing values, encoding categorical variables, normalization)
- Exploratory Data Analysis (EDA) to visualize data patterns
- Model training and evaluation (Logistic Regression, SVM, Decision Tree, Naive Bayes)
- Performance metrics (accuracy, precision, recall, F1-score, ROC-AUC)
- Prediction script for new patient data
- Insights into key factors influencing heart disease

## Dataset
The dataset used is `HeartDisease.csv`, containing patient records with features such as:
- Age
- Sex
- Chest pain type
- Resting blood pressure
- Cholesterol levels
- Fasting blood sugar
- Resting ECG results
- Maximum heart rate achieved
- Exercise-induced angina
- ST depression
- Slope of peak exercise ST segment
- Number of major vessels colored by fluoroscopy
- Thalassemia
- Target variable (presence or absence of heart disease)

## Folder Structure
├─ HeartDisease.csv # Dataset
├─ heart_disease_prediction.py # Python script for prediction
├─ heart_disease_prediction.ipynb # Complete workflow in notebook
├─ Logistic_X_SVM.ipynb # Logistic Regression & SVM comparison
├─ Naive_bayes_X_Decision_Tree.ipynb # Naive Bayes & Decision Tree comparison
├─ requirements.txt # Python dependencies
└─ README.md # Project documentation

## Installation
1. (Optional) Create a virtual environment:
python -m venv venv
source venv/bin/activate # Windows: venv\Scripts\activate

markdown
2. Install dependencies:
pip install -r requirements.txt

## Usage
- Open the Jupyter notebooks (`.ipynb`) to explore the workflow:
- `Logistic_X_SVM.ipynb`
- `Naive_bayes_X_Decision_Tree.ipynb`
- `heart_disease_prediction.ipynb`
- Run `heart_disease_prediction.py` to make predictions on new patient data.

## Model Evaluation
- Accuracy, precision, recall, F1-score, and ROC-AUC metrics are calculated for each model.
- Feature importance analysis identifies critical factors like age, cholesterol, resting blood pressure, and maximum heart rate.

## Contributing
Contributions are welcome! You can:
- Improve preprocessing
- Add new models (e.g., Random Forest, Gradient Boosting)
- Develop a web app or API for real-time predictions

Please open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Author
Supraja Asthanaditta  
[GitHub Profile](https://github.com/Supraja1423)
