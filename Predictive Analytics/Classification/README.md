
In this exercise, we worked with NBA rookie data to predict whether a player will last at least five years in the league. 
We used various stats like games played, points, assists, and rebounds to train our model. 
The goal was to classify the rookies into two groups: those who would last 5+ years ("Yes") and those who wouldn't ("No"). 
We first prepped the data, converted the target variable into a factor, and split the data into training and testing sets.

We then applied the k-Nearest Neighbors (K-NN) algorithm to predict the players' chances of lasting in the league. 
After standardizing the data and testing different values of k, we found that a k of 17 gave us the best results. 
We also ran the k-NN model and used a confusion matrix to evaluate its performance using recall, precision, and F1 scores for the "Yes" and "No" classes.

Next, we trained a Decision Tree model to see how it compared to k-NN. 
The decision tree helped us understand what factors (like games played and offensive rebounds) are key for a rookie to last five years. 
We also adjusted the cut-off for classifying players and compared how the results changed in terms of accuracy and other evaluation metrics.

Finally, we saved and compared the performance of both models to make the best prediction about the rookies' future in the NBA.

![image alt](https://github.com/aarern/descriptive-predictive-analytics/blob/eecaf886f056dca3253d09e917fdb9d4f8d50cb8/Predictive%20Analytics/Classification/spo1.jpg)
