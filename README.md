# Natural Language Processing Project

This repository contains information about the modules that were used in the realisation of a "Multi Language Question-Answer Pipeline on different Corpora".
This project was realised in the NLP2 course of the Informatic Faculty of UPV, San Sebastian.

.

**The following corpora for the Information Retrieval modul have been used:**

Wikipedia Abstract Dump, cleaned:
https://dumps.wikimedia.org/enwiki/latest/

Kaggle simple/normal Wikipedia Abstracts:
https://www.kaggle.com/datasets/markwijkhuizen/simplenormal-wikipedia-abstracts-v1

Covid19 passages
https://github.com/allenai/cord19

.

**For the implementations following modules were used:**

Language Identification: FastText
https://fasttext.cc

Machine Translation: Transformer Models created by the Language Technology Research Group at the University of Helsinki
https://huggingface.co/Helsinki-NLP

Information Retrieval:
Whoosh library using Okapi BM25 algorithm (BM-> Best Matching)
https://whoosh.readthedocs.io/en/latest/intro.html


Question Answering:
https://huggingface.co/bert-large-uncased-whole-word-masking-finetuned-squad
