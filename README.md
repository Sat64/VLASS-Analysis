# VLASS-Analysis
In this, all the analysis done by me on VLASS is present here.

1. ML Full Analysis ASI.ipynb file :
Contains the loading and cleaning of data, separation measurement, plotting a histogram of columns, Basic_ML_part() function to calculate the basic properties such as accuracy, classification report, confusion matrix (converted to a percentage), and plotting it. 

- ML_Analysis() function uses AutoML from Flaml 
- Input: X, Y, an array of model names you want it to look to find an optimized solution, time_budget,k-fold.
- Analysis: 
  (a) It will divide the data into test and train. The test data will be kept as unseen data and AutoML will try to optimize within the time_budget frame to maximize the metric on 
      stratified k-fold data. Here weights are also calculated from Y_train and used to tackle the class imbalance problem.
  (b) It will then calculate the feature importance and permutation importance. This will help us to gain insight into the data.
  (c) It will then use Basic_ML_part() function to calculate the basic properties.

2. Satyapriya_ASI2024_626.pdf: Poster presentation ASI conference 2024.
3. Satyapriya_ASI2024_626.mp3: Audio File explaining the Poster for the ASI conference 2024.  
