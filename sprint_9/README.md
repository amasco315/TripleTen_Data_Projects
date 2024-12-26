# Sprint 9 ML in Business Project

In this project I will be looking at 3 different datasets containing information on oil well sites. Each datasets pertains to a different region. My goal will be to determine which region has the highest profit margin. I will do so by bulding and training a model for each region to help predict which region has the highest profit margin. I will then use the bootstrapping technique to analyze potential risks of loss, as well as potential profits.

## The Data
Geological exploration data for the three regions are stored in 3 separate files: \
**geo_data_0.csv** \
**geo_data_1.csv** \
**geo_data_2.csv** 
- id — unique oil well identifier
- f0, f1, f2 — three features of points (their specific meaning is unimportant, but the features themselves are significant)
- product — volume of reserves in the oil well (thousand barrels).

## The Process
First I downloaded and preprocessed each dataset. I then split each dataset into Training and Validation sets in order to train the models properly. After each model was trained and analyzed, I went on to calculating the volume of reserves in each region needed to breakeven. I then wrote a function that was used to calculate the estimated profit in each region. Lastly, Bootstrap Analysis was used to determine what the best region for oil well development was. 

## The Results 
For detailed results see the conlcusion section of the notebook. 
