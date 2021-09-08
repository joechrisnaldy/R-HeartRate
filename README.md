# R-HeartRate
**Introduction** </br>
Millions of people develop some sort of heart disease every year, and heart disease is the
biggest killer of both men and women in the United States and around the world. More than
17 million people died of heart disease in 2017. Statistical analysis has identified many risk
factors associated with heart disease such as age, blood pressure, total cholesterol,
diabetes, hypertension, family history of heart disease, obesity, lack of physical exercise,
etc. We will run statistical tests and regression models using the Cleveland heart disease
dataset to assess one particular factor -- the maximum heart rate one can achieve during
exercise and associated with a higher likelihood of getting heart disease.

**Conclusion** </br>
After these metrics are calculated, we'll see (from the logistic regression OR table) that older
age, being male, and having a lower max heart rate are all risk factors for heart disease. We
can also apply our model to predict the probability of having heart disease. For a 45 years
old male with a max heart rate of 140, our model generated a heart disease probability of
0.6276149, indicating a high risk of heart disease. Although our model has an overall
accuracy of 0.71, some cases were misclassified, as shown in the confusion matrix. One way
to improve our current model is to include other relevant predictors from the dataset into
our model; try another model such as Neural Network or decision tree, etc.
