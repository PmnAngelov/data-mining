Sentiment Analysis 

Sentiment analysis, also referred to as opinion mining, is an approach to natural language processing (NLP) that identifies the emotional tone behind a body of text.

Using the Corpus operator, the movie_reviews.tab file is loaded. The dataset file contains movie reviews in text form. Preprocess Text operator is added to process the text data. Text is converted to lowercase, tokenized, and stopwords and punctuation are filtered out. 

<p align="center">
<img align="center" src="https://github.com/PmnAngelov/data-mining/blob/main/Text%20processing/imgs/c1.PNG" />
</p>

Two Corpus Viewers are added, one for visualizing the text data of the negative reviews (Corpus Viewer (negative)) and one for the positive ones (Corpus Viewer(positive)). They are each connected to Word Cloud tools to visualize the most common words.

<p align="center">
<img align="center" src="https://github.com/PmnAngelov/data-mining/blob/main/Text%20processing/imgs/c2.PNG" />
</p>

The Word Cloud (negative) depicting the most common words in negative movie reviews shows that the most frequently used words include:

<p align="center">
<img align="center" src="https://github.com/PmnAngelov/data-mining/blob/main/Text%20processing/imgs/c3.PNG" />
</p>

On the other hand, Word Cloud (positive), depicting the most common words in positive reviews, shows that the most frequently used words in them include:

<p align="center">
<img align="center" src="https://github.com/PmnAngelov/data-mining/blob/main/Text%20processing/imgs/c4.PNG" />
</p>

The total extracted words from negative reviews are 3785 in number, while those from positive reviews are 3642. Despite the smaller number of negative reviews, they contain more words than positive reviews.






