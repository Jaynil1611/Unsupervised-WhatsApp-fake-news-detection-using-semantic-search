# Unsupervised-WhatsApp-fake-news-detection-using-semantic-search

Implementation of my paper : https://ieeexplore.ieee.org/document/9120902

Social media has become the backbone of today’s lifestyle. One of the well-known social media applications WhatsApp Messenger is a free and cross-platform text messaging software that also provides services for sending and receiving multimedia messages. But at the same time in recent years, its easy accessibility has served a way for propagating fake and biased news articles, blogs and messages. Fake news and messages have paved their way for Political polarization, ethnic tensions, unwanted panic and mass hysteria. 

1. We propose a solution that uses Natural Language Processing for analysing the messages and leverages Transfer Learning Models to detect the authenticity of the information. <br>
2. Scanning the entire WhatsApp conversation using Selenium webdriver.<br>
3. Claims are filtered from the bulk of forwarded messages.<br>
4. Their authenticity is verified by checking news articles from trusted news sources and evaluating if they agree to the information we are checking.<br>
5. Perform Semantic search mechanism between each claim and associated news sources. <br>
6. The similarity comparison is done to predict the truthfulness of the claim.<br>
7. Depending upon the similarity the text is classified as fake or truth and links for provided for relevant news articles.<br>
