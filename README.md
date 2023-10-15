# Sales Prediction App

![Sales Prediction App](Image/trends.jpg)


This repository contains a Streamlit application for predicting sales based on various factors like the number of items on promotion, date, city, state, and item family.

## Overview

The Sales Prediction App takes in user input regarding different parameters such as the number of items on promotion, city, state, and item family. The model then processes this data to predict the expected sales for the provided inputs.

## Setup & Installation

1. Clone the repository:
```
git clone <repository-url>
```

2. Navigate to the repository:
```
cd path-to-repository
```

3. Install the required libraries:
```
pip install -r requirements.txt
```

4. Run the Streamlit app:
```
streamlit run app.py
```

## Usage

### Predicting Sales

1. Navigate to the "Prediction" tab on the Streamlit app.
2. Enter the required details in the input fields.
3. Click on the "Predict Sales" button.
4. The predicted sales value will be displayed on the screen.

### Model Information

For more details regarding the trained model, its accuracy, and the data it was trained on, navigate to the "Model Information" tab on the Streamlit app.

## Model

The application uses an XGBoost model trained on a systematically sampled subset of the dataset. The model considers various features like day of the week, city, state, item family, and others to make predictions.

## Feedback

Feedback is a valuable aspect of any application. Users can provide feedback on the accuracy of the predictions and any additional suggestions for improvements.





