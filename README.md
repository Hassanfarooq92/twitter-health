# health-tweets
Python Anaconda platform has been used for labelling and classification. Dataset consists of tweets related to health from different news channels. Data-set consisted of approx. 60,000 tweets combined from all sources.
Code consists of two sessions. one for pre-processing and one for classification. Pre processing also involves topic modeling from tweets and assigning the highest probability topic to given tweet.

  - Pre-processing and topic modeling (pre-processing,topic_modeing Genism.ipynb)
  - Classification  (KNN roccio naive-bayes.ipynb)

# Topic Modeling!
Major challenge with this data set was un-labelled tweets. So, we’ve applied LDA (Latent Dirichlet Allocation) for topic modelling of these un-labelled tweets. 

Just like value of k, in LDA we have to adjust value of number of topics to a point where clusters are well formed. In our case, 4 was opt imal number of topics without cluster-overlapping:
