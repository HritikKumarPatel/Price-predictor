# Price-predictor
I have built a Price Predictor which tells us the price of any area with the help of 13 attributes given about that area. </br>
I have basically tried three regression models:- </br>
a.) Linear Regression </br>
b.) Random Forest Regression </br>
c.) Decision Tree regression </br>
Out of which Random Forest performed best for me so finalized that. </br>
In this, I handled many of the corner cases like:- </br>
a.) what if the data has NULL values at some points </br>
b.)overfitting which I solved using crorr_val_score or k-fold technique </br>
c.)equal distribution of data like only 0 and 1 in right proportion using stratified shuffle split. </br>
