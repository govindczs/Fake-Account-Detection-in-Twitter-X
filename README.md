# Fake Account Detection in Twitter/X

## Overview
This project focuses on detecting fake accounts on Twitter/X using multiple machine learning algorithms. The dataset includes various behavioral and interaction-based features to classify accounts as real or fake.

## Implemented Algorithms
The following six algorithms have been implemented for fake account detection:
1. Enhanced Graph-based Semi-supervised Learning Algorithm (EGSLA)
2. Support Vector Machine (SVM) & Neural Network (NN) Hybrid Model
3. Word2Vec with XGBoost
4. Random Forest Classifier
5. Binary Logistic Regression
6. Naive Bayes Classifier

## Dataset
The dataset consists of the following columns:
- User ID: Unique identifier for the user.
- No Of Abuse Report: Number of abuse reports against the user.
- No Of Rejected Friend Requests: Number of friend requests rejected by others.
- No Of Friend Requests That Are Not Accepted: Sent friend requests that were not accepted.
- No Of Friends: Number of friends the user has.
- No Of Followers: Number of followers the user has.
- No Of Likes To Unknown Account: Number of likes given to unknown accounts.
- No Of Comments Per Day: Number of comments made per day.
- Fake Or Not Category: Binary label indicating whether the user is fake (1) or real (0).

## Repository Structure
The repository contains the following files:
- EGSLA_FINAL.ipynb – Implementation of the Enhanced Graph-based Semi-supervised Learning Algorithm.
- SVM_NN_final.ipynb – Implementation of the Support Vector Machine & Neural Network hybrid model.
- Word2Vec_XGBOOST.ipynb – Implementation of Word2Vec with XGBoost.
- README.md – Documentation for the project.

## Installation
To run the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Fake-Account-Detection-in-Twitter-X.git
   cd Fake-Account-Detection-in-Twitter-X
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebooks to train and evaluate models.

## Usage
- Open the respective Jupyter Notebook files (.ipynb) in Google Colab or Jupyter Notebook.
- Run the cells to execute the models.
- Modify hyperparameters within the notebooks if necessary.

## Results
Each model has been evaluated based on:
- Accuracy
- Precision
- Recall
- F1-score

Detailed results and model performance comparisons are provided in the results/ directory (to be added).

## Future Work
- Add implementations for Random Forest, Binary Logistic Regression, and Naive Bayes.
- Improve feature engineering for better classification.
- Experiment with deep learning-based approaches.
- Integrate real-time Twitter/X data using APIs.

## Contributors
- Rahulappu2004 ([GitHub Profile](https://https://github.com/Rahulappu2004/))

## License
This project is licensed under the MIT License - see the LICENSE file for details.

---
Feel free to contribute and improve this project!

