# Capstone-Project

Using Starbucks promotions data(2013–2018), I analyzed how different people react to different promotions and created a model that would recommend the best offer to a client.

The three types of offers I analyzed were:
1.BOGO- Buy one Get one Free
2.Discount offers
3.Informational Offers.

The data used was from Starbucks promotion data that had transactions data showing a user purchases made with time and amount, demographic data showing users age, income , gender, membership and the offer data which showed the three types of offers given.

A model was then created to predict which type of offer to give to a customer.

The findings are discussed in the medium blog post
(https://medium.com/@makhanuhesther/starbucks-promotion-offers-4cd568bfb932)

## Libraries used
import pandas as pd

import numpy as np

import math

import json

from datetime import datetime

from time import time

import matplotlib.pyplot as plt

import seaborn as sns

import warnings

from sklearn.naive_bayes import GaussianNB

from sklearn.ensemble import AdaBoostClassifier

from sklearn.metrics import accuracy_score,f1_score

from sklearn.model_selection import train_test_split,GridSearchCV

from sklearn.naive_bayes import GaussianNB

from sklearn.neighbors import KNeighborsClassifier

from sklearn.svm import SVC

## Files.
Portfolio.json

Profile.json

Transcript.zip... you have to unzip the file. It was too big couldnt be uploaded in githuib without zipping.

## Conclusion

The best performing F1 score was 0.89 by SVC for the discount offer training.

The lowest of all models was the KNeighboursClassifier Model for BOGO training.

More promotions should be focused on males as they are the higher income earners with the discount offers being the best for them.

The most interesting part was the cleaning and data preparation as it helped understand the data more and improve my skills in python.

The models could be improved further by using grid search

