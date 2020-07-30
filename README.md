# Online Ratings for Electronic Gadgets for Commercial Purpose

Online Ratings for Electronic Gadgets for Commercial Purpose by [Muhammad Syamil, Amer Fathullah, Amirul Hakim, Ahmad 'Asim, Muhammad Ariffin](https://github.com/amerfathullah)

## Overview

This repository contains code for our data mining project. The dataset is downloaded from Kaggle. The code is developed using [Scikit learn](http://scikit-learn.org/stable/index.html).
It uses following algorithms: <br>

- Multinomial Naive Bayes
- Support Vector Machine

Also, it has visualisation of data and the knowledge obtained from it.

## Dependencies

- python3.8.5
- virtualenv
- jupyter notebook
- pandas
- numpy
- nltk
- matplotlib
- sklearn
- beautifulsoup4
- lxml

## Data

Download the required data from [this](https://www.kaggle.com/PromptCloudHQ/amazon-reviews-unlocked-mobile-phones/data) kaggle page and put it in the same directory.

## Installation

You may run this code in a virtual environment. We preferred to do so.<br>
Assuming that you have installed pip and virtualenv,<br>
Create a virtualenv and activate it. eg. let's call it `env`
```
cd env
git clone https://github.com/hiteshvaidya/sentiment_analysis.git
cd sentiment_analysis
```
Install the Python libraries required for this project
```
pip install pandas
pip install numpy
pip install nltk
pip install matplotlib
pip install sklearn
pip install beautifulsoup4
pip install ipykernel
pip install lxml
```

In order to run jupyter notebook in a virtualenv, you need to create a new kernel. Follow this [blog](https://anbasile.github.io/programming/2017/06/25/jupyter-venv/) or this stackoverflow [page](https://stackoverflow.com/questions/37891550/jupyter-notebook-running-kernel-in-different-env) to create one.


## Usage

- Open jupter notebook. Now go in settings and change kernel to the new kernel that you just created.
- Now run the code in jupyter notebook.

## Acknowledgement

Credits for part of this code to [Suki Lau](https://github.com/sukilau) and [Hitesh Vaidya](https://github.com/hiteshvaidya).
