# Neural_Network_Charity_Analysis

## Overview of analysis
The purpose of this analysis was to determine, through neural network modeling, which organiztions would be successfully if they were funded by this charity

## Results
### Data Preprocessing
-Target variable to be considered is "IS_SUCCESSFUL"
-Features to be to be considered are "APPLICATION_TYPE", "AFFLIATION", "CLASSIFICATION", "USE_CASE", "ORGANIZATION", "INCOME_AMT" AND "ASK_AMT"
-Features to be removed should be "SPECIAL_CONSIDERATIONS", "STATUS", "EIN", and "NAME"

### Compiling, Training, and Evaluation the Model
-I used 80 neurons in the first hidden layer, 30 in the second hidden layer, in a total of 3 layers; I choose "relu" for the hidden layers and "sigmoid" for the output layers
-I was not able to achieve the target model performance
-I tried to increase the model performance by increase the number of hidden layers, increasing the neurons, changing the output activation function and changing the hidden layer activiation function; increasing the neurons seemed to minimally increase the performance

## Summary
I wouldn't be able to make any conclusions from this model as the accuracy was only about 56% (after optimization). However, for the sake of time, I only generated 20 epochs, which may not have been enough time for the model to run. I did try the logistic regression and got a lower accuracy so that probably wouldn't be a good model, unless I stripped more features. Stripping features might be a good next features as aside from "EIN" and "NAME", there may be additional features that aren't beneficial. Increasing neurons seemed to help so a combination of increasing neurons and hidden layers might help boost the accuracy. I'm not sure what the what the best activation function would be for this data set but trying different combinations might also help, although when I changed the output activation function, it did not improve the accurancy. 
