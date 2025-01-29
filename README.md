# BikeSharing
Problem Statement
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.
In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.
They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
## Business Goal
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.
## Observations
There is more collinearity between few variables. 
Based on this, while building a model - we have to take into account of this collinearity based on VIF and p-values
And we will fit a best model as per understanding.
## Model 
From the model, we get below constant and coefficient details.
Constant - 1146.7
yr - 2078.04
holiday - -799.994
temp - 4773.4236
windspeed - -1581.19
Sep - 773.06
Sun - -375.87
Moderate - -584.38
Summer - 763.63
Winter - 1023.74
### Evaluation Of Model with test data
R2 - 0.76
Residuals are following normal distribution


