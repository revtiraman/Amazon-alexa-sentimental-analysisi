# Amazon-alexa-sentimental-analysisi
# Amazon Alexa Review Sentiment Analysis

## Project Overview
This project analyzes the Amazon Alexa dataset and builds classification models to predict if the sentiment of a given input sentence is positive or negative. 

## Dataset
The dataset used is `amazon_alexa.tsv`, which contains reviews for Amazon Alexa products.

## Project Structure
- `sentiment_analysis.py`: The main code file containing data preprocessing, model training, and evaluation.
- `README.md`: This file, providing an overview and instructions.

## Requirements
- Python 3.7+
- Libraries: numpy, pandas, matplotlib, seaborn, nltk, scikit-learn

## Setup and Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/your_username/amazon-alexa-sentiment-analysis.git
    cd amazon-alexa-sentiment-analysis
    ```

2. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

3. Download the dataset and place it in the project directory.

## Running the Project
1. Ensure you have the dataset in the correct path.
2. Run the Python script:
    ```bash
    python sentiment_analysis.py
    ```

## Model and Evaluation
The project uses a RandomForestClassifier for sentiment analysis. The model's performance is evaluated using a confusion matrix and cross-validation.

## Hyperparameter Tuning
GridSearchCV is used for hyperparameter tuning to find the best parameters for the RandomForestClassifier.

## Results
The best parameters found for the RandomForestClassifier are displayed after running the grid search.

## License
This project is licensed under the MIT License.
