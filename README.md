# password-strength-and-sentiment-predictor-using-NLP
Customer Sentiment Predictor is a project that aims to analyze customer reviews and predict their sentiment using natural language processing (NLP) techniques. The project involves data pre-processing, data modeling, and analyzing the sentiment of customer reviews.

Project Overview
The project consists of the following steps:

Data Pre-Processing: The raw customer review data is pre-processed to clean and prepare it for modeling. This involves importing necessary libraries such as pandas and numpy.

Data Loading: The customer review data is loaded from a CSV file using the pandas library.

Feature Engineering: Additional features are created based on the existing data. In this case, a "Helpful%" feature is calculated by dividing the HelpfulNumerator by the HelpfulnessDenominator.

Categorizing Upvotes: The "Helpful%" values are categorized into different groups using pandas' cut function. The categories represent different ranges of upvote percentages.

Analyzing Upvotes: The upvotes are analyzed based on different scores using a pivot table and a heatmap. This allows for a visual representation of the relationship between scores and upvotes.

Applying Bag of Words: The customer review text is converted into numerical vectors using the Bag of Words technique from the sklearn library.

Model Training and Testing: The data is split into training and testing sets. A logistic regression model is trained on the training data and evaluated on the testing data.

Top Positive and Negative Words: The coefficients of the trained logistic regression model are used to identify the top positive and negative words associated with customer sentiment.

Getting Started
To get started with the Customer Sentiment Predictor project, follow these steps:

Clone the repository: git clone https://github.com/ssharmapavitra/Natural-Language-Processing.git
Install the required dependencies: pip install -r requirements.txt
Run the project: python main.py
Requirements
Python 3.7+
pandas
numpy
scikit-learn
seaborn
Dataset
The project uses a dataset containing customer reviews, which is stored in a CSV file. The CSV file should be placed in the project directory with the filename "Reviews.csv".

Results
The project provides insights into customer sentiment based on their reviews. It includes visualizations of the relationship between review scores and upvotes, as well as the top positive and negative words associated with customer sentiment.

Contributing
Contributions to the Customer Sentiment Predictor project are welcome. If you encounter any issues or have suggestions for improvement, please create an issue or submit a pull request.

Acknowledgments
The project is based on the concept of natural language processing and sentiment analysis.
The dataset used in this project is sourced from Amazon Customer Reviews.
About
Customer Sentiment Predictor is a 
