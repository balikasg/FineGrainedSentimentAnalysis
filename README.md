# Fine Grained Sentiment Analysis

The repository contains the code (as a Jupyter Notebook) that I wrote for my Grenoble Data Science Meet-up presentation. 

I presented results for the task of Fine Grained Sentiment Analysis for tweets. In particular, the problem is as follows: 

- We are given a tweet
- We need to predict the sentiment of the tweet, that is one of {Very Negative, Negative, Neutral, Positive, Very Positive}

To run the experiments, you will first need to download the data: 

`
git clone https://github.com/balikasg/FineGrainedSentimentAnalysis.git
cd FineGrainedSentimentAnalysis
wget https://www.dropbox.com/s/qqvokdtalf0kgs2/2017_English_final.zip
unzip 2017_English_final.zip
`

This will download the repository to the directory "FineGrainedSentimentAnalysis" and also download the SemEval 2017 data and unzip them.

To run the experiments, you will need the Python Scientific modules (numpy, scipy, pandas, scikit-learn). The code was written with Python 2.7. 

Running the last cells of the notebook with the embeddings, needs downloading them. 
For English: https://github.com/facebookresearch/fastText/blob/master/pretrained-vectors.md
From the terminal:
`
wget https://s3-us-west-1.amazonaws.com/fasttext-vectors/wiki.en.zip
unzip wiki.en.zip
`
This requires a lot of space (>10GB). Also loading the embeddings and the model requires a lot of RAM, so take it into account. 
