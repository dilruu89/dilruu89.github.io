## Tweet Sentiment Extraction (LSTM)

**Project Link:** <https://github.com/dilruu89/Kaggle/blob/main/nlp-02-tweet-sentiment-extraction.ipynb>

**Project description:** Sentiment analysis is an automated technique that extracts insights from text data by categorizing them into positive, negative, or neutral polarities. It's widely applied to interpret customer feedback, survey responses, and product reviews. Consequently, organizations can measure public sentiment about their products, brands, or services through online conversations.

Analyzing tweets serves as a method to understand public opinion about topics, products, or services. Companies employ this approach to gain insights for informed decisions. This project focuses on extracting sentiment from tweets, aiming to distinguish the emotional context within a series of posts.

For this study, I've selected Kaggle's Tweet Sentiment Extraction competition dataset, containing around 27,500 tweets.

```javascript
data = pd.read_csv('/kaggle/input/tweetsentiment/train.csv')

```

### Techniques/ Algorithms / Metrics

In the beginning stages, I performed Exploratory Data Analysis (EDA). This was followed by the selection of important features, construction of the model, and subsequently evaluation of its performance. The primary techniques applied for model creation and performance assessment are as follows.

1. Logistic Regression
2. Correlation Analysis
3. Backward Feature selection
4. Confusion Matrix
5. ROC curve
