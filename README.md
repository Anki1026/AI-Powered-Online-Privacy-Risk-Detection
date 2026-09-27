# AI-Powered Online Privacy Risk Detection System

## Project Overview
This project explores how Natural Language Processing (NLP) and Machine Learning can be used to identify potential privacy risks in social media text. It classifies text into three risk levels: **Low, Medium, and High**, based on patterns that may indicate the disclosure of personal or sensitive information.

## Objectives
- Identify potential privacy-related information in social media posts.
- Classify posts into Low, Medium, and High privacy-risk categories.
- Apply and compare different Machine Learning and NLP models.
- Explore the use of transformer-based models for privacy-risk classification.

## Tech Stack
- Python
- Pandas and NumPy
- Scikit-learn
- Natural Language Processing (NLP)
- TF-IDF
- Hugging Face Transformers
- BERT
- Google Colab

## Project Workflow
1. Load and explore the dataset.
2. Preprocess and prepare the text data.
3. Assign privacy-risk labels using rule-based patterns.
4. Convert text into features for Machine Learning models.
5. Train and evaluate classification models.
6. Explore BERT-based text classification.
7. Compare model performance using evaluation metrics.

## Models Explored
- Logistic Regression
- Naive Bayes
- Support Vector Machine (SVM)
- BERT

## Results
- BERT achieved 99.4% accuracy in the reported research experiment.
- Multiple Machine Learning models were explored and evaluated.

**Important:** The privacy-risk labels were generated using rule-based patterns. Therefore, the reported accuracy measures how well the models predict these assigned labels; it does not by itself establish real-world privacy-risk detection accuracy.

## Dataset
- The project uses the [Sentiment140 dataset](https://www.kaggle.com/datasets/kazanova/sentiment140), which contains Twitter posts for sentiment analysis.
- The dataset is not included in this repository. To run the notebook, download the dataset from Kaggle and upload the CSV file when prompted in Google Colab.
- Please ensure that you comply with the dataset's applicable terms of use.

## How to Run
1. Open the notebook in Google Colab.
2. Obtain the required dataset.
3. Run the notebook cells in order.
4. Upload the dataset when prompted.
5. Review the preprocessing steps, model training, and evaluation results.

A GPU runtime is recommended for the BERT section.

## Limitations
- Labels are generated using predefined rules and may not capture every form of privacy risk.
- Model performance depends on the dataset, preprocessing, and labeling approach.
- High accuracy against rule-generated labels does not necessarily translate to performance on real-world privacy risks.
- Further validation using human-reviewed labels and diverse datasets is needed.

## Future Improvements
- Validate labels with human annotation.
- Expand the dataset and evaluate on additional sources.
- Conduct detailed error analysis.
- Explore advanced transformer models.
- Improve the detection of contextual and less obvious privacy risks.

## Author
**Ankita Parameswaran**
