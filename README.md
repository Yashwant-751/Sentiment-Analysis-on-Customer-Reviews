Overview
This project demonstrates how to perform sentiment analysis on customer reviews using Python. The goal is to analyze the sentiment of the reviews to gauge overall customer satisfaction and identify areas for improvement. The project utilizes basic Natural Language Processing (NLP) techniques with the help of Python libraries such as TextBlob, Pandas, and Matplotlib.

Features
Text Preprocessing: Converts text to lowercase for uniformity.
Sentiment Analysis: Classifies reviews as Positive, Neutral, or Negative using the TextBlob library.
Data Visualization: Visualizes the distribution of sentiments using a bar chart.
Installation
Prerequisites
Python 3.x
Required Python Libraries:

pip install pandas textblob matplotlib
Usage
Prepare the Dataset:

Create a reviews.csv file containing customer reviews with a single column named Review.
Example:
csv

Review
"I love this product! It's amazing."
"The product is okay, not great."
"I am very disappointed with this purchase."
"Absolutely fantastic, will buy again."
"Terrible experience, not recommended."
Run the Script:

Save the Python code in a file named sentiment_analysis.py.
Execute the script:

python sentiment_analysis.py
Output:

The script will load and preprocess the reviews, perform sentiment analysis, and display a bar chart showing the distribution of sentiments.
A summary of the sentiment breakdown will be printed in the console.
Conclusion
This project is a simple yet effective way to understand and practice sentiment analysis using Python. It is ideal for beginners who want to get started with NLP and data analysis.

License
This project is open-source and available under the MIT License.
