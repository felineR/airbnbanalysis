# airbnbanalysis

This project is created as part of Udacity's nanodegree program "Data Scientist". It is the first project of this program and is named "Write a Data Science Blog Post".

The three main questions posed by this project are:
1. Which listing attributes have the highest impact on the listing's price?
2. How do the prices of superhost's listings differ from the prices of regular host's listings?
3. How well can we predict a listing's price?

Summary of results:
1. Highest impact on a listing's price have: # of guests that can be accommodated, extraordinary property type, # of bedrooms, having a strict cancellation policy, # of beds, # of guests included in a booking, renting out the entire home, renting out a private room (negative impact), property type 'Apartment' (negative impact), and # of bathrooms.
2. In Berlin, superhosts receive higher payments for their listings as compared to regular hosts. In Boston, it is not necessarily price-wise worth the effort to receive and retain the status ‘superhost’.
3. After 100 iterations the mean of r squared for predicting the listing prices was 5.35 % for Berlin and 33.86 % for Boston.

Please see my blog post on Medium for details on the findings (https://medium.com/@feline.bohn/10-considerations-to-maximize-your-return-when-renting-out-your-place-on-airbnb-21726288e542).

Files in the repository:
- AirBnBDataPreparation.ipynb | contains all data preparations made.
- AirBnBDataScience.ipynb | contains the three main questions and the analysis made to answer them.
- berlin_listings_summary.csv | contains the rawdata of AirBnB listings in Berlin downloaded from Kaggle (link see below).
- boston_listings.csv | contains the rawdata of AirBnB listings in Boston downloaded from Kaggle (link see below).
- my_berlin_after_data_preparation.csv | contains the cleaned data for AirBnB listings in Berlin after data preparation.
- my_boston_after_data_preparation.csv | contains the cleaned data for AirBnB listings in Boston after data preparation.
- README.md | contains all useful informations to get starting studying this project. This document is the README.md.

Python libraries used:
- pandas
- matplotlib
- numpy
- seaborn
- datetime
- sklearn

Acknowledgements:
- This project is conducted as part of the Udacity Nanodegree on Data Science. Please find further informations here: https://www.udacity.com/course/data-scientist-nanodegree--nd025
- The rawdata for this project have been downloaded on kaggle. Please see https://www.kaggle.com/brittabettendorf/berlin-airbnb-data  for the Berlin dataset and https://www.kaggle.com/airbnb/boston for the Boston dataset.

Author of this project is: F B
Created in November 2021