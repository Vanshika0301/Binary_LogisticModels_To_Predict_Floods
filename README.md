# Flood Prediction using Logistic Regression and KNN Classifier

![image](https://github.com/Vanshika0301/Flood_Prediction_using_LogisticRegression_and_KNNClassifier/assets/146732449/cb6dc2ee-4e89-47d6-95e0-903905035143)

## Overview
This project aims to predict floods in Kerala, India, based on monthly rainfall data using binary logistic regression and the K-Nearest Neighbors (KNN) classifier. The dataset includes monthly rainfall measurements from different years, along with a binary label indicating whether a flood occurred in that year or not.

## Dataset
The dataset (kerala.txt) contains the following columns:
- SUBDIVISION: Name of the region (always "KERALA")
- YEAR: Year of the data entry
- JAN to DEC: Monthly rainfall measurements in millimeters
- ANNUAL RAINFALL: Total annual rainfall in millimeters
- FLOODS: Binary label indicating whether a flood occurred (YES: 1, NO: 0)

## Project Structure
The project is structured as follows:
- kerala.txt: Dataset containing monthly rainfall data and flood labels
- flood_prediction.ipynb: Jupyter Notebook containing the Python code for data preprocessing, exploratory data analysis, model training, and evaluation
- README.md: Markdown file providing an overview of the project and instructions for running the code

## Dependencies
- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- scikit-learn
- seaborn
- matplotlib

## Results
The notebook provides detailed steps for:
- Data preprocessing, including handling missing values and converting categorical labels to numerical format
- Exploratory data analysis (EDA), including visualizations of rainfall patterns over different months and years
- Model training using logistic regression and KNN classifier
- Model evaluation using accuracy scores and cross-validation
- KNN with the highest accuracy score, i.e., 91.67%

## Future Work
Possible future enhancements include:
- Experimenting with different machine learning algorithms and hyperparameter tuning
- Incorporating additional features such as temperature, humidity, and geographical data for improved prediction accuracy
- Deploying the model as a web application or API for real-time flood prediction
