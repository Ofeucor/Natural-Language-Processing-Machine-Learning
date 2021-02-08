# Task 2  - Classification - Natural Language Processing

This repository that contains the material related to analyze a Twitter collection from the computer engineering degree of the University of Castilla-La Mancha.


## Introduction

The purpose of this work is to use natural language process to analyze a Twitter collection about offensive language and hatred. Data used in this work comes from CrowdFlower, a company dedi-cated to acting as a mediator between companies and users whowill carry out mini-jobs. T

Our main objective, as we said previously, is to apply techniques of text and languageprocessing to discover useful and previously unknown “gems” ofinformation in large text collections, like we present, and implementand facilitate Sentiment Analysis tasks using NLTK features andclassifiersve this goal, we have first developed a baseline with simple regression techniques, on which we have subsequently made two lines of improvement.


## File hierarchy

In the following scheme you can see the directory structure of our repository, containing descriptions of each element.

```python
├── README.md                                                                     <- The top-level README for users using this project.
├── data
│   ├── @big.txt                                                            <- Data related to the features of the training dataset.
│   ├── @labeled_data.csv                                                   <- Data related to the labels of the training dataset.
│   ├── @refined_ngram.csv                                                  <- Data related to the features of the test dataset.
|   └── pickles
│       ├── preprocessed_tweets.pickle                                     <- Data related to the tweets after preprocessing.
|       └── other_features.pickle                                          <- Data related to other features that have been calculating during preprocessing.
│
├── notebook
│   └── Natural_Language_Processing_Machine_Learning.ipynb                  <- High line containing the model that gives us the best results.
│
└── reports      
    ├── report.pdf                                                                <- Report describing the process and techniques used.
    └── figures                                                                   <- Folder containing images of all the graphics generated in the notebooks.


```

## Reproducibility

In order to be able to reproduce our results, the first thing we will have to do is clone the repository on your local.  

To run our notebooks, you will have to open them with appropriate software such as [Jupyter Notebook](https://jupyter.org/) or [Google Colab](https://colab.research.google.com/), and run all the cells of that notebook. The only thing you will have to do is to load the files corresponding to the tweets, dictionary with weel-written words and another diccionary of some n-grams that you can find in tweets in the data load cells. 

Pre-processing tweets is a very time consuming process. For this, we use the Pickle library, load preprocessed data and other features.

Once every cell has been executed, you'll be able to visualize the results of applying various algorithms(SVM and Naive Bayes).

## Other links

Finally, here you can find some links that may be useful. These links correspond to the cloud versions of the notebook in the repository.

* [Natural_Language_Processing_Machine_Learning](https://colab.research.google.com/drive/1Ac2x9tCcSK9NRt0mN7oW5sais6gDQj5O?usp=sharing)
