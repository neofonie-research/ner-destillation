# Wissensdestillation für Named-Entity-Recognition (NER)

Dieses Repo ist eine Demonstration der grundlegenden Idee der Wissensdestillation - eine gängige Technik zur Modellkomprimierung. 

In dieser Demonstration haben wir [flair-english-large](https://huggingface.co/flair/ner-english-large) als Lehrermodell verwendet. 
Und [BBC News data](https://www.kaggle.com/datasets/gpreda/bbc-news) als unmarkierte Rohdaten. Der Lehrer markiert die unmarkierten Daten und überträgt dieses Wissen dann auf ein kleineres Modell.

Wenn Sie die in den Notebooks angegebenen Schritte befolgen, sollten Sie in der Lage sein, das Modell zu reproduzieren. 
