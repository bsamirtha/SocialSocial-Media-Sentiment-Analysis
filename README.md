# Social-Media-Sentiment-Analysis

Sentiment analysis enables businesses to uncover the emotions and opinions behind online mentions, providing valuable insights into public perception. By understanding these sentiments, companies can proactively address issues and enhance their brand's reputation. This system helps improve product offerings by identifying what resonates with customers and what doesn't. Marketers can analyze comments from review sites, survey responses, and social media posts to gain detailed insights into specific product features. These findings are then conveyed to product engineers, driving innovation and continuous improvement.

# Dataset 

For this project, we will be using the Sentiment140 dataset, available at [Kaggle](https://www.kaggle.com/datasets/kazanova/sentiment140). The dataset contains 1,600,000 tweets, extracted using the Twitter API, annotated for sentiment analysis. Each entry includes the following fields:

- **target:** Polarity of the tweet (0 = negative, 4 = positive)
- **ids:** Unique ID of the tweet (e.g., 2087)
- **date:** Date and time of the tweet (e.g., Sat May 16 23:58:44 UTC 2009)
- **flag:** Query used (e.g., lyx). If no query was used, this value is NO_QUERY.
- **user:** Username of the person who tweeted (e.g., robotickilldozr)
- **text:** Content of the tweet (e.g., Lyx is cool)

This dataset is invaluable for training models to detect sentiment in tweets, offering a rich source of annotated data for analysis.


# Key Leanings


1. **Effective Data Preprocessing**  
   Proper preprocessing, including tokenization, stemming/lemmatization, and removing stop words, is essential for accurate sentiment classification.

2. **Vectorization Techniques**  
   Selecting appropriate vectorization methods like `TfidfVectorizer` or `CountVectorizer` converts text into numerical data, which is crucial for model training.

3. **Sentiment Labeling and Interpretation**  
   Accurate sentiment labeling (positive, negative, neutral) and interpretation are vital for training models that reliably classify sentiments.

4. **Model Evaluation Metrics**  
   Use metrics such as accuracy, precision, recall, and F1-score to evaluate model performance and ensure it generalizes well to new data.
