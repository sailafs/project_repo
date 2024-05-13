# Tutorial Modelling Data Titanic

Tutorial ini akan mengolah data titatic menjadi data yang siap dilakukan pemodelan

## Prerequisites

1. Download data [here](https://www.kaggle.com/competitions/titanic)
2. Instalasi menggunakan `pip install requirements.txt`

## Getting Started
- Dataset Splitting
- Training
- Model Validation

### Dataset Splitting
split data into traiing, validation, and test sets

```code
x_train, y_train, x_test, y_test = dataset_splitting()
x_train.shape, y_train.shape
```

## References
1. Di scikit-learn documentation