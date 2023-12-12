USING DATA TO PREDICT HUMAN LONGEVITY

Bhargav Gorantla

The goal of this project is multifaceted. One goal is to train models that can predict a populations longevity based on its attributes like thinness, alcohol consumption, etc. The second goal is to apply these models to individuals to calcualte their longevity.

Answering how long a person will live can be very useful to insurance companies and even individuals to predict their own lifespan.

The data used to train these models: https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who
This data is sourced from WHO and contains various attributes of the populace of different countries from the years 2000 to 2015.
It also contains the average lifespan of the population.

Multiple machine learning algorithms will be used including: KNN, SVM, Decision Trees, etc.

After training multiple models, here are my findings:
The most important attribute that affects human longevity is Income decomposition of resources.  
The second most important feature is the prevalence of aids. This applies to a region but doesn't really apply to an individual living in that region.  
The third most important feature is schooling. Schooling probably correlates with income which means access to better healthcare.  
The fourth and fifth most important features are thinness.
Alcohol consumption is the sixth most important feature.  
The least three important features are the prevalence of various diseases like Polio and Hepatitis B.  
The reason these diseases don't affect the longevity of a region too much is because they are not fatal unlike HIV/AIDS.

Out of the trained models, DecisionTree model had the lowest error and would be the best model to use for future predictions.

In the final review and report, I will go through the same data and show more observations/conclusions to supplement the conslusions in this project.

- Link to notebook - https://github.com/bgorantla/Final-Project/blob/main/Final_Project.ipynb

Contact and Further Information:
Bhargav Gorantla
bgorantla500@gmail.com
