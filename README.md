# Bulldozer Price Prediction With ML


## Overview
This README file provides an overview of the Bulldozer project. The project involves exploring and analyzing the Blue Book for Bulldozers, a Kaggle competition lauched in 2013
### Prerequisites
Make sure you have the following Python packages installed:

 > numpy
>
 > pandas
> 
 > scikit-learn
> 
You can install them using:

    pip install numpy pandas scikit-learn


## Dataset
The data can be found at: https://www.kaggle.com/c/bluebook-for-bulldozers/data
The data for this competition is split into three parts:

  * Train.csv is the training set, which contains data through the end of 2011.
  * Valid.csv is the validation set, which contains data from January 1, 2012 - April 30, 2012 You make predictions on this set throughout the majority of the competition. Your score on this set is used to create the public leaderboard.
  * Test.csv is the test set, which won't be released until the last week of the competition. It contains data from May 1, 2012 - November 2012. Your score on the test set determines your final rank for the competition.

The key fields are in train.csv are:

  * SalesID: the uniue identifier of the sale
  * MachineID: the unique identifier of a machine.  A machine can be sold multiple times
  * saleprice: what the machine sold for at auction (only provided in train.csv)
  * saledate: the date of the sale


## Project goals
The evaluation metric for this competition is the RMSLE (root mean squared log error) between the actual and predicted auction prices. The higher the RMSLE, the better the predictions.



## Contributing
Feel free to contribute to the project by opening issues or submitting pull requests. Your feedback and ideas are highly appreciated.



## Acknowdlegdements
This project was completed following a data bootcamp course on [Udemy](https://www.udemy.com/course/complete-machine-learning-and-data-science-zero-to-mastery/?couponCode=KEEPLEARNING), with customizations implemented by me throughout the process.
Happy coding!

