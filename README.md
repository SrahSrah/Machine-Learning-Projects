# Predicitng Bike Rentals:

A basic neural network that uses traditional matrix multiplication (rather than TensorFlow). This was my first neural network and a great way to understand the math behind neural networks before utilizing more convenient deep-learning packages in later projects. 

This dataset has the number of riders for each hour of each day from January 1 2011 to December 31 2012. I used Stochastic Gradient Descent to train the network, resulting in a training loss of 0.109 and 0.218. A comparison of the model's predicitions versus reality is below. As you can see, the model accurately predicits the number of bike rentals needed throughout the month of December, however, the model begins to overpredict as the Christmas approaches. Because the data only spans two calendar years, the model is fairly accurate at predicting a typical week of rentals, but has yet to adjust its predictions for the holidays. To correct this overprediction, additional years of data would be required.

![alt text](https://github.com/SrahSrah/Predicting-Bike-Rentals-ML/blob/master/results.png)
