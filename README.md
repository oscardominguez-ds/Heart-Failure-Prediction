# Heart Failure Prediction
### Predticting heart failure from 11 features

## Oscar Dominguez

Source - https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction

# Description
Heart failure is a the most common event caused by Cardio Vascular Disease. Cardio Vascular Diseases are the number cause of death in the world. Machine learning can help to predict heart disease. Early detection is important for CVD management.

# Data Dictionary
<img width="489" alt="Screenshot 2023-04-06 at 10 58 10 PM" src="https://user-images.githubusercontent.com/123289046/230535137-36b6a99f-210a-411a-8c44-a55bb763b876.png">

# Analytical insights

  ## We can see that people with a higher Oldpeak have a higher chance of having heart disease.
  
  <img width="452" alt="Screenshot 2023-04-07 at 3 37 48 AM" src="https://user-images.githubusercontent.com/123289046/230569935-9dabd6e4-fba5-40c9-bf91-73aae32c1c00.png">
  
  ## This plot shows us that the same as the chart above but using 'Oldpeak' and 'Age' column. Green color or 1 means at risk for Heart Disease
  
<img width="565" alt="Screenshot 2023-04-14 at 12 23 21 AM" src="https://user-images.githubusercontent.com/123289046/231942992-d571afd0-44f4-4191-9401-118774321f58.png">

  ## Comparing 'MaxHR' and 'Age'. Those at risk for heart disease tend to have a lower max heart rate

<img width="571" alt="Screenshot 2023-04-14 at 12 23 12 AM" src="https://user-images.githubusercontent.com/123289046/231942996-2b353492-6e1b-4489-b266-bf88bf4e427c.png">
  
# Best Model - Random Forest Classifier model
## Displaying all scores but our focus is on the Testing Accuracy score.

<img width="173" alt="Screenshot 2023-04-14 at 2 41 53 AM" src="https://user-images.githubusercontent.com/123289046/231967368-1533724c-94fa-44e7-8c20-0263379d4c3d.png">

## A description of model solving busines problem -
## The Random Forest Classifier model score tells us that the features used in the model together account for 89.5% of the variance in the target.

## Recommendations -  
### Patients - Our insights show that people who have a higher OldPeak are at risk of having heart disease and a management plan should be put in place to treat. Also, patients with a lower maximum heart, not taking into account for the age, all have a higher risk of getting heart disease.

### Model Performance: I suggest that the model that should be used for this data is the Random Forest Classifier model 

