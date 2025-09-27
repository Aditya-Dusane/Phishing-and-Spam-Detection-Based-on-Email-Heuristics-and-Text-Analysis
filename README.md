🎣 Phishing and Spam Detection: Email Heuristics & Text Analysis
🎯 Overview
This project implements a machine learning system designed to detect and classify malicious emails (Phishing) and unwanted messages (Spam) by analyzing two key areas:

Email Heuristics: Structural features like URL length, domain characteristics, and the use of IP addresses.

Text Analysis (NLP): Linguistic features extracted from the email body and subject line, including suspicious keywords and sentiment.

The primary goal is to provide a highly accurate and explainable defense layer for email security.

🛠️ Key Technologies
Language: Python

Machine Learning: Scikit-learn, Gradient Boosting Classifier (Top Performer)

NLP & Data: NLTK, Pandas, NumPy

Exploration: Jupyter Notebook (Phishing URL Detection.ipynb)

📊 Performance Summary
After extensive feature engineering and model comparison, the Gradient Boosting Classifier achieved the highest performance.

Metric

Result

Accuracy (URL Detection)

~97.4%

Key Predictive Features:

HTTPS Status: Whether the website uses a secure connection.

Anchor URL Ratio: The proportion of links pointing to external domains.

Website Traffic: An indicator of site novelty or obscurity.

🚀 Quick Setup
To run the analysis locally, clone the repository and install dependencies:

# Clone the repository
git clone https://github.com/Aditya-Dusane/Phishing-and-Spam-Detection-Based-on-Email-Heuristics-and-Text-Analysis.git

# Install required libraries
pip install -r requirements.txt

# Run the notebook for full analysis
jupyter notebook Phishing URL Detection.ipynb

🤝 Contact
Aditya Dusane
www.linkedin.com/in/aditya-dusane
