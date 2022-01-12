# Predicting the Booking cancellations for hotels <br>
This repository to meet requirements for data science bootcamp with SADIA. <br>
Jawaher Alzahrani <br>

## Abstract <br>
Booking cancellations are undoubtedly one the biggest headaches of any revenue manager or hotel manager nowadays.So I worked with data contains booking information provided by [Kaggle](https://www.kaggle.com/jessemostipak/hotel-booking-demand/code) .The goal of this project was to use classification models to predict  the hotel booking's cancellation to help improve operations and  planning to arrange of these reservations. by use three model (Logistic regression, k-nearest neighbors, and random forest )to achieve promising results for this problem.With this information hotels can, for example, contact clients that the model predicted will cancel in order to get a cancellation earlier - so they can have more time to resell the room. Or perhaps approach the client in a way to make them feel special and keep their reservation and therefore cancel the others he or she had made in other hotels in the same city.<br>
## Design<br>
This project is one of the T5 Data Science BootCamp requirements. Data provided by Kaggle has been used in this project. The Hotel booking demand data included our target variable (is_canceled) value indicating if the booking was canceled (1) or not (0). Improve unbalanced data use resampling to fit model.<br>
## Data <br>
The dataset contains 119390 reservations with 32 features for each, 12 of which are categorical and  the other is numeric. 
This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things.<br>

## Algorithms <br>

*Feature Engineering* <br>
1. Mapping Month name to number of month as  integer encoding<br>
2. Converting categorical features to binary dummy variables <br>
3. drop some fearure unnecessary <br>
4. drop missing value and duplicate row <br>
5. apply Random Oversampling the data was imbalance <br>

## Models <br>
  
Logistic regression, k-nearest neighbors, and random forest classifiers were used before settling on Random forest as the model with  better cross-validation performance as realistic value. <br>
## *Model Evaluation and Selection* <br>
  
Logistic regression, k-nearest neighbors, and random forest were used to classify the canceleation booking.The models were trained on a 80/20 test vs. train. In this project we saw that we can predict reservations that will cancel with a confidence .The official metric was the accuracy of the model, where the model tested on the accuracy, precision, recall, and F1 score. The result of used model:<br>

Logistic regression:<br>
Accuracy: 97% <br>
Precision: 94% <br>
Recall: 95% <br>
F1: 94.6% <br>

KNN: <br>
Accuracy: 97.4% <br>
Precision: 94% <br>
Recall: 96.8% <br>
F1: 95% <br>

Random forest: <br>
Accuracy: 97.8% <br>
Precision: 95.5% <br>
Recall: 96.6% <br>
F1: 96% <br>


## Tools <br>
- Numpy and Pandas for data manipulation <br>
- Scikit-learn for modeling <br>
- Matplotlib and Seaborn for plotting <br>
- imbalanced-learn to undersampling  <br>

## Communication <br>
the slides  [here](https://github.com/JawaherJamaan/hotel-booking-Data-Science/blob/main/Final/Presentation%20-%20Hotel%20Booking%20Cancelation.pdf)

