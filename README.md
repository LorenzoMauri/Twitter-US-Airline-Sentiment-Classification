# Twitter US Airline Sentiment Classification
---------------------------------------------------------
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
Questo lavoro è volto allo sviluppo di alcuni modelli di Machine Learning per la classificazione della polarità (positivo, negativo o neutro) delle recensioni di compagnie aeree presenti sulla piattaforma Twitter nel mese di Febbraio 2015. 
In particolare vengono implementati i seguenti classificatori : 

* Artificial Neural Network (ANN)

* Random Forest (RF)

* Support Vector Machine (SVM)

Inoltre viene proposta una tecnica di `Text Augmentation` con il fine di risolvere il problema di sbilanciamento delle classi e una rappresentazione wordcloud per i commenti positivi e negativi.

<img src = 'https://raw.githubusercontent.com/LorenzoMauri/Twitter-US-Airline-Sentiment-Classification/main/wordcloud_neg.PNG?token=ANZPV23M3QOGHWQSJW4GBH3AXJ364' width = 200 height = 200></img>

<img src = 'https://raw.githubusercontent.com/LorenzoMauri/Twitter-US-Airline-Sentiment-Classification/main/wordcloud_pos.PNG?token=ANZPV27X6IM2LQAUOIHGHA3AXJ4AU' width = 200 height = 200></img>

#### Relazione
Per ulteriori dettagli fare riferimento al [Report.pdf](https://github.com/LorenzoMauri/Twitter-US-Airline-Sentiment-Classification/blob/main/Report.pdf)

<a name = 'dataset'></a> 
## Dataset
----------
Il dataset considerato è il seguente [Twitter US Airline Sentiment](https://www.kaggle.com/crowdflower/twitter-airline-sentiment) , disponibile sulla piattaforma Kaggle.

<a name = 'requisiti'></a>
## Requisiti
-------------

Per una corretta esecuzione del codice, verificare che tutte le librerie menzionate nel file [requirements.txt](https://github.com/LorenzoMauri/Twitter-US-Airline-Sentiment-Classification/blob/main/requirements.txt) siano installate.

## Risorse & how-to-run
-------------------------

* `Tweets.csv` : dati grezzi

* `twitterReviewsBalanced_Aug.csv` : dati elaborati e bilanciati con data augmentation

* `twitterReviewsBalanced_noAug.csv` : dati elaborati e bilanciati senza data augmentation

* `Text_Mining_preprocessing.ipynb`  : contiene il codice sorgente per l'elaborazione del testo

* `Text_Mining_models.ipynb` : contiene il codice sorgente per la rappresentazione del testo, il training/test dei classificatori e le visualizzazioni di commenti positivi/negativi tramite wordcloud. 




