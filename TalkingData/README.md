# TalkingData competition
The goal is to predict the gender and age of the customers.
I am going to document all the steps in Jupyter notebooks.

## Notebooks:

* 1_understand_data: 
   - Investigate what's in the gender_age and phone_brand_device_model files. 
   - Do a few plots to get a feeling of the distributions 
   - Merge gender_age and phone files as well as the test and training sets
   - Use the merged data in a new notebook to create new features with which a first model can be trained

* 2_understand_events_data:
   - creates hasEvents, nEvts, and mean/variance of longitude and latitude variables
   - splits timestamp into day and hour

* predict_classes:
   - introduces reference model to be tested against new ML models
   - Reference: probabilities are equal to *n(per group)/n(total)*
