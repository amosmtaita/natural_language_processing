# Language Modelling 

## Overview
We include different notebooks to provide the student with practical means to explore language models and transformers, as well as their application in NLP tasks like wotd-sense disambiguation. We follow an incremental approach in accordance with the contents of session 6 of the course, focused on semantics.

## N-gram based language models
In [this notebook](https://github.com/acastellanos-ie/natural_language_processing/blob/master/language_modelling/language%20modelling.ipynb) we are going to start playing with languages models. In particular, we are going to start with the simplest approach based on n-grams. Then, in the following threads, we will move to more advanced approaches based on LSTM and Transformer architectures.

## ELMo

In [this other notebook](https://github.com/acastellanos-ie/natural_language_processing/blob/master/language_modelling/language%20modelling_elmo.ipynb) we can review an implementation of a sentiment analyzer leveraging the representation provided by ELMo.

## Fine-tuning pre-trained transformers for text classification
Fine-tuning pre-trained language models learnt with transformers has improved the state of the art in multiple NLP evaluation tasks. In [this notebook](https://github.com/hybridnlp/tutorial/blob/master/01a_nlm_and_contextual_embeddings.ipynb) we fine tune a pre-trained  BERT language model to carry out a binary classification task where tweets are labelled as generated by bots or hurmans.

## Using transformers for word-sense disambiguation
In [this notebook](https://github.com/hybridnlp/tutorial/blob/master/03a_LMMS_Transigrafo.ipynb) we show an implementation of Transigrafo as a extension of the code for Language Modelling Makes Sense (LMMS), presented at ACL 2019, which uses contextual embeddings in Word Sense Disambiguation (WSD) tasks.

## Additional resources
The last two notebooks are part of the tutorial [Hybrid Techniques for Hybrid Natural Language Processing](http://hybridnlp.expertsystemlab.com/tutorial/). The complete lessons, materials and resources of the tutorial can be found [here](http://hybridnlp.expertsystemlab.com/tutorial/index.php/sample-page/). You can find all the notebooks of the tutorial in its [repo](https://github.com/hybridnlp/tutorial). The following book is also focused on the concepts illustrated here: _Jose Manuel Gomez-Perez, Ronald Denaux and Andres Garcia-silva. 2020. A Practical Guide to Hybrid Natural Language Processing - Combining Neural Models and Knowledge Graphs for NLP. https://doi.org/10.1007/978-3-030-44830-1_

