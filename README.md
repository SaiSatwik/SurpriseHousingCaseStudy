# Project Name
> SurpriseHousingCaseStudy


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.
- For the same purpose, the company has collected a data set from the sale of houses in Australia.
- The company is looking at prospective properties to buy to enter the market.
- Goal is to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
-  Initially we started analysing the dataset having 80 feature (both numerical and catogorical). We removed few features initially as these features mostly take single values which could not help in distinguising different data points.
-  After expanding categorical features, by creating dummy variables,  we ended up into almost 224 features.
-  Applying Lasso regression pushed few features to zero leaving only 212 features in the dataset.
-  Lasso and Ridge performs perfoms better that OLS as these regularisation techniques of Ridge and Lasso regression add penalty to the model parameters which keep the model simpler. This helps in reducing the variance of the final model without much effect to bias.

- Important predictor features found after applying Lasso regression
   - Neighborhood_Crawfor
   - Neighborhood_NridgHt
   - OverallQual
   - GrLivArea
   - BldgType_Twnhs

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- python - version 3.9.7

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was done as part of Machine Learning module in ML and AI program conducted by IIITB and upgrad. I thank all the mentors, coworked and faculty at UpGrad and IIIT Banglore for their continuous guidance throughtout this course.

## Contact
Created by [@SaiSatwikK] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
