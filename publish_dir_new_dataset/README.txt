FakeNewsNet : A Data Repository with News Content, Social Context andSpatiotemporal Information for Studying Fake News on Social Media


The dataset include following files:
1) politifact_fake.csv -  Samples related to fake news collected from PolitiFact
2) politifact_real.csv -  Samples related to real news collected  from PolitiFact
3) gossipcop_fake.csv - Samples related to fake news collected from GossipCop
4) gossipcop_real.csv - Samples related to real news collected from GossipCop

Each of the above CSV files are comma separated files and have the following columns
a) id - unique identifider added for each sample
b) url - Url of the article from web that published that news 
c) title - Title of the news article found in the URL
d) tweet_ids - Tweet ids of tweets related to news sample posted on Twitter. This field is list of tweet ids separated by tab.


Social engagements and user information are not disclosed because of Twitter Policy. The code for collecting social engagements from Twitter will be published on GitHub.
