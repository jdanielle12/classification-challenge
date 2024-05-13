# Spam Classification Challenge 

## Overview
This project aims to build and evaluate machine learning models for classifying emails as spam or not spam. This project utilizes a dataset containing various feautres extracted from emails, such as word frequencies and character frequencies, along with a binary target variable indicating whether each email is spam or not.

## Features
* The dataset contains the following features:
  * `word_freq_make`: Frequency of the word "make" in the email
  * `word_freq_address`: Frequency of the word "address" in the email
  * ...
* Target Variable:
  * `spam`: Binary variable indicating whether the email is spam (1) or not spam (0)

## Setup Instructions
1. Clone the repository:
`git clone https://github.com/jdanielle12/classification-challenge.git`
2. Navigate to the project directory:
`cd classification-challenge`
3. Install the required dependencies:
`pip install -r requirements.txt`

## Requirements
* Python 3.x
* Jupyter Notebook
* pandas
* scikit-learn

## Usage
1. Open the files in any compatible environment
2. Execute the cells in the notebook to run the analysis, preprocess the data, train the machine learning models and evaluate the model performance

## Results
* Logistic Regression Model:
  * Accuracy: 0.9226759339704604 (roughly 92.27%)
* Random Forest Model:
  * Accuracy: 0.9582971329278888 (roughly 95.83%)

