# Twitter US Airline Sentiment Classification
------------------------------------------------
*Data Science MSc, Università degli studi di Milano-Bicocca*

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


<a name = 'dataset'></a> 
## Dataset
----------
Il dataset considerato è il seguente [Twitter US Airline Sentiment](https://www.kaggle.com/crowdflower/twitter-airline-sentiment) , disponibile sulla piattaforma Kaggle.

<a name = 'requisiti'></a>
## Requisiti
-------------
Per una corretta esecuzione del codice, verificare che tutte le librerie menzionate nel file requirements.txt (in allegato) siano installate.

## Risorse & how-to-run
-------------------------

Il codice sorgente è presente all'interno dei seguenti file : 

* Text_Mining_models.ipynb : contiene la rappresentazione del testo, il training/test dei classificatori e la visualizzazioni di commenti positivi/negativi tramite wordcloud. 


* Text_Mining_preprocessing.ipynb  : contiene l'elaborazione del testo

I dati grezzi sono contenuti nel file Tweets.csv mentre i file twitterReviewsBalanced_Aug.csv e twitterReviewsBalanced_noAug.csv contengono il dato a seguito della fase di elaborazione (output del file Text_Mining_preprocessing.ipynb) 

