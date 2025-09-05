# World Health Organisation - Life Expectancy Predictor

## Situation

Your data analytics team has been tasked with providing an estimated prediction of life expectancies across countries.
The data has been provided by the World Health Organisation (WHO), and it contains records between 2000 and 2015 across 183 countries. 

## Task

Your team has been tasked with constructing two models: One that uses the least information necessary to make a prediction, as well as a more elaborate one that can be used if states decide to share more sensitive data.

One of the main focuses of this project is data integrity. Several countries have previously expressed concerns with sharing some of their sensitive data, such as medical records, as they may bring about unwanted financial implications when correlated with their quality of life measurements and hindered social developments. 

Therefore, you should use your judgement as ethical data practitioners to determine which features may/should be used.

The task is to produce a function that takes in relevant population statistics (features) and makes a prediction on the average life expectancy, offering one model that includes geographically sensitive features and another safer model, which excludes them. 

## Deliverables

1. Model1, which predicts life expectancy using features that may be geographically sensitive.

2. Model2, which predicts life expectancy by excluding features that are more geographically sensitive for countries that may wish not to use model1, as explained in the task above.

3. A report titled Sensitive Model Considerations that details your reasons for why some features may be more sensitive and better to exclude in Model2.
