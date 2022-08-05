### Problem Statement

I am a financial analyst at a real_estate investment firm. Our firm has a lot of real-estate in Ames, Iowa. My next task is to use a dataset that was given to me to predict the sales price of the real-estate owned by the firm. I have a training data set that will be used to create an accurate model, and a testing data set to test my model on. 

### Data Dictionary

[click here to view Data Dictionary](https://www.kaggle.com/competitions/dsir-523-project-2-regression-challenge/data)

The data-set gives many different housing details. Based on my prior experience as a financial analyst in real-estate I began with inputs that I new would have a large impact on sales-price. I then analyzed the data to see what other data I believed would help increase the accuracy of my model. 

### Analysis Summary

Analyzing the data has given insights into important trends and impacts that certain house attributes has on the house's sale-price. The first insight was shown through looking at the heatmap. The biggest factor on house's sale-price is the overall quality of the house. The two next biggest attributes that impact house's sale-price is the square footage and area.

I first split my data into categorical data and nominal data. I then created functions that created scatterplots and histograms for the nominal data and bar graps for the categorical data. For the scatterplots and histograms I looked if the relationsip between the house factor and sales-price looked linear and if the data looked to have a normal distribution. For the bar graphs I looked to see if the sales price were largely different between each house factor.

I then created linear regression models, Ridge models, and Lasso models. For linear regression models I created a basic train-test-split model, a model that did a polynomial transformation before the train-test-split, a model that did a standard scaler before the train-test-split. A model that did the polynomial transformation before the train-test-split and thhen a standard scaler on the X_train and X_test. I then also did a Ridge model and a Lasso model. 

The next was finding that the model that did the best was linear regression model using polynomial features before adding categorical variables. The best model after adding categorical variables was a linear regression model with standard scaler. The linear regression model with polynomial features had the best R2 regression score, cross val score, testing scores and training scores. 

### Conclusions/Recommendations

For the data-set given it is possible to create a good model that can predict the sales-price of houses in Ames, Iowa. Based on the analysis of the different types of models, the model that could best use the data given to predict sales-prices of houses in Ames, Iowa is a linear regression model that included polynomial features. Accurate predictions of the sales-price of houses owned by the firm can help them decide what should be done with them. The next steps would be to add to the model created, by adding more house factors or changing the transformations used in the model to keep improving the model and making it more and more accurate.   


