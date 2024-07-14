# CodeAlpha_TitanicSurvivalClassification
It performs titanic survical classification based on factors that lead to success-socio-economic status, age, gender and more.

# Titanic Survival Classification Project Overview

This project demonstrates the application of machine learning techniques to predict survival on the Titanic dataset using a Random Forest Classifier.

## Dataset

The dataset used in this project is the Titanic dataset, which includes various features such as passenger class (`pclass`), sex (`sex`), age (`age`), number of siblings/spouses aboard (`sibsp`), number of parents/children aboard (`parch`), fare (`fare`), and others. This dataset is commonly used for predictive modeling and is available on platforms like Kaggle.

## Features

- `pclass`: Passenger class (1st, 2nd, or 3rd).
- `sex`: Gender of the passenger.
- `age`: Age of the passenger.
- `sibsp`: Number of siblings/spouses aboard.
- `parch`: Number of parents/children aboard.
- `fare`: Passenger fare.
- Other features related to cabin, embarkation port, and survival status.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/titanic-survival-classification.git
   cd titanic-survival-classification
Create a virtual environment and activate it:

'''bash
Copy code
python -m venv venv
source venv/bin/activate   # On Windows use `venv\Scripts\activate`
Install the required dependencies:

'''bash
Copy code
pip install -r requirements.txt

### Results

The Random Forest Classifier achieved an accuracy of 97.33% in predicting survival outcomes on the Titanic dataset. This performance is summarized below:

#### Confusion Matrix

[[144 0]
[ 7 111]]


### Conclusion

This project demonstrates the application of machine learning techniques to predict survival on the Titanic dataset using a Random Forest Classifier. The model's high accuracy highlights its effectiveness in accurately analyzing historical passenger data to predict survival probabilities.

Through this project, we explored the importance of feature selection, model evaluation, and performance metrics in machine learning. The insights gained provide a valuable learning experience for understanding the factors influencing survival rates on the Titanic.

The project is a practical example of data science and machine learning, showcasing the steps in building and evaluating predictive models. By leveraging Python libraries such as pandas, sci-kit-learn, and matplotlib, we were able to preprocess data, train the model, and evaluate its performance effectively.

Feel free to adjust the content based on any additional insights or reflections you may have gained from your project experience.
