# Sentiment Analysis Project

## Overview
This project implements a sentiment analysis system using various machine learning models. It processes textual data, extracts features, trains multiple classification models, and evaluates their performance in predicting sentiment.

## Features
- Data processing and feature extraction from raw text
- Implementation of multiple machine learning models:
  - Logistic Regression
  - Random Forest
  - Support Vector Machine (SVM)
  - Naive Bayes
- Model evaluation with various performance metrics
- Visualization of results including confusion matrices

## Installation
1. Clone this repository:
	```bash
	git clone https://github.com/reetmitra/Twitter-Sentiment-Analysis.git
	cd Twitter-Sentiment-Analysis
	```
2. Create a venv (Optional):
	```bash
	python -m venv venv
	source venv/bin/activate
	```
3. Install the required packages:
	```bash
	pip install -r requirements.txt
 	```

## Usage
1. Data Processing:
- Place your raw data in the `data/raw/` directory
- Run the data processing script:
  ```
  python src/data_processing.py
  ```

2. Feature Extraction:
- After data processing, run the feature extraction:
  ```
  python src/feature_extraction.py
  ```

3. Model Training:
- Train the models using:
  ```
  python src/model_training.py
  ```

4. Evaluation:
- Evaluate the trained models:
  ```
  python src/evaluation.py
  ```

## Results
The performance of each model is evaluated using the following metrics:
- Accuracy
- Precision
- Recall
- F1-score

Confusion matrices for each model are saved in the `figures/` directory.

## Models
1. **Logistic Regression**: A linear model for binary classification.
2. **Random Forest**: An ensemble learning method using multiple decision trees.
3. **Support Vector Machine (SVM)**: A powerful algorithm for both linear and non-linear classification.
4. **Naive Bayes**: A probabilistic classifier based on applying Bayes' theorem.

## Future Work
- Implement deep learning models (e.g., LSTM, BERT)
- Experiment with different feature extraction techniques
- Develop a web interface for real-time sentiment analysis
- Explore multi-class sentiment classification

## Contributing
Contributions to this project are welcome! Please fork the repository and submit a pull request with your proposed changes.

## Contact
Your Name - your.email@example.com

Project Link: [https://github.com/reetmitra/Twitter-Sentiment-Analysis](https://github.com/reetmitra/Twitter-Sentiment-Analysis)
	   
