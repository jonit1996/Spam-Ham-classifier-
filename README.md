# Spam/Ham Email Classification Model

A machine learning model that classifies emails as either spam or ham (non-spam).

## Table of Contents

- [Introduction](#spamham-email-classification-model)
- [Usage](#usage)
- [Installation](#installation)
- [Data](#data)
- [Model](#model)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

  ## Usage

To classify an email as spam or ham, you can use the following command:

python classify_email.py -email <email_text>

## Installation

1. Clone this repository.
2. Install the required Python packages using pip:

## Data

We used the "Spam.csv" dataset for training and testing. You can find the dataset [here]( https://www.kaggle.com/datasets/tmehul/spamcsv ).

## Model

We employed a Multinomial Naive Bayes classifier for this email classification task. 
The model achieved an accuracy of 96% on the test dataset.

## Results

- Accuracy: 95%
- Precision: 96%
- Recall: 94%
- F1 Score: 95%

