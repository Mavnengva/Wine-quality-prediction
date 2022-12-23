
# Wine-quality-prediction (Лаба 1 & 2)
Objectives:

 The objectives of this project are as follows
1.	To experiment with different classification methods to see which yields the highest accuracy
2.	To determine which features are the most indicative of a good quality wine

By the use of several Machine learning models, i will predict the quality of the wine, according to it's features.
For this project, I used Wine Quality dataset to build various classification models to predict whether a particular  wine is “good quality” or not. Each wine in this dataset is given a “quality” score between 0 and 10. For the purpose of this project, I converted the output to a binary output where each wine is either “good quality” (a score of 7 or higher) or not (a score below 7). The quality of a wine is determined by 11 input variables:

Attribute Information:

fixed acidity: most acids involved with wine or fixed or nonvolatile (do not evaporate readily).
volatile acidity: the amount of acetic acid in wine, which at too high of levels can lead to an unpleasant, vinegar taste.
citric acid: found in small quantities, citric acid can add 'freshness' and flavor to wines.
residual sugar: the amount of sugar remaining after fermentation stops, it's rare to find wines with less than 1 gram/liter and wines with greater than 45 grams/liter are considered sweet
chlorides: the amount of salt in the wine.
free sulfur dioxide: the free form of  SO2  exists in equilibrium between molecular  SO2  (as a dissolved gas) and bisulfite ion; it prevents microbial growth and the oxidation of wine.
total sulfur dioxide: amount of free and bound forms of  SO2 ; in low concentrations,  SO2  is mostly undetectable in wine, but at free  SO2  concentrations over 50 ppm,  SO2  becomes evident in the nose and taste of wine.
density: the density of water is close to that of water depending on the percent alcohol and sugar content.
pH: describes how acidic or basic a wine is on a scale from 0 (very acidic) to 14 (very basic); most wines are between 3-4 on the pH scale.
sulphates: a wine additive which can contribute to sulfur dioxide gas  (SO2)  levels, wich acts as an antimicrobial and antioxidant.
alcohol: the percent alcohol content of the wine.
quality: score between 0 and 10.
type: red/white.

Understanding Wine and Types
Wine is an alcoholic beverage made from grapes which is fermented without the addition of sugars, acids, enzymes, water, or other nutrients

Red wine is made from dark red and black grapes. The color usually ranges from various shades of red, brown and violet. This is produced with whole grapes including the skin which adds to the color and flavor of red wines, giving it a rich flavor.

White wine is made from white grapes with no skins or seeds. The color is usually straw-yellow, yellow-green, or yellow-gold. Most white wines have a light and fruity flavor as compared to richer red wines.

## ЛАБ 2

Generally, our measurements and model scores worked well to show the aim of the study. This study can be completed in a shorter way as well without repeating similar functions; however, this study also aims to use different methods to have accurate scores from variable sources.
I used the following algorithms as my models:

Dummy Classifer       
KNN        
Decision Tree         
Logistic Regression 

i created a models to predict the quality of the wines. For these models we are going to use the  wine dataset that didn't have the derived variable 'rating'. First we will have to split our dataset into training and testing sets. Training set wiill be used to craete our model and we will predict over testing set.
As the data has been processed, we will proceed with Model Deployment. Different methods will be tested to finalize the best fit modal for the Wine Quality prediction.
The score for the models:

Dummy Classifer:       50.0 %

KNN:                   98.7 %

Decision Tree:         97.6 %

Logistic Regression:   98.3 %

It can be concluded that KNN is the most accurate model for our dataset, with 98.7 percentages of success.

I focused on classification methods on this study. However, I agree that other algorithms can be more successful such as KNN and Logistic Regression  give better results. 
