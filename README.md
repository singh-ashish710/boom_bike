# Boombikes-LinearRegression-Assignment



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Multiple linear regression is performed on the dataset.
- The project is done as part of coursework in the Machine Learning module.
- We are trying to find the number of rentals issued from the company based on numerous independent values such as temperature, weather, humidity, holiday, etc.
- The Boombikes bike rental dataset is being used.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

The summary of the model after data interpretation, visualization, data preparation, model building and training, residual analysis and evaluation of test model are as follows-

1) The R-squared value of the train set and test set is 83.00%, and 80.00% respectively. which suggests that the model explains the variance accurately so based on the R2 score it can be said that it is a good model. 

2) The final model has a mean squared error near 0 for training and testing datasets. The same is the good indicator of variance is accurately predicted for the test set. 

3) The p-values and VIF of variables of the final model were within the prescribed limit i.e. VIF < 5 and p-value <.05 

4) RFE was also conducted and Y_test vs y_pred residual were scattered near the regression line.  

5) We can conclude the following 
- the bike demands are dependent on the temperature and weather.
- demand is more on the winter than in summer and spring. 
- September and October had more demand than the rest of the months. 
- Demand is more on Wed, Thurs, and Sat and more on holidays. 

6) Bike rental had significantly increased demand in the year 2019 when compared to 2018 which means that user are happy with the business idea. However, Boom Bike needs to focus on sprint and summer as demand was comparatively lower So, need to run more promotional activities to drive the sales up another suggestion can be turning casual customers as regular customers to have repeat business.  


## Technologies Used
pandas
seaborn
matplotlib
statsmodels
sci-kit learn
numpy

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [singh-ashish710@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
