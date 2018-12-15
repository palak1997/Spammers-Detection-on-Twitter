# Spammers-Detection-on-Twitter
Online social networks (OSNs) are emerging communication medium for people to establish and manage social relationships. In OSNs, regularly billions of users are involved in social interaction, networking, recommendations, alerting, and social campaigns. With the increased popularity of online social networks, spammers find these platforms easily accessible to trap users in malicious activities by posting spam messages. Spammer is a person that perform scamming activities over the internet and tries to corrupt the social networks. 

With reference to twitter the spammers are users which posts harmful links , post links with unrelated tweets , post repeatedly to grab the attention of users , abuse the mention functions to post unwanted messages. The aim of most spammers is to grab the attention of other users. Specifically on Twitter, for every 21 tweets, one is spam and about 15% of active users are autonomous agents. Spams on Twitter not only affect the online social experience,but also threatens the safety of cyberspace. For example, in September 2014, New Zealand’s network was melt down due to a malware downloading spam , the result of which signaled the alarm of Twitter spams. So there is a need to find a solution so that people are saved from spammers.

In this work, Twitter is modeled as a directed graph G = (V ,A) which consists of a set V of nodes (vertices) representing user accounts and a set A of arcs (directed edges) that connect nodes. Each arc is an ordered pair of distinct nodes. An arc a = (i, j) is directed from vi to vj which stands for the user i is following user j. Twitter is not a mutual relationship. Any user can follow you and you do not have to approve or follow back. Thus twitter is modeled as a directed graph. The dataset was first processed and only the attributes which helped in the analysis were extracted . The two sets of spam users and non-spam users were combined in a table with an
attribute is_spam indicating 1 for a spam account and 0 for a non-spam account.
The features are extracted from different aspects which included graph-based features and content-based features.
Graph-based features :
Three features, which are the number of followees, the number of followers, and the reputation of a user are taken into account
Content-based features :
Features taken into account are , Replies and Mentions , Http Links and Trending Topics Further Machine learning algorithm SVM , Decision Tree and Random Forest have been applied on these features and the accuracy has been compared . Using the dataset and the features a model was built using machine learning algorithms like SVM , Decision tree and Random forest which have compared on the basis of accuracy.
Another feature has been introduced in the content-based feature in which the sentiment of the tweet text has been analysed using Textblob and the sentiment of the emoji used in the tweet has been analysed by giving it a score between -1 to 1 where -1 indicated extreme negative sentiment and 1 indicates extreme positive sentiment. The score for the emoji has been given manually where around 40 emojis are taken into consideration and mapped with their respective score. If the difference between the sentiments of the text and the emoji cross
a certain value then the user is reported spam.
