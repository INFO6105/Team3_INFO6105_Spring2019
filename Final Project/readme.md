# Fake Box

The whole point of this exercise is to stop the spread of misinformation. Fakebox analyzes news articles to assess whether they are likely to be real news or not. By looking at a range of available aspects of an article (title, content and URL) using built-in machine learning models and a manually curated database, Fakebox can successfully identify fake news.

Develop a machine learning program to identify when a news source may be producing fake news. We aim to use a corpus of labeled real and fake new articles to build a classifier that can make decisions about information based on the content from the corpus. The model will focus on identifying fake news sources, based on multiple articles originating from a source. Once a source is labeled as a producer of fake news, we can predict with high confidence that any future articles from that source will also be fake news. Focusing on sources widens our article misclassification tolerance, because we will have multiple data points coming from each source.



## Getting Started

The steps required to install and deploy the project in live system are as follows:

### Prerequisites

To begin with we need to install python 2.x/3.x in our local system and add it to our classpath.Some python packages are also needed for deployment

```python
Python packages:

numpy
pandas
sklearn
nltk
xgboost
seaborn
pickle
flask
ggplot
```

Installing

Following steps are required to install necessary packages

Install python packages mentioned above using pip command

```
pip install <package_name>
```



### **Essentials**

These files consists of models essential to deploy the project in live system.

https://drive.google.com/drive/folders/1Y14cpzlm6311R5IM4bI8zX2lAVwm78jH?usp=sharing



## **Project Proposal**

https://docs.google.com/document/d/1RpEQ2ythFIVs5RNhOtB-daWkJWovOoO5tO4Mj25yLV8/edit?usp=sharing



## Data Collection and Preparation**

In our work, we will analyse two available data sets :

1. Fake News Classifier Dataset from Kaggle
2. Toxic Comment Classification Dataset from Kaggle



## Features : 

**title**: the title of a news article

**content**: the text of the article

**publication**: which company published the article

**label**: a label that marks the article as fake/real



## **Model Comparisons** 

Performance metric for Naive Bayes Classifier 

![img](https://lh5.googleusercontent.com/EsaJiIZ4uk-_ROi8zMwj9abOWmicdMQ4oPxVFBaiLLjNRtcHGD-Rt2kRtRH-2AuBkFmmC_thR_UmvclXUz0g5_ed0_dC_2bzFkiqUHxGZCgfT_-xPKj2bpyOderO3hCRgyhOPqUA)



Performance metric for SVM

![img](https://lh3.googleusercontent.com/8JwwrVUQ0ba01TMJP1JdRa-d_P8c8wGlt6oVps3AI44JacTxBnBdAnwyQhKleaiCzfnyhLUS-ArpX1OflRlLYiCE7Idf2IkbpoiSMf_zxTxYvWV6cUbF-oOoiAjpLQXYB7aaQlPZ)



Performance metric for Logistic Regression

![img](https://lh4.googleusercontent.com/lZUhPca2ZtP3-agTgInEnW2AHSRPVE0918VfnfxndXr3Mb-h699rwP4ziVTyrkZQHFa5I4v5awwZTso80iVw9Id4-zPKfIwcjqrPEGmcdC5uqmmVLIGLIkNNN1MHUrBV3P7Y9ZO7)



## Codelabs

https://docs.google.com/document/d/1nJLFpV1Ef6ZwzFu9KS93dAU48HMP_Em4F55sMl7MGK4/edit?usp=sharing



## Built With

- [Jupyter Notebook](https://jupyter-notebook.readthedocs.io/en/stable/) - Code editor used for python
- [NewsAPI:](<https://newsapi.org/>) API used to retrieve real time news and articles
- [Heroku](https://www.heroku.com/) :Cloud Application Platform used to host the website
- [Flask](http://flask.pocoo.org/) :Microframework in python used to deploy the front end



## **Citations:**

1. <https://www.kaggle.com/anthonyc1/fake-news-classifier-final-project/data>
2. <https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification/data>
3. <https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/data>



## Authors

- **Ami Vora**
- **Juhi Pareek**
- **Aditya Soni**
- **Hemin Joshi**



