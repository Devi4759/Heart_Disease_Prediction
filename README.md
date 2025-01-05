# Heart Disease Prediction Application

## Description
The **Heart Disease Prediction Application** is a web-based tool that predicts the risk of heart disease based on user-provided health metrics. This application leverages Machine Learning algorithms to analyze input data and provide accurate predictions. In addition, it offers several features like locating nearby hospitals, accessing articles on heart health, and answering health-related questions to enhance user awareness.

## Features
- **Heart Disease Prediction**: Input health metrics to predict whether you are at risk of heart disease.
- **User-Friendly Interface**: An interactive UI built using HTML, CSS, and JavaScript.
- **Machine Learning**: Backend prediction system using Flask and trained machine learning models.
- **Nearby Hospitals**: Provides a list of nearby hospitals for users requiring immediate medical assistance.
- **Educational Articles**: Access a blog section with curated articles on heart health and preventive care.
- **Interactive Questions**: Answer health-related questions to improve awareness and knowledge about heart health.

## Machine Learning Algorithms Used
- Logistic Regression (Scikit-learn)
- Naive Bayes (Scikit-learn)
- Support Vector Machine (Linear) (Scikit-learn)
- K-Nearest Neighbours (Scikit-learn)
- Decision Tree (Scikit-learn)
- Random Forest (Scikit-learn)
- XGBoost (Scikit-learn)
- Neural Network

**Accuracy Achieved**: 95% (Random Forest)

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Flask (Python)
- **Database**: MySQL
- **Machine Learning**: Trained models for prediction using Python libraries

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repository/heart-disease-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd heart-disease-prediction
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Set up the database:
   - Create a MySQL database and update the database credentials in the Flask configuration.
   - Run the database migration script to set up tables.
5. Start the Flask server:
   ```bash
   flask run
   ```
6. Access the application in your browser at `http://127.0.0.1:5000`.

## Usage
1. Open the application in your browser.
2. Fill in the health metrics in the provided form:
   - **Age**: Enter your age.
   - **Sex**: 0 for Female, 1 for Male.
   - **Chest Pain Type**: 0-3 based on the severity.
   - Other health metrics as listed in the form.
3. Click the **Predict** button.
4. View the prediction result:
   - "You have a heart disease" or "You don’t have heart disease."
5. Explore additional features:
   - **Nearby Hospitals**: Find hospitals near your location.
   - **Health Articles**: Read blogs on heart health.
   - **Interactive Questions**: Answer questions to learn more about maintaining heart health.

## Future Enhancements
- Incorporate real-time location for better hospital suggestions.
- Add multi-language support for a wider audience.
- Enhance the machine learning model for even better accuracy.
- Introduce user accounts for personalized health tracking.

---
