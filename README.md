Overview

The Resume Analyzer is an AI-powered application that classifies resumes into different job categories using Natural Language Processing (NLP) and Machine Learning (ML) techniques. It helps recruiters quickly screen and categorize resumes based on relevant job roles.



Features

Automated Resume Classification – Categorizes resumes into predefined job roles.

Preprocessing & Cleaning – Removes unnecessary text, symbols, and whitespace.

Machine Learning Model – Uses BERT for high-accuracy classification.




Dataset

The dataset was sourced from Kaggle.

It contains two columns:

Category – Job role the resume belongs to.
Resume – Full text of the candidate’s resume.




Model Training

Preprocessing:

Removed special characters, stopwords, and performed text normalization.

Tokenization using BERT tokenizer.


Training the Model:

Used BERT as a base model.

Fine-tuned for resume classification.

Achieved 95%+ accuracy on evaluation data.




Technologies Used

Python

BERT (Bidirectional Encoder Representations from Transformers)

scikit-learn

NLTK & Text Processing

Pandas & NumPy





Results

Accuracy: 95%+

Evaluation Metrics: Precision, Recall, F1-score all above 0.95
