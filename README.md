# Sentiment-Analysis-Dashboard-on-Social-Media
This project analyzes and visualizes public sentiment from social media platforms using Natural Language Processing (NLP) and machine learning. It collects data in real-time, processes it to classify sentiment as positive, negative, or neutral, and displays the results on an interactive dashboard.

Features
Real-time social media data collection.
NLP-based text processing for sentiment classification.
Machine learning models for accurate analysis.
Interactive dashboard with visualizations like graphs and charts.
Technologies Used
Programming: Python
Libraries: scikit-learn, Pandas, Matplotlib, NLP libraries
Dashboard: Streamlit or Dash

Applications
Brand reputation tracking
Customer feedback analysis
Public opinion monitoring




Implementation for the project

Run these in your command prompt to make this run:

pip install flask pip install scikit-learn pip install nltk pip install pandas
The project is saved as follows:

project/ │ ├── sentimental_analysis.py #python backend code ├── templates/ # HTML files │ └── index.html ├── static/ # CSS, JS, images, etc. └── styles.css
Change file path to your CSV file in python code on line 39 accordingly.

Here, path to csv file is:- C:\Users\nimit\Downloads\twitter_training.csv
Things to save:- 1.sentimental_analysis.py 2.frontpage.css 3.frontpage.html 4.twitter-training.csv 5.Readme.txt

To run: run the sentimental_analysis.py in a compiler and go to 127.0.0.1;:5000 on your local browser

