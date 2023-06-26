# Amazon Movie Reviews Star Rating Prediction

## Problem Statement
The goal of the project is to build a model that can accurately predict the star rating of user reviews based on given features. The dataset contains various attributes such as text, summary, time, and helpfulness, which can be used to train a predictive model.

## Dependencies
* Python
* Pandas
* NumPy
* Scikit-learn 
* NLTK
* LightGBM

## Requirements
The project requires the following data files:
[Amazon Movie Reviews dataset](https://www.kaggle.com/competitions/cs506-spring-2023-midterm/data)

## Installation Instructions
1. Install the required dependencies using pip:
```
pip install pandas numpy scikit-learn nltk lightgbm
```
2. Download the necessary NLTK resources for sentiment analysis:
```
import nltk
nltk.download('vader_lexicon')
```
3. Run the project code