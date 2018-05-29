# health-tweets
Python Anaconda platform has been used for labelling and classification. Dataset consists of tweets related to health from different news channels. Data-set consisted of approx. 60,000 tweets combined from all sources.
Code consists of two sessions. one for pre-processing and one for classification. Pre processing also involves topic modeling from tweets and assigning the highest probability topic to given tweet.

  - Pre-processing and topic modeling (pre-processing,topic_modeing Genism.ipynb)
  - Classification  (KNN roccio naive-bayes.ipynb)

## Topic Modeling!
Major challenge with this data set was un-labelled tweets. So, we’ve applied LDA (Latent Dirichlet Allocation) for topic modelling of these un-labelled tweets. 

Just like value of k, in LDA we have to adjust value of number of topics to a point where clusters are well formed. In our case, 4 was opt imal number of topics without cluster-overlapping.

To run this code, install python 3, using Anaconda.


1) Pandas
2) Numpy
3) Sklearn
4) nltk

### Installation

Install the dependencies and devDependencies in order to get the code working, using conda install or pip install:

```sh
$ pip install pandas
$ pip install numpy
$ pip install nltk
$ nltk.download(all)
$ pip install sklearn
```
### Running the code
After jupyter notebook installation, Using cmd, navigate to folder containing .ipynb files and Launch the notebook by using foolowing command

```sh
 $ jupyter notebook
 ```

then run click on pre-processing, topic modelling.ipynb from browser window opened by jupyter command. Now run thecode block by block and see the output. Download the packages while running the code when asked for. This code will create labels for given documents.

After labeling, Next open KNN Roccio Naive-bayes.ipynb. and execute block by block.
