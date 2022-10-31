# Sentiment Analysis
* Previews *
SmartSA is a strategy which conveys Social Network activities of famous tweet users.
Those tweets consist of at least a reply, 10 faves, and 5 retweets.

Tweets go into data normalizers and classify in a RoBERTa pre-trained model.
Softmax normalizes output into probabilities and annotate has Negative, Neutral, and Positive, respectively.
Finding max of each annotated label and produce a confidentiality level of final Market Analysis.
