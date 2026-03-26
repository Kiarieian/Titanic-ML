# Titanic ML

A machine learning project for predicting passenger survival on the Titanic dataset.

## Overview

This project uses classification algorithms to predict whether a passenger survived the Titanic disaster 
## features
Age, Sex, Ticket class and fare.

## Model
- Random Forest Classifier
- Trained on `train.csv` with feature encoding and missing value handling
- Predicts survival (0 = did not survive, 1 = survived)
- Can output survival probability per passenger

## Visualizations
- Survival distribution
- Survival probability by Sex
- Survival probability by Passenger Class
- Probability histogram for all passengers

## Insights
- Female passengers had higher survival probability
- Higher class (Pclass=1) had higher survival rates

## Dataset

- **Source**: Kaggle Titanic Dataset
- **Features**: PassengerId, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, Embarked
- **Target**: Survived (0 = No, 1 = Yes)

## Installation

```bash
git clone <repository-url>
cd Titanic-ml
pip install -r requirements.txt
```

## Usage

```python
python train.py
python predict.py
```
## License

MIT
