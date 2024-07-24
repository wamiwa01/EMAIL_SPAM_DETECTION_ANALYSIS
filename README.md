# EMAIL_SPAM_DETECTION_ANALYSIS

Email spam detection is used to identify and filter out spam emails from the bulks emails our inbox receives everyday. It separate the emails into SPAM and Not Spam. Keeping our inbox safe from possible threat and harm. Machine learning algorithms can be trained to filter out spam mails based on their content.

## DESCRIPTION

• The project code completely done using Python on Jupyter Notebook

• Started with 2962 observations and 2 columns

## STEPS TAKEN

• Installing and Importing Libraries

     Installing and importing all necessary libraries like Pandas, re, Matplotlib, NLTK, Wordcloud, Sklearn
     
• Data cleaning

    Converting Spam column dtype float to integer, Writing a function that removes url links, emails,
    hashtags, excess whitespaces in the email column
    Dropped duplicates etc

• Exploratory Data Analysis (EDA)

    Viewing the proportion of spam to not spam
    
• Data Visualization

    Distribution of Spam and not spam using numbers of characters and number of words.
    wordcloud of most common word used in Spam and not spam

• Machine learning: Training and Testing of Models

    Created a function that trains model, x train, x test, y train, y test
    to fit the model, then make predictions on the trained model.

• Machine Learning Model: Multinomial Naive Bayes

    Create a machine learning pipeline using scikit-learn, combining text vectorization (CountVectorizer) 
    and a Multinomial Naive Bayes classifier for email spam detection.
    
    Visualising confusion matrix by heatmap to get clear performance of the classification model 
    and then performed Data Preprocessing, NLP, Classification and Classification report

• Spam Email detection teating

    Test the prediction to confirm if it successfully clasify the email into each category of Spam and Not spam
