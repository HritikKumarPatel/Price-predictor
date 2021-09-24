# Price-predictor
I have built a Price Predictor which tells us the price of any area with the help of 13 attributes given about that area. 
I have basically tried three regression models:-
a.) Linear Regression 
b.) Random Forest Regression 
c.) Decision Tree regression 
Out of which Random Forest performed best for me so finalized that.
In this, I handled many of the corner cases like:-
a.) what if the data has NULL values at some points
b.)overfitting which I solved using crorr_val_score or k-fold technique
c.)equal distribution of data like only 0 and 1 in right proportion using stratified shuffle split.
