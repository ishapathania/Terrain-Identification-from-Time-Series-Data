# Terrain-Identification-from-Time-Series-Data
The overall objective of this project is to create a model that can predict the terrain based on the readings received by the gyroscope and accelerometer attached to the subject walking in four situations, namely, "Standing/Walking", "Going downstairs","Going Upstairs", "Walking on grass".

* The dataset is available at https://ieee-dataport.org/open-access/lower-limb-prostheses-environmental-context-dataset
* The entire code is in the jupyter notebook format.
* Change the path variable of the training data set and the test data set accordingly
* Run the cells sequentially to first read the data and preprocess the data.
* Then Run the cell that divides the training dataset into a separate training and test data set
* Next, Run the cell which applies ADASYN to the train data set and then the next cell converts the labels into one hot encoded vectors
* The next function is a window function which converts the data into 3-Dimensions.
* Running the subsequent functions would intitialize the model and train it accordingly and plot the learning curves, F1 scores and confusion matrix.
* The next few functions will generate the test set predictions.


