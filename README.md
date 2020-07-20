# Predicting the Judiciary Decisions of the European Court of Human Rights
This study explores the use of natural language processing tools and the application of neural networks in order to predict the outcomes of cases presided over by the European Court of Human Rights. The objective of this project is to aid the European Court to identify outcomes automatically based on the facts of the case. Hence, given the full summary of a case, our task is to extract the relevant information and have our model perform a binary classification resulting in a 'violation' or a 'non-violation' outcome. While different models in text classification have been studied in machine learning and other communities, applying the latest text classification models on legal data has not been widely studied and their performance is still unknown. Previous work on case law focused solely on linear models, whereas in this study, I use several text classification methods and compare their performance, starting with a linear model and moving on to neural networks, making use of more powerful and popular, pre-trained models such as BERT. This work highlights that linear models have outperformed neural networks with Logistic Regression achieving an accuracy of 79%.
## Getting Started

### Prerequisites
* Python 3.3 (or later)
* Jupyter Notebook

### Installing
I strongly recommend  installing Python and Jupyter using the [Anaconda Distribution](https://www.anaconda.com/distribution/), which includes Python, the Jupyter Notebook, 
and the libraries necessary to run this application.

Otherwise, if you already have Python, you can install the Jupyter Notebook and the necessary libraries with the comands below:

#### Install Jupyter Notebook with pip

```
python3 -m pip install --upgrade pip
python3 -m pip install jupyter
```

#### Install libraries with pip

```
pip install -U scikit-learn
pip install pandas
pip install numpy 
pip install -U spacy
```

### System Requirements

* Operating system: Windows 7 or newer, 64-bit macOS 10.10+, or Linux, including Ubuntu, RedHat, CentOS 6+, and others.
* System architecture: Windows- 64-bit x86, 32-bit x86; MacOS- 64-bit x86; Linux- 64-bit x86, 64-bit Power8/Power9.

## Authors
Irina Carabella-Kozeni

## References
* [Medvedeva, M., Vols, M. & Wieling, M. Artif Intell Law (2019)](https://link.springer.com/article/10.1007/s10506-019-09255-y)
* [Jeremy Howard, Sebastian Ruder. 2018. Universal Language Model Fine-tuning for Text Classification](https://arxiv.org/abs/1801.06146)
