# Project Name
> Surprise Housing - A US based housing company wants to enter Australian market and want leverage the anaytics and predict the actual value of the prospective properties and decide whether to invest in them or not.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A US-based housing company named Surprise Housing has decided to enter the Australian market.The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. The company want to leverage the anaytics and predict the actual value of the prospective properties and decide whether to invest in them or not. 

**Business Goal** 

Using the predictive model the management wants;
- To understand how exactly the prices vary with the variables. 
- To manipulate the strategy of the firm infering the model and concentrate on areas that will yield high returns. 
- To understand the pricing dynamics of a new market.

**Analytical Objective**
- To understand which variables are significant in predicting the price of a house
- How well those variables describe the price of a house.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The Feature Engineering interms of Recategorising the Nominal Categorical variables based on the class wise independence has resulted in optimizing on the categories for each feaure and also improve the model predicion power and lower the variance
- The approach has resulted in total of 90 features for the modeling
- Numerical features were selected based on Co-relation it has with Target Variable 
- RFE method was used to reduce the number of features to half 45/90(in the final model) which has give a good model with low variance
- Both Ridge and Lasso performed to the same level after tuning the alpha value (alpha = 7.4 for Ridge and 200 for Lasso)
- The perforamcen in terms of Adjusted R2;
    - Ridge - Train = 0.845, Ridge Test = 0.828
    - Lasso - Train = 0.84, Lasso Test = 0.827
    
- **Model Interpretation**
- Top 10 features;
    - Total Bath Rooms
    - Neighborhood belonging to - StoneBr, NridgHt, NoRidge 
    - Total SFT of the house
    - Total rooms above grade
    - Number of fireplaces
    - GarageArea
    - Neighborhood belonging to - Veenker, Timberland, Somerset
    - Wood deck area in square feet
    - Basement Type 1 finished square feet
    - Overall Quality

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- python - 3.10.1
- pandas - 1.3.5
- numpy - 1.21.5
- matplotlib - 3.5.1
- seaborn - 0.11.2
- scikit-learn - 1.0.2
- scipy - 1.7.3
- statmodels - 0.13.1

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->