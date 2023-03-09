
# Transport Demand Prediction



# Problem Statement

In this project the task was to build a machine learning model to predict the ticket demand prediction of the vehicle according to each ride id which were travelling from 17 diffrent locations and travelling to Nairobi.

# Project Summary 

In this project the task was to build a machine learning model to predict the ticket demand prediction of the vehicle according to each ride id which were travelling from 17 diffrent locations and travelling to Nairobi.

In this at first I explored the data and find out insights from the data and plotted them by using amazing visualizations with the help of libraris like matplotlib and seaborn. While doing the exp[loratory data analysis i found out that in the dataset their is no target column which will tell us about the number odf seats booked in each ride id, so i created the target feature by applying group by mehod on ride ids and considerd the nunique seat numbers booked in each ride id.

Then I preformed rigouros feature engineering on the dataset and created multiple new features by using existing features. which was nescassry for getting good iunsights and better model performance. For building model to get the predictions i have used algorithms like Linear regression, Lasso regression , Ridge egression, Random forest algorithm, Gradient bosting algorithm and Xtreme gradient boosting algorithm. Then i did hyperparameter tunning on all these algorithms. I have used r2 score as ou primary evaluation metric of the model and after observing scores for all the algorithms i observed that by doing hyperparameter tunning on XGBoost algorithym we can get the best r2 score value which was 0.70 and considerd this score as best score and best model anmong all the other models.


# Data Description



- ride_id : Unique id of a vechicle on a specific route on a specific day and date.

- Seat_number : Seat assigned to ticket

- payment_method : Method used by customer for purhasing ticket.

- payment_receipt : Unique id number for purchased ticket from mobiticket

- travel_date : Date of ride departure

- travel_time : Time of ride departure

- travel_from : Town from which ride originated

- travel_to : Destination of ride.

- car_type : Vechicle type ( shuttle or bus)

- max_capacity : Maximum capacity of vechicle.


# ML Model Implementation

Xtreme Gradient Boosting algorihym has given the best score  r2 score = 0.70
