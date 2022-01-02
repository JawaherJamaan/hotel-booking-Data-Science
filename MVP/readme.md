# MVP of hotel-booking-canceleation

In this folder, the Minimum Viable Product (MVP) is provided. 

The initial steps in detail are provided in the Jupyter notebook. 
The data explored in addition to the EDA phase is done. 

## The MVP notebook summarizes the following: 
- Explore the features 
- Drop some unnecessary features like ('agent','company')
- drop missing value and duplicate row.
- Create one-hot-encoding for the customer_type and reservation_status
- intger encoding for ```hotel``` to (0,1)and ```arrival_date_month name``` to number month as int 
- the target of data is ```is_canceled``` (Label feature)
- Apply the ```LogisticRegression```
- Train and test a LogisticRegressions model to classify the data and got 1.0


The following figure illustrates the number of nights people stay in city hotel has more vacationers for the short term 
and resort hotel a different rate, between 1 to 5 nights for staying long term.

![pos_neg_sent](https://github.com/JawaherJamaan/hotel-booking-Data-Science/blob/main/MVP/Period%20stay.png)


## There are a few more steps to finish the project: 
- Try to ito develop the model. 
- test model by confusion matrix.
- Use different models like KNN. 

