# 📈 Predict rating given product reviews on Amazon 

This project analyzes the Amazon Fine Food Reviews dataset, which consists of reviews of fine foods from Amazon. 
With 568,454 reviews from 256,059 users on 74,258 products, this dataset covers a timespan of 13 years, from Oct 1999 to Oct 2012.

🔎 EDA:
Take a look at the beautiful visualization of this dataset on this blog: 
https://nycdatascience.com/blog/student-works/amazon-fine-foods-visualization/

🎯 Objective:
The goal of this project is to determine whether a review is positive or negative. A rating of 4 or 5 is considered positive, while a rating of 1 or 2 is considered negative. Reviews with a rating of 3 are ignored.

🤔 How to determine if a review is positive or negative?
The Score/Rating of a review is used as a proxy way to determine the polarity of a review. However, it is important to note that this is an approximate way of determining the positivity or negativity of a review.

💻 Data Source:
You can find the dataset on Kaggle at:
https://www.kaggle.com/snap/amazon-fine-food-reviews

📊 Attributes:
- Id
- ProductId - unique identifier for the product
- UserId - unique identifier for the user
- ProfileName
- HelpfulnessNumerator - number of users who found the review helpful
- HelpfulnessDenominator - number of users who indicated whether they found the review helpful or not
- Score - rating between 1 and 5
- Time - timestamp for the review
- Summary - brief summary of the review
- Text - text of the review


🔍 Real world problem: Predict rating given product reviews on Amazon.

📊 Steps:

1️⃣ Dataset overview: Take a look at the Amazon Fine Food reviews dataset with EDA. 📈

2️⃣ Data Cleaning: Remove duplicates from the dataset. 🧹

3️⃣ Why convert text to a vector? To perform machine learning algorithms, text data needs to be converted to a numerical form. 🔢

4️⃣ Bag of Words (BoW): A common method to convert text to a vector is BoW. 🛍️

5️⃣ Text Preprocessing: Text needs to be preprocessed before applying BoW. Steps include stemming, stop-word removal, tokenization, and lemmatization. 📝

6️⃣ uni-gram, bi-gram, n-grams: N-grams are used to capture the context of words in the text. 🔠

7️⃣ tf-idf (term frequency-inverse document frequency): Another method to convert text to a vector is tf-idf, which captures the importance of a word in a document. 📈🔠

8️⃣ Why use the log in IDF? The log is used to reduce the effect of very high frequency words. 📉

9️⃣ Word2Vec: Word2Vec is a neural network-based approach to convert words to vectors. 🧠

🔟 Avg-Word2Vec, tf-idf weighted Word2Vec: Two variants of Word2Vec are avg-Word2Vec and tf-idf weighted Word2Vec. 🧮

1️⃣1️⃣ Bag of Words(code sample) 💻

1️⃣2️⃣ Text Preprocessing(code sample) 💻

1️⃣3️⃣ Bi-Grams and n-grams(code sample) 💻

1️⃣4️⃣ TF-IDF(code sample) 💻

1️⃣5️⃣ Word2Vec(code sample) 💻

1️⃣6️⃣ Avg-Word2Vec and TFIDF-Word2Vec(Code Sample) 💻

Thank you for checking out this project! 🙏

Note:
This Case-study/Project was covered in the Applied AI course.

Thank you for checking out this project! 🙏
