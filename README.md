# Cats-vs-Dog-Classification
Using CNN, the model classifies between cat and dog images. I used a dataset from Kaggle and to execute this project I used tensorflow. Additionally, I also saved the weights and the model and have uploaded the files as well. 

The code file starts out with reading the necessary libraries and then starts reading the paths for the images. In my dataset, there were two folders; cats and dogs. Both of them only contained photos so there were no separate files for training data and testing data. In order to attain the testing and training data, I first read through both folders and stored the cat and dog images in separate dictionaries. I also saved the labels - whether its a cat or a dog depicted as the value 0 or 1 - in another dictionary. 

Then I set onto split the dataset into testing and training dataset after combining the cat and dog images. The training dataset was loaded into the model. The model consists of 4 hidden layers; after each layer we have the BatchNormalization. The activation fucntion used throughout the hidden layers was Relu and also in the 1st fully connected(FC) layer as well. In the last FC, we have the sigmoid activation fucntion to predict if its a cat or a dog.

The accuracy that was acquired after training and testing was 0.9821029305458069 or 98.2%.
