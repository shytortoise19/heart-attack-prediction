# Heart Attack Prediction

This project aims to predict the likelihood of heart attacks in patients using machine learning techniques. The dataset includes various features like age, sex, cholesterol levels, exercise-induced angina, and more, to build a logistic regression model that estimates the chances of a heart attack.

## Dataset
https://www.kaggle.com/datasets/rashikrahmanpritom/heart-attack-analysis-prediction-dataset
The dataset includes the following features:

- **Age**: Age of the patient
- **Sex**: Sex of the patient
- **exang**: Exercise-induced angina (1 = yes; 0 = no)
- **ca**: Number of major vessels (0-3)
- **cp**: Chest pain type:
  - Value 1: typical angina
  - Value 2: atypical angina
  - Value 3: non-anginal pain
  - Value 4: asymptomatic
- **trtbps**: Resting blood pressure (in mm Hg)
- **chol**: Cholesterol level in mg/dl
- **fbs**: Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
- **rest_ecg**: Resting electrocardiographic results:
  - Value 0: normal
  - Value 1: ST-T wave abnormality
  - Value 2: Probable or definite left ventricular hypertrophy
- **thalach**: Maximum heart rate achieved
- **target**: 0 = less chance of heart attack, 1 = more chance of heart attack

## Libraries Used

The following Python libraries are used in this project:

- `numpy`
- `pandas`
- `seaborn`
- `matplotlib`
- `scikit-learn`

## Model and Evaluation

The primary model used for prediction is Logistic Regression. The following metrics are used to evaluate the model's performance:

- Accuracy Score
- Precision
- Recall
- F1 Score

Additionally, a confusion matrix is plotted to visualize the model's performance.

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/shytortoise19/heart-attack-prediction.git
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter notebook to load the data and train the model:
   ```bash
   jupyter notebook heart_attack_prediction.ipynb
   ```

## Results

The evaluation metrics are printed in the console after running the model, and a confusion matrix is generated to better understand the classification performance.

