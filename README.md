# Car-Price-Prediction

You need to predict the Cost of the Used Cars. The Price of the Used Car is in INR Lakhs.

**Data Description**
The problem contains two data sets, Train Data, and Test Data. Model building is to be done on Train Data set and the Model testing is to be done on the Test Data set. The output from the Test Data is to be submitted on the Hackathon platform

**Don't Overfit**
The Train Set contains 22500 rows of Data whereas the Test Set contains approx 52000 rows of the Data. Build your Model in such a way that It does not over-fit.
Tip: Check R2 Score of your model on Validation Set

**Data Dictionary**
Name: Name of the Car (Brand & Model mentioned)
Location: Location where the Car was sold/is available for purchase.
Year: Year of the Car Built
Kilometers_Driven: The total number of Kilometers driven by the Previous Owner.
Fuel Type: Either is Petrol, Diesel, or CNG Car.
Transmission: Manual or Automatic
Owner_Type: Either it is the First Owner car or the Second Owner or Other.
Mileage: Mileage Offered by the Car Manufacturer.
Engine: Engine Capacity in CC
Power: Power generated by the car engine in bhp
Seats: Number of Seats in the Car
New_Price: The price of a new car of the same model.
Price: target variable

**Evaluation Metric**
Submissions are scored on the root mean squared error. The lower the RMSE, the better the score would be.

## RESULT
I developed multiple regression models to predict the price of used cars in INR Lakhs. To prevent overfitting, I carefully validated the models using R² scores and experimented with various regularization techniques. Additionally, I applied Grid Search CV for hyperparameter tuning to optimize model performance.

My final model achieved an **RMSE** score of **6.50** on the test dataset, ensuring a balance between accuracy and generalization. 
