Credit Card Fraud Detection

Purpose: The purpose of this project is to go through a dataset of credit card
transactions and clasify which of this transactions is Fraud

Dataset: Dataset is hosted by https://www.kaggle.com/mlg-ulb/creditcardfraud

Characteristics: I produced requerements.txt file using conda list --export > package-list.txt

Note: To install an anaconda enviroment with all this packages
conda create -n myenv --file Requerements.txt

Note 2: Variables
        'Class': 1 for Fraud and 'Class': 0  for no Fraud
        'Amount': Amount in Dollars of the Theft
        'V1-V30':m Scaled Varibles with PCA
