# Neural_Network_Charity_Analysis

## Overview of the Analysis
In this assignment we sused Machine Learning and Neural Networks to help predict applicants that will be successfully funded by Alphabet Soup. We received a doucment with 34,000 other organizations that have been funded to use to perform our analysis. 

## Results
### Data Preprocessing
* What variable(s) are considered the target(s) for your model? The target for the model is the IS_SUCCESSFUL
* What variable(s) are considered to be the features for your model? All columns except IS_SUCCESSFUL, EIN, and Name are considered features.
* What variable(s) are neither targets nor features, and should be removed from the input data? EIN and NAME were both dropped becauase they have very little or no impact on the outcome. 

#### Compiling, Training, and Evaluating the Model
* How many neurons, layers, and activation functions did you select for your neural network model, and why My original attempt had two hidden layes with 8 and 5 neruons each and a activition of relu for input and sigmoid for output. In this model I saw a accuracy of 50%. Using this as my starting place I tried a handful of other options including adding an additional layer, adding additional neurons, increasing epcochs and changing activation model.
![ScreenShot](https://github.com/Cayswartz/Neural_Network_Charity_Analysis/blob/653efd6f19acc70edc2b0bdb65a05ad9970ca1d6/Screen%20Shot%202022-07-29%20at%2011.34.52%20AM.png)



* Were you able to achieve the target model performance? I was not able to achieve the target performance even with a handful of different attempts

* What steps did you take to try and increase model performance?
I attempted to increase the model by adding additional layers, adding additional neurons, increasing epcochs and changing activation models but unfortuntely was not able to successful reach the target accuracy. 

## Summary 
Overall, I was unable to successfully reach the target accuracy. Adding additional data to the data set could help provide some more clarity on how to make these predictions or looking in to using a different modeling technique. 
