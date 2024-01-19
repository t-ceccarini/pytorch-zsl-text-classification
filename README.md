# Zero-Shot Learning text classification
Tutorials on Zero-Shot Learning techniques for text classification using Pytorch and HuggingFace.

## Tutorials
* 1 - [Sentiment Analysis on Italian Tweets](https://github.com/t-ceccarini/pytorch-zsl-text-classification/blob/master/sentiment_analysis_twitter.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/t-ceccarini/pytorch-zsl-text-classification/blob/master/sentiment_analysis_twitter.ipynb)

    In this tutorial we'll be building a machine learning model for the sentiment analysis of italian tweets. Further details on the sentipolc dataset used can be found [here](https://www.evalita.it/campaigns/evalita-2016/tasks-challenge/sentipolc/). We'll focus only on the polarity classification task.

* 2 - [Zero-shot text classification](https://github.com/t-ceccarini/pytorch-zsl-text-classification/blob/master/zero_shot_text_classification.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/t-ceccarini/pytorch-zsl-text-classification/blob/master/zero_shot_text_classification.ipynb)

    Here we'll explore two techniques for text classification: the first one in which the problem of text classification is defined as NLI problem as explained [here](https://joeddav.github.io/blog/2020/05/29/ZSL.html). Next we experiment with the [LASER](https://github.com/facebookresearch/LASER) library to calculate and use multilingual sentence embeddings and test the transfer capabilities of this approach. In particular we used the [pip-packaged ported version](https://github.com/yannvgn/laserembeddings) of this library.
