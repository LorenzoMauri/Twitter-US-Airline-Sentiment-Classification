# Twitter US Airline Sentiment Classification
---------------------------------------------------------

[![Python Version](https://img.shields.io/badge/Python-3.6+-blue.svg)](https://shields.io/) [![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity) [![Documentation Status](https://readthedocs.org/projects/ansicolortags/badge/?version=comingSoon)](http://ansicolortags.readthedocs.io/?badge=latest) 

:technologist: *by Lorenzo Mauri, Alessandro Vincenzi, Emanuele Rebesco*

:round_pushpin: *Data Science MSc, Università degli studi di Milano-Bicocca*

<a name = 'gruppo'></a> 
## Authors

|Nome                | matricola   | email                       |
|--------------------|-------------|-----------------------------| 
|Alessandro Vincenzi | 800608      |a.vincenzi3@campus.unimib.it |
|Lorenzo Mauri       | 807306      |l.mauri28@campus.unimib.it   |
|Emanuele Rebesco    | 864006      |e.rebesco@campus.unimib.it   |



<a name = 'obiettivi'></a> 
## Goals
------------
This project aims at developing three distinct machine learning models in order to classify Twitter's comments polarity (positive, negative and neutral). 
More specifically the following models are implemented :

* Artificial Neural Network (ANN)

* Random Forest (RF)

* Support Vector Machine (SVM)

Moreover a `Text Augmentation` technique is employed to solve the classes imbalance problem and a wordcloud visualization is presented.


#### Report 
Further details are available at [Report.pdf](https://github.com/LorenzoMauri/Twitter-US-Airline-Sentiment-Classification/blob/main/Report.pdf)
(italian version)

<a name = 'dataset'></a> 
## Dataset
----------
The dataset is available at the following link : [Twitter US Airline Sentiment](https://www.kaggle.com/crowdflower/twitter-airline-sentiment) ,  on Kaggle website.

<a name = 'requisiti'></a>
## Requirements
-------------

[requirements.txt](https://github.com/LorenzoMauri/Twitter-US-Airline-Sentiment-Classification/blob/main/requirements.txt) contains all the dependencies, please check it before running the code.

## Resources & how-to-run
-------------------------

* `Tweets.csv` : raw data

* `twitterReviewsBalanced_Aug.csv` : augmented dataset 

* `twitterReviewsBalanced_noAug.csv` : non-augmented dataset

* `Text_Mining_preprocessing.ipynb`  : jupyter notebook that contains the source code for data preprocessing. 
  * Data is imported via Google Colaboratory , so please make sure to mount the Drive before any other operation. Then         change the variable `filePath` (section : `Import dati` ) with your pathname (where `Tweets.csv`is located).

```
filePath = '/content/drive/MyDrive/text mining and search/twitter sentiment/Tweets.csv
```


* `Text_Mining_models.ipynb` : jupyter notebook that contains the source code for data modeling (training and validation steps) and visualization (wordclouds related to positive/negative tweets).

  * 	Please change  the pathname in the  `Import dati` section. In addition, in order to generate the wordcloud visualizations [logo di Twitter](https://github.com/LorenzoMauri/Twitter-US-Airline-Sentiment-Classification/blob/main/wordcloud_shape.jpg) is needed : change its pathname in the following snippet (`Extra` section)

```
twitter_mask = np.array(Image.open("/content/social-twitter-bird-symbol_318-27588.jpg"))
```





