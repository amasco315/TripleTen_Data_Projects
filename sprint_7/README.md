# Sprint 7 Intro to Machine Learning Project
Mobile carrier Megaline has found out that many of their subscribers use legacy plans. They want to develop a model that would analyze subscribers' behavior and recommend one of Megaline's newer plans: Smart or Ultra. You have access to behavior data about subscribers who have already switched to the new plans (from the project for the Statistical Data Analysis course). For this classification task, you need to develop a model that will pick the right plan. Since you’ve already performed the data preprocessing step, you can move straight to creating the model. Develop a model with the highest possible accuracy. In this project, the threshold for accuracy is 0.75. Check the accuracy using the test dataset.  

## The Data 
The data is taken from one dataset on the behavior of Megaline users. /
**users_behavior.csv:**
- сalls — number of calls,
- minutes — total call duration in minutes,
- messages — number of text messages,
- mb_used — Internet traffic used in MB,
- is_ultra — plan for the current month (Ultra - 1, Smart - 0)

## The Process
The data preprocessing for this project had already been completed earlier in the Sprint, so for this project I dove right into to splitting the source data into Training, Validation, and Test sets. I then built and trained 3 different types of models: DecsionTreeClassifier, RandomForestClassifier, and LogisticRegression. 

## The Results
The Final model that I chose for this project was the DecisionTreeClassifier, and the metric that we were looking at was accuracy. This model's accuracy was 79.8%. 