# Twitter US Airline Sentiment Classification
---------------------------------------------------------

[![Python Version](https://img.shields.io/badge/Python-3.6+-blue.svg)](https://shields.io/) [![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity) [![Documentation Status](https://readthedocs.org/projects/ansicolortags/badge/?version=comingSoon)](http://ansicolortags.readthedocs.io/?badge=latest) 

:technologist: *by Lorenzo Mauri, Alessandro Vincenzi, Emanuele Rebesco*

:round_pushpin: *Data Science MSc, Università degli studi di Milano-Bicocca*

<a name = 'gruppo'></a> 
## Contatti

|Nome                | matricola   | email                       |
|--------------------|-------------|-----------------------------| 
|Alessandro Vincenzi | 800608      |a.vincenzi3@campus.unimib.it |
|Lorenzo Mauri       | 807306      |l.mauri28@campus.unimib.it   |
|Emanuele Rebesco    | 864006      |e.rebesco@campus.unimib.it   |



<a name = 'obiettivi'></a> 
## Obiettivi
------------
This project aims at developing three distinct machine learning model in order to classify Twitter's comments polarity (positive, negative and neutral). 
More specifically, the following models are implemented :

* Artificial Neural Network (ANN)

* Random Forest (RF)

* Support Vector Machine (SVM)

In addition, a `Text Augmentation` technique is employed to deal with the dataset's class imbalance problem and a wordcloud visualization is shown.


#### Report 
Further details are available at [Report.pdf](https://github.com/LorenzoMauri/Twitter-US-Airline-Sentiment-Classification/blob/main/Report.pdf)
(italian version)

<a name = 'dataset'></a> 
## Dataset
----------
The dataset is available here [Twitter US Airline Sentiment](https://www.kaggle.com/crowdflower/twitter-airline-sentiment) on Kaggle website.

<a name = 'requisiti'></a>
## Requirements
-------------

Per una corretta esecuzione del codice, verificare che tutte le librerie menzionate nel file [requirements.txt](https://github.com/LorenzoMauri/Twitter-US-Airline-Sentiment-Classification/blob/main/requirements.txt) siano installate.

## Risorse & how-to-run
-------------------------

* `Tweets.csv` : dati grezzi

* `twitterReviewsBalanced_Aug.csv` : dati elaborati e bilanciati con data augmentation

* `twitterReviewsBalanced_noAug.csv` : dati elaborati e bilanciati senza data augmentation

* `Text_Mining_preprocessing.ipynb`  : contiene il codice sorgente per l'elaborazione del testo. 
  * L'import dei dati grezzi viene svolto tramite un'istanza Colab collegata a Google Drive, perciò prima di effettuare ogni altra operazione è necessario autenticarsi con le proprie credenziali e fare il mount del Drive. Successivamente, modificare il `path` seguente (nella sezione `Import dati` del notebook) con il proprio percorso (in cui `Tweets.csv` risiede).

```
filePath = '/content/drive/MyDrive/text mining and search/twitter sentiment/Tweets.csv
```


* `Text_Mining_models.ipynb` : contiene il codice sorgente per la rappresentazione del testo, il training/test dei classificatori e le visualizzazioni di commenti positivi/negativi tramite wordcloud. 


  * Analogamente, per importare i dati è necessario cambiare il percorso nella sezione `Import dati`. Inoltre, al fine di generare correttamente le visualizzazioni wordcloud, è necessario importare il [logo di Twitter](https://github.com/LorenzoMauri/Twitter-US-Airline-Sentiment-Classification/blob/main/wordcloud_shape.jpg) e sostituire il percorso di tale immagine nello snippet seguente (presente nella sezione `Extra` del notebook)

```
twitter_mask = np.array(Image.open("/content/social-twitter-bird-symbol_318-27588.jpg"))
```





