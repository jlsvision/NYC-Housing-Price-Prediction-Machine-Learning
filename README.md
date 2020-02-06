# Predicting NYC Housing Prices using data

Homeownwes and professionals face the dilemma of working with outragous prices, whether it will be selling a home or buying a home. With this in mind, timing is crucial when making this financial decision.




<img src="images/jose-sanchez-JHrcLW42Q1Y-unsplash.jpg" width="600">  




New York is a center in the world's economy, people constantly moving in and out. Our main question was how are prices subject to various conditions such as neighborhood, size, condition, etc? What model can we use to predict future prices? What are the biggest factors in pricing and what can homeowners and buyers do about this? Columns: 22, Rows: 84,549




<img src="images/Screen%20Shot%202020-01-22%20at%2012.22.44%20AM.png" width="600">  





The dataset was acquired from the New York State Department of Finance for free, this comprehensive dataset includes 22 columns(headers) and 84,549 rows





<img src="images/Screen%20Shot%202020-01-22%20at%202.50.18%20PM.png" width="600">  





Data Cleaning: The process of data cleaning required the identification of the data we were working with. Was it categorical? Is it essential data to keep in our machine learning model?





<img src="images/Screen%20Shot%202020-01-21%20at%2011.19.59%20PM.png" width="600">  






After cleaning the dataset and identifying points of interest, we used a correlation matrix to identify the relationships each coefficient had with each other. This way we were able to explore certian properties and coefficients further.


<img src="images/Screen%20Shot%202020-01-22%20at%205.56.44%20PM.png" width="600">  




With this process we identified the training data (a representation of the data) to be fed into the Keras and Scikit Learn Regression Model. As we can see above, we ran the model at 150 epoch for best accuracy to train the model. 

<img src="images/Screen%20Shot%202020-01-22%20at%209.25.01%20AM.png" width="600">  

The model was able to create a dataset of predicted data. We visualized the data using Matplotlib and alligned it with the real data used to train the model. The results of the prediciton were actually looking positive and correlated to the data at certian points.

<img src="/images/Screen%20Shot%202020-01-22%20at%208.52.09%20AM.png" width="600">  

As we looked at the predicted data and actual data more closely we can see that the predicted price data was able to follow the same trend over time at certian points of the year. This could mean that there are price increase or decrease at specific times of the year.




