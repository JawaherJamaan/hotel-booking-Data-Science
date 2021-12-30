# Hotel booking Project Proposal 

This repository to meet requirements for data science bootcamp with SADIA.


# Predict the hotel booking's cancellation?

 A study conducted by property management systems (PMS) provider Guestline has revealed insights on how hoteliers can avoid booking cancellation. 
The survey amongst 2,000 participants delved into how people book their hotels, and more importantly, their main priorities and desires when choosing one.

## Dataset
We have data set **hotel-booking-demand** that represents booking data for a city hotel and a resort hotel with 1193900 records and 32 features. 
Includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, 
and the number of available parking spaces, among other things. I use this data set for extract useful information to hotels companies or booking apps.
This dataset can be found at Kaggle: https://www.kaggle.com/jessemostipak/hotel-booking-demand/code <br>
  
This dataset contains hotel for the following type:<br>
•	City hotel <br>
•	Resort hotel<br>


The dataset is available as the ```.csv``` file. a sample of data is shown in the following table:
<table width="100%">
 <tr>
  <th>hotel</th><th>is_canceled</th><th>lead_time</th><th>arrival_date_year</th><th>arrival_date_month</th><th>arrival_date_week_number</th><th>arrival_date_day_of_month</th><th>stays_in_weekend_nights</th><th>stays_in_week_nights</th><th>stays_in_week_nights</th><th>adults</th><th>children</th><th>babies</th><th>meal</th><th>country</th><th>market_segment</th><th>is_repeated_guest</th><th>previous_cancellations</th><th>reserved_room_type</th><th>assigned_room_type</th><th>booking_changes</th><th>deposit_type</th><th>days_in_waiting_list</th><th>customer_type</th><th>adr</th><th>required_car_parking_spaces</th><th>total_of_special_requests</th><th>reservation_status</th><th>reservation_status_date</th>
 </tr>
 <tr>
  <th>Resort Hotel</th><th>0</th><th>342</th><th>2015</th><th>July</th><th>27</th><th>1</th><th>0</th><th>0</th><th>2</th><th>0.0</th><th>0</th><th>BB</th><th>PRT</th><th>Direct</th><th>0</th><th>0</th><th>C</th><th>C</th><th>3</th><th>No Deposit</th><th>0</th><th>0</th><th>Transient</th><th>0.0</th><th>0</th><th>0</th><th>Check-Out</th><th>2015-07-01
</th>
 </tr>
</table>


The most important features for this study:<br>
**Hotel**, Hotel Resort Hotel or City Hotel<br>
**is_canceled**, Value indicating if the booking was canceled (1) or not (0) ( label variable, the target)<br>
**lead_time**, Number of days that elapsed between the entering date of the booking into the PMS and the arrival date<br>
**arrival_date_year**, Year of arrival date<br>
**arrival_date_month**, Month of arrival date<br>
**arrival_date_week_number**, Week number of year for arrival date<br>
**arrival_date_day_of_month**, Day of arrival date<br>
**stays_in_weekend_nights**, Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel<br>
**stays_in_week_nights**, Number of weeknights (Monday to Friday) the guest stayed or booked to stay at the hotel<br>
**adults**, Number of adults<br>

The logistic Regression Analysis is the process of predicting a Label based on the features at hand so, here we use regression to know relationship between cancellation and other features.<br>
Also, In this particular study, the KNN algorithm is used to classify hotel bookings in terms of cancellation risk (1 = model predicts that the customer will cancel their booking, 0 = customer is not predicted to cancel their booking). 


## Tools
I uesd Jupyter notebook to write codes and import libraries to achieve the goal of this dataset, such as:<br>
```numby, matplotlib, pandas``` used to EDA and prepare data to train a model a.<br>
and for regression use  ``` sklearn , logisticRegression(function)``` will be used to analyzes the relationship between two or more features
it is type of supervised learning to train the model.And ```KNeighborsClassifier ```to KNN

## **TO DO**: 
- I will do wrangling data and exploratory data analysis before used the model.
- Visualize data and Fit models.
- **NOTE:** some features might be increased or changed and the model as well.

