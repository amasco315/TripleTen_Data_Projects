# Sprint 12 Numerical Methods Project
Rusty Bargain used car sales service is developing an app to attract new customers. In that app, you can quickly find out the market value of your car. You have access to historical data: technical specifications, trim versions, and prices. You need to build the model to determine the value. 

Rusty Bargain is interested in:

- the quality of the prediction;
- the speed of the prediction;
- the time required for training

## The Data
The data is taken from a single dataset containing information on customer's vehicle information. The target for this dataset is the 'Price' column\
**car_data.csv:**
- DateCrawled — date profile was downloaded from the database
- VehicleType — vehicle body type
- RegistrationYear — vehicle registration year
- Gearbox — gearbox type
- Power — power (hp)
- Model — vehicle model
- Mileage — mileage (measured in km due to dataset's regional specifics)
- RegistrationMonth — vehicle registration month
- FuelType — fuel type
- Brand — vehicle brand
- NotRepaired — vehicle repaired or not
- DateCreated — date of profile creation
- NumberOfPictures — number of vehicle pictures
- PostalCode — postal code of profile owner (user)
- LastSeen — date of the last activity of the user
- Price — price (Euro)

## The process
First, the dataset was loaded and preprocessed. Next, I used the get_dummies method to one hot encode the categorical features. Next, the dataset was split into Training, Validation, and Testing sets, and the numerical features of the training sets were standardized using StandardScaler(). I then went on to build 4 different types of models: LinearRegression, DecisionTreeRegressor, RandomForestRegressor, LightGBM. The models were tuned, and the training and prediction times for each model were also measured. 

## The Results
The final model chosen was LightGBM based on training and prediction time, as well as RMSE value. For full detailed results see the conclusion section of the notebook. 