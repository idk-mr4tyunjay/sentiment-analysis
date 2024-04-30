**Sentiment Analysis**

---

**Table of Contents**
- [Introduction](#introduction)
- [Installation](#installation)
- [Authentication](#authentication)
- [Usage](#usage)
- [License](#license)

---

### Introduction

Sentiment Analysis, also known as opinion mining, is the process of computationally determining whether a piece of text is positive, negative, or neutral. This project demonstrates sentiment analysis using Python and Twitter data.

**Why Sentiment Analysis?**

- **Business**: Understand customer sentiment, product feedback, and brand perception.
- **Politics**: Analyze public opinion, detect consistency in government actions, and predict election results.
- **Public Actions**: Monitor social phenomena, detect potential risks, and gauge the general mood online.

### Installation

To run this project, you'll need:
- `Tweepy` for accessing Twitter API
- `TextBlob` for text processing
- Install using `pip install tweepy` and `pip install textblob`

### Authentication

To fetch tweets via Twitter API, create an app in your Twitter account, and obtain the required keys and tokens.

### Usage

1. Initialize `TwitterClient`.
2. Call `get_tweets` with the query term (e.g., "Donald Trump").
3. Analyze sentiment percentages and view positive/negative tweets.


### License

This project is licensed under the [MIT License](LICENSE).
