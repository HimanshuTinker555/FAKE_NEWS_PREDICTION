# FAKE_NEWS_PREDICTION
## Introduction
Develop a machine learning program to identify when a news source may be producing fake news. We aim to use a corpus of labeled real and fake new articles to build a classifier that can make decisions about information based on the content from the corpus. The model will focus on identifying fake news sources, based on multiple articles originating from a source. Once a source is labeled as a producer of fake news, we can predict with high confidence that any future articles from that source will also be fake news.


## Dataset Description
* train.csv: A full training dataset with the following attributes:
  - id: unique id for a news article
  - title: the title of a news article
  - author: author of the news article
  - text: the text of the article; could be incomplete
  - label: a label that marks the article is fake or real
    ^ 1 : Fake News
    ^ 0 : real News
* test.csv: A testing training dataset with all the same attributes at train.csv without the label.
