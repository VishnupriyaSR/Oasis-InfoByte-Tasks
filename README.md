Email spam detection is a crucial task in machine learning and natural language processing.Spam e-mail detection is critical for protecting customers from unsolicited and potentially harmful information that can clog their inboxes and compromise their security. Mails are Categorized as 'Spam' or 'Ham' in the dataset. By performing analysis and applying machine learning algorithms for building the predictive system, the model will predict the upcoming mail as spam or ham according to the research on the data.

# Steps

# 1. Data Collection
   
Spam Emails Dataset: Collect a dataset containing both spam and non-spam (ham) emails. Popular datasets include the Enron Spam Dataset and the SpamAssassin Public Corpus.

# 2. Data Preprocessing

Text Cleaning: Remove special characters, numbers, and punctuation. Convert text to lowercase.

Tokenization: Split text into individual words or tokens.

Stopwords Removal: Remove common words that don't add much meaning (e.g., "the", "is").

Stemming/Lemmatization: Reduce words to their base or root form.

# 4. Feature Extraction

Bag of Words: Represent text data as a matrix of token counts.

TF-IDF (Term Frequency-Inverse Document Frequency): Weigh words based on their importance in the document relative to the entire corpus.

# 5. Model Selection

Used MB model for detection.Multinomial Naive Bayes (Multinomial NB) is a variant of the Naive Bayes classifier suited for categorical data, particularly for text classification problems. 

It works well for text data where features are counts or frequencies of words, such as in spam detection.

# 6. Training and Evaluation

Train-Test Split: Divide data into training and testing sets.

Metrics: Evaluate the model using accuracy, precision, recall, F1-score, and ROC-AUC.

# 7. Deployment

Integrate the trained model into an email system to classify incoming emails in real-time.
