# Deep-Learning-for-Sentiment-Analysis

In this project, I built a deep learning model to classify the sentiment of messages from [StockTwits](https://stocktwits.com/), a social network for investors and traders. My model is able to predict whether a particular message is positive or negative. From this, I generated a signal of the public sentiment for various ticker symbols.

### Overview

When deciding the value of a company, it's important to follow the news. For example, a product recall or natural disaster in a company's product chain. You want to be able to turn this information into a signal. Currently, the best tool for the job is a Neural Network.

For this project, I used posts from the social media site StockTwits. The community on StockTwits is full of investors, traders, and entrepreneurs. Each message posted is called a Twit. This is similar to Twitter's version of a post, called a Tweet. I built a model around these twits that generate a sentiment score.

To capture the degree of sentiment, I used a five-point scale: very negative, negative, neutral, positive, very positive. Each twit is labeled -2 to 2 in steps of 1, from very negative to very positive respectively. I built a sentiment analysis model that will learn to assign sentiment to twits on its own, using this labeled data.
