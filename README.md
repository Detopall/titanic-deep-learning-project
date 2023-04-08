# Titanic Surviving Kaggle - Deep Learning Project

This project aims to predict the survival of passengers of the Titanic using a basic Neural Network with TensorFlow. The dataset taken from the Titanic Kaggle dataset that contains 12 features from the passengers.

I've also made a file for the submission and a picture with the submission scores.

The ``prediction.ipynb`` contains ``Regularisation``, ``Batch Normalization`` and ``Babysitting``. There are different models create to find the best model.

## Usage

Execute this command to use the same virtual environment that I used. This will also install all the packages that I used and the right versions.

```bash
pipenv install
```

If you want to retrain and retest the model and data-cleaning file you can execute the cells from these files:

```bash
data_cleaning.ipynb
&
prediction.ipnb
```

All the cells have already been executed, so the output is already visible. There is also a folder named ``html_notebooks`` that contains the html version of the notebooks.

## Results

You can find the classification_report in the ``classification-report.png``. You can also find the results of the Kaggle submission under the name ``submission_score.png``.
