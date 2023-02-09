# Predict_Blood_Donations
This is a project of DataCamp to predict blood donations in a campus on Taiwan. 


This dataset is from a mobile blood donation vehicle in Taiwan. The Blood Transfusion Service Center drives to different universities and collects blood as part of a blood drive. We want to predict whether or not a donor will give blood the next time the vehicle comes to campus.


The data is structured according to RFMTC marketing model (a variation of RFM), so that means every column in our DataFrame has the numeric type.


The conclusion for this project was that the demand for blood fluctuates throughout the year. As one prominent example, blood donations slow down during busy holiday seasons. An accurate forecast for the future supply of blood allows for an appropriate action to be taken ahead of time and therefore saving more lives.


In this notebook, we explored automatic model selection using TPOT and AUC score we got was 0.7850. This is better than simply choosing 0 all the time (the target incidence suggests that such a model would have 76% success rate). We then log normalized our training data and improved the AUC score by 0.5%. In the field of machine learning, even small improvements in accuracy can be important, depending on the purpose.


Another benefit of using logistic regression model is that it is interpretable. We can analyze how much of the variance in the response variable (target) can be explained by other variables in our dataset.


You can find this project on https://projects.datacamp.com/projects/646 and dataset on https://www.kaggle.com/datasets/shabbir94/blood-transfusion?resource=download
