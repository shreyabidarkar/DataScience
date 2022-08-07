# DataScience Project - Air Quality Index Prediction
### What is AQI?
An air quality index (AQI) is used by government agencies to communicate to the public how polluted the air currently is or how polluted it is forecast to become. Public health risks increase as the AQI rises. The AQI of India is determined by monitoring ground-level ozone, particulates, sulfur dioxide, carbon monoxide and nitrogen dioxide, and other pollutants.

In this notebook, I aim to visualize the AQI of different states and their change over time. We may understand pollution in India better by finding a pattern in the data.

Air is what keeps humans alive. Monitoring it and understanding its quality is of immense importance to our well-being.

 ## Problem Statement 
Air pollution in India is the biggest issue and is affecting public health. 
Exposure to air pollution can cause damage to the airways through several mechanisms including oxidative stress, airway remodeling, inflammatory pathways, and by enhancing respiratory sensitization to allergens. 
Exposure to pollutants such as ozone, nitrogen dioxide, and PM2. 5 can induce airway inflammation. 
We need to identify the factors which causes increase in air pollution and try to take precautionary measures and control it.

## Our Goal
Our goal is to build a model to determine a model and see if the Air pollution in India is rising and what are the factors that causes this increase in air pollution. 
We will use Bayesian Estimation and various Macine learning algorithms to check how much the air polluion has increased in various cities over the period of time.

### Data Science Libraries used which needs to be installed using command (pip install library name*)- 
numpy, pandas, scipy, scikitlearn, seaborn, matplotlib, plotply, FB Prophet, pymc3. 

## Conclusion
Random forest adds additional randomness to the model, while growing the trees. Instead of searching for the most important feature while splitting a node, it searches for the best feature among a random subset of features. This results in a wide diversity that generally results in a better model.

FBProphet is interesting, sophisticated and quite easy to implement. Even by using the default argument or parameter, this model allows you to generate good forecast output with little effort or domain knowledge in time-series analysis.

However, Random forest algorithm can be used for both classifications and regression task. It provides higher accuracy through cross validation. Random forest classifier will handle the missing values and maintain the accuracy of a large proportion of

Fine particulate matter (PM2.5) is an air pollutant that is a concern for people's health when levels in air are high. PM2.5 are tiny particles in the air that reduce visibility and cause the air to appear hazy when levels are elevated.data

This is the reasonwe use pm 2.5 in bayesian estimation.

Long term exposure to PM2.5 has already cost millions of lives in India due to heart and lung diseases. It may now be driving up covid-related deaths

How did Beijing mitigate its air pollution? Contribution of different causes of decline in PM2.5 levels in Beijing during 2013-17

Causes Contribution Surrounding emission reduction 22% Coal-fired boiler control 19% Clean fuels in the residential sector 17% Meteorological change 12% Optimized industry structure 10% Fugitive dust control 7% Improved end-of-pipe control 6% Vehicle emission control 6% Integrated treatment of VOCs 1%
 
