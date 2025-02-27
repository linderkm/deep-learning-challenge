# deep-learning-challenge
This repo contains code and analysis for the Module 21 Challenge. Code for training and evaluation for the initial model can be found in AlphabetSoupCharity.ipynb. Code for attempted optimization can be found in AlphabetSoupCharity_Optimization.ipynb. Saved model instances and additional callbacks can be found in /models.

References for this work can be found in the 'References' section below.

## Analysis
### Overview
The purpose of this work was to train a deep learning model on charity data, with the goal of building a model that can classify applicants as likely or unlikely to succeed, based on standardizaed application data points.
### Results
#### Preprocessing
* Target variables: 'IS_SUCCESSFUL'
* Feature variables: 'EIN', 'NAME', 'APPLICATION_TYPE', 'AFFILIATION', 'CLASSIFICATION','USE_CASE', 'ORGANIZATION', 'STATUS', 'INCOME_AMT', 'SPECIAL_CONSIDERATIONS', 'ASK_AMT'
* Removed features: 'EIN' and 'NAME' were removed, as they are neither measurable features (for the purpose of training this particular model), or targets.
#### Compiling, Training, and Evaluating the Model
* 



## References
1) https://stackoverflow.com/questions/71873453/pandas-value-counts-and-unique-result-in-different-category-orders
2) Module 19; Lesson 2; Activity 4
3) https://stackoverflow.com/questions/77643432/why-is-pd-get-dummies-returning-boolean-values-instead-of-the-binaries-of-0-1
4) Module 21; Lesson 1; Activity 2
5) https://www.tensorflow.org/api_docs/python/tf/keras/layers/Dropout
6) https://www.tensorflow.org/api_docs/python/tf/keras/callbacks/ModelCheckpoint
7) https://www.tensorflow.org/guide/keras/serialization_and_saving