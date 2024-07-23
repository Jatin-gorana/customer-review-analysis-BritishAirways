# British Airways Customer Review Analysis and Behavior Modeling

Project Overview

This project analyzes customer reviews of British Airways to gain insights and build a model to predict customer satisfaction. The aim is to understand customer sentiments, identify key themes, and predict satisfaction levels based on their feedback.
Analyses and Insights
Data Collection and Preprocessing

    Data Source: Online platforms.
    Cleaning: Removed duplicates and irrelevant data.
    Tokenization: Split reviews into individual words.
    Stop Words Removal: Removed common words to focus on important ones.

Sentiment Analysis

    Objective: Determine if reviews are positive, negative, or neutral.
    Method: Used NLP tools like NLTK or TextBlob.
    Result: Most reviews were positive, showing general customer satisfaction.

Topic Modeling

    Objective: Find main topics in the reviews.
    Method: Used LDA (Latent Dirichlet Allocation).
    Key Topics: Flight experience, customer service, in-flight amenities, punctuality.

Word Cloud Visualization

    Objective: Show frequently mentioned words.
    Tool: WordCloud library.
    Insight: Words like "service," "staff," "comfortable," and "delay" were common.

Predictive Modeling

    Objective: Predict customer satisfaction from review text.
    Method:
        Feature Extraction: Used TF-IDF to convert text to numbers.
        Model: Trained a Random Forest classifier.
        Evaluation: Checked accuracy, precision, recall, and F1-score.
    Result: The model accurately predicts customer satisfaction.

Customer Segmentation

    Objective: Group customers by review sentiments.
    Method: Used K-Means clustering.
    Segments Identified:
        Highly Satisfied: Positive reviews.
        Neutral: Mixed reviews.
        Dissatisfied: Negative reviews.

Monthly Trends Analysis

    Objective: Find trends in reviews over months.
    Tool: Line charts.
    Insight: Peaks in reviews during holiday seasons.

Tools and Technologies

    Data Processing: Python (Pandas, NumPy)
    NLP: NLTK, TextBlob, Scikit-learn
    Visualization: Matplotlib, Seaborn, WordCloud
    Modeling: Scikit-learn (Random Forest, K-Means)
    Data Source: Link was provided in task
