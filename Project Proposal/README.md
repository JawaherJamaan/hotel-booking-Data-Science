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
  <th>id</th><th>imdb_id</th><th>popularity</th><th>budget</th><th>revenue</th><th>original_title</th><th>cast</th><th>homepage</th><th>director</th><th>tagline</th><th>keywords</th><th>overview</th><th>runtime</th><th>genres</th><th>production_companies</th><th>release_date</th><th>vote_count</th><th>vote_average</th><th>release_year</th><th>budget_adj</th><th>revenue_adj</th>
 </tr>
 <tr>
  <th>135397</th><th>tt0369610</th><th>32.985763</th><th>150000000</th><th>1513528810</th><th>Jurassic World</th><th>Chris Pratt|Bryce Dallas Howard|Irrfan Khan|Vi...</th><th>http://www.jurassicworld.com/</th><th>Colin Trevorrow</th><th>The park is open.</th><th>monster|dna|tyrannosaurus rex|velociraptor|island</th><th>Twenty-two years after the events of Jurassic ...</th><th>124</th><th>Action|Adventure|Science Fiction|Thriller</th><th>Universal Studios|Amblin Entertainment|Legenda...</th><th>6/9/15</th><th>5562</th><th>6.5</th><th>2015</th><th>1.379999e+08</th><th>1.392446e+09</th>
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

