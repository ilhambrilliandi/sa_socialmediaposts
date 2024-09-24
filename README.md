# Sentiment Analysis: Social Media Posts

In this project i try to analyze the sentiment from 3 social media platforms (Facebook, Instagram, Twitter) using BERT method. This method categorize the text into 5 different levels:
1 = negative
2 = somewhat negative
3 = neutral
4 = somewhat positive
5 = positive

here's the required specific libraries for this project:
- transformers
- torch
- re

Overview:
- Each platform has different user's behaviour. While Twitter's users' traffic mostly occured in last days of the month, Facebook and Instagram relatively spread across the entire month.
- The users' traffic suddenly peaked at 2023 on all platforms.
- The model finds that across all platforms, most of the posts' sentiment is positive, followed by negative. Shows that posts are rarely neutral.
- Need to take a note that this model doesn't accurately spot the ambiguous sentences such as sarcasms.
