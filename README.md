# plinkogame
Revising ML with JS -Simulation of popular game Plinko using the KNN algorithm. 

Concepts covered:

1. Identifying data, assembling them (for dropPosition, bounciness, size, bucketLabel)

2. Deciding the type of output

3. Picking algorithm (K nearest neighbor)

4. Using model(s) to predict - classification 


KNN implementation
a. Drop the ball around the board, and record values
b. For each observation, take the absolute value
c. Sort results from least to great
d. What are the top k records- common values
e. What came frequently, and where will it goto


Improving Efficiency
1. Adjust parameters of analysis
2. Add more features
3. Change prediction point
4. Accept, there might not be a good co-relation


Some important functions:

Function knn    - To implement KNN algorithm
Function distance - Check the distance between multiple features 
Function splitDataset - To split data into testSet and trainingSet
Function minMax - To achieve Normalisation


Utility Library used: Lodash
