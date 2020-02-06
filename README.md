# DataMining
Project done for SIN460, where we had to use KNN-algorithm to classify our dataset.
You can get the dataset in https://archive.ics.uci.edu/ml/datasets/Wine

My first attempts were difficult because I didn t know how to do the preprocessing methods so I did what I thought it was in RedWine1 and RedWine2.

RedWine1 is the first data mining code done for this dataset but since we could see that there was a bad distribution of data, our results were affected giving us an illusion that they would predict almost always right when in reality the algorithm was only choosing one value to predict.

RedWine2 is a better version of the fist because I was able to divide the attributes into two large groups without a significant distance between the two, that way our algorithm was able to actually choose between two values instead of one.

Now we have WineQuality1 where even though we had PCA and Stratified KFold it wasn't enough and our model had a high accurancy which we know it is not like that. And WineQuality2 with KFold so our results are even more accurate in their predictions.

KMeans is the clustering of a client problem we had.
