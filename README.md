# Anserini Notebooks

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/castorini/anserini-notebooks/master)
[![Generic badge](https://img.shields.io/badge/Lucene-v8.3.0-brightgreen.svg)](https://archive.apache.org/dist/lucene/java/8.3.0/)
[![Maven Central](https://img.shields.io/maven-central/v/io.anserini/anserini?color=brightgreen)](https://search.maven.org/search?q=a:anserini)
[![PyPI](https://img.shields.io/pypi/v/pyserini?color=brightgreen)](https://pypi.org/project/pyserini/)

This repo holds static copies of notebooks for the [Anserini](https://github.com/castorini/anserini) IR toolkit (Java) and [Pyserini](https://github.com/castorini/pyserini) (Python interface to Anserini).
There are two ways to play with the notebooks here, using Colab and Binder.

## Colab

The notebooks in this repo are sync'ed (by hand) with notebooks in Colab.
These online demos provide a low-effort way to try out Anserini and Pyserini features:

+ Anserini demo on Robust04: [[Colab]](https://colab.research.google.com/github/castorini/anserini-notebooks/blob/master/anserini_robust04_demo.ipynb) [[GitHub]](anserini_robust04_demo.ipynb)
+ Pyserini demo on Robust04: [[Colab]](https://colab.research.google.com/github/castorini/anserini-notebooks/blob/master/pyserini_robust04_demo.ipynb) [[GitHub]](pyserini_robust04_demo.ipynb)
+ Pyserini demo on MS MARCO passage ranking task: [[Colab]](https://colab.research.google.com/github/castorini/anserini-notebooks/blob/master/pyserini_msmarco_passage_demo.ipynb) [[GitHub]](pyserini_msmarco_passage_demo.ipynb)

These are older notebooks that aren't being maintained anymore:

+ Pyserini Demo on COVID-19 Dataset (Title + Abstract Index): [[Colab]](https://colab.research.google.com/github/castorini/anserini-notebooks/blob/master/pyserini_covid19_default.ipynb) [[GitHub]](pyserini_covid19_default.ipynb)
+ Pyserini Demo on COVID-19 Dataset (Paragraph Index): [[Colab]](https://colab.research.google.com/github/castorini/anserini-notebooks/blob/master/pyserini_covid19_paragraph.ipynb) [[GitHub]](pyserini_covid19_paragraph.ipynb)
+ Pyserini+SciBERT Demo on COVID-19 Dataset (Title + Abstract Index): [[Colab]](https://colab.research.google.com/github/castorini/anserini-notebooks/blob/master/Pyserini%2BSciBERT_on_COVID_19_Demo.ipynb) [[GitHub]](Pyserini+SciBERT_on_COVID_19_Demo.ipynb)
+ Related Article Search on COVID-19 Dataset: [[Colab]](https://colab.research.google.com/github/castorini/anserini-notebooks/blob/master/covid19_related_article_search.ipynb) [[GitHub]](covid19_related_article_search.ipynb)

Click "Open in Playground" and you'll be able to replicate our results!

## Binder

This entire repo is configured with work with [Binder](https://mybinder.org/).
Click the "launch binder" icon on the top-left corner to initialize an executable environment around these notebooks.

## Pre-Built Indexes

For convenience, we've pre-built a few common indexes, available to download [here](https://git.uwaterloo.ca/jimmylin/anserini-indexes).

