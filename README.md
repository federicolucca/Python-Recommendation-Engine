# User-Item Recommendation System

This repo demonstrate a online retail recommendation system which recommend items for the user.

Here are the different notebooks:

- [Data Processing](https://github.com/AdnanShah/Python-Recommendation-System/blob/rest_api_lightfm/retail_recom_sys_DATA_PRE_PROCESSING.ipynb): Loading and processing the data to prepare them for input into my models.
- [Deep Learning Model](https://github.com/AdnanShah/Python-Recommendation-System/blob/rest_api_lightfm/lightFM_retail_recom_sys_MODEL_CREATION.ipynb): This file is responsible for the creation of deep leaning model. This file use implicit collaborative filtering which is a Deep Learning approach to predict the items.
- [Making Predictions](https://github.com/AdnanShah/Python-Recommendation-System/blob/rest_api_lightfm/lightFM_retail_recom_sys_PREDICTIONS.ipynb): Making predictions of items user may like based on user_id and also item_id user purchased.

## Data Source

This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.

https://www.kaggle.com/jihyeseo/online-retail-data-set-from-uci-ml-repo

## Rest Api

Backend for web based recommendation system is also available [here](https://github.com/AdnanShah/Python-Recommendation-System/tree/rest_api_lightfm/django-rest-framework/fm_Rec):

- [Rest Api](https://github.com/AdnanShah/Python-Recommendation-System/tree/rest_api_lightfm/django-rest-framework/fm_Rec): I also created a rest api for the recommender using django and django-restframework which takes user_id as input and predict items user may also like.

## The main contents of this project are following:

- Implementation of implicit collaborative filtering using [LightFM framework](https://github.com/lyst/lightfm).
- Different ways of recommendating items to uers(user-user or item-item)
- Implementation of demo program of the recommender system

## Installing

I created a virtual environment in my machine, and run the code.
To run the python code first create a virtual environment and install all dependencies by run the command:

```
$: pip install -r requirements.txt
```

and run jupyter nootebook

```
$:  jupyter nootebook
```

To make predictions run lightFM_retail_recom_sys_PREDICTIONS.ipynb

## Requirements

- [Python 2.7](https://www.python.org/download/releases/2.7/) or [Python 3.6](https://www.python.org/downloads/release/python-360/)
- [Jupyter Notebook](http://jupyter.org/)

## Dependencies

Choose the latest versions of any of the dependencies below:

- [lightfm](https://github.com/lyst/lightfm)
- [pandas](https://pandas.pydata.org/)
- [numpy](http://www.numpy.org/)
- [scipy](https://www.scipy.org/)
- [sklearn](http://scikit-learn.org/stable/)
