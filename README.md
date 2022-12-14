# Real-industry-projects [Mercedes-Benz-benchtime-prediction]
DESCRIPTION

Reduction of the time a Mercedes-Benz spends on the test bench.

Problem Statement Scenario:

Since the first automobile, the Benz Patent Motor Car in 1886, Mercedes-Benz has stood for important automotive innovations. These include the passenger safety cell with a crumple zone, the airbag, and intelligent assistance systems. Mercedes-Benz applies for nearly 2000 patents per year, making the brand the European leader among premium carmakers. Mercedes-Benz is the leader in the premium car industry. With a huge selection of features and options, customers can choose the customized Mercedes-Benz of their dreams.

To ensure the safety and reliability of every unique car configuration before they hit the road, the company’s engineers have developed a robust testing system. As one of the world’s biggest manufacturers of premium cars, safety and efficiency are paramount on Mercedes-Benz’s production lines. However, optimizing the speed of their testing system for many possible feature combinations is complex and time-consuming without a powerful algorithmic approach.

I was required to build a solution that will enable the car manufacturer to reduce the time that cars spend on the test bench. I worked with a dataset representing different permutations of features in a Mercedes-Benz car to predict the time it takes to pass testing. Optimal algorithms contributed to faster testing, resulting in lower carbon dioxide emissions without reducing Mercedes-Benz’s standards.

I then performed the following tasks:

1) I've loaded and explored data using pandas
2) I've Identified columns which had zero variance (using var() capability of pandas)
3) I've applied label encoder to columns containing categorical values
4) I've applied dimensionality reduction using PCA
5) I've split the training data in to train and validation sets
6) I did some fitting and predicting using to different algorithms (xgboost and randomforeset regressor)
7) I've measured the performance using mean square error metric.
