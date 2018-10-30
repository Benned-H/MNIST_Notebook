# MNIST_Notebook
## Summary
This was my Keras implemention of a CNN which classifies the MNIST dataset. I also submitted this code to the related Kaggle 
competition. The Jupyter Notebook includes my sources as well as extensive comments/documentation in order to explain what 
each line of code does.

### Date
Developed in September/October of 2018.

### Goals
My main goal with this project was introduce myself to the Keras library, as well as to submit something of my own through the 
Kaggle submission process. I added methods to save/load Keras models into the Notebook in order to save ongoing training 
progress on a given Keras model.

### Process
I coded the notebook by primarily following along a tutorial for creating a CNN in Keras for classifying MNIST the dataset.
I altered the layers of my CNN from the tutorial's suggestion, simply to add additional possible accuracy to the network. 
During this process, I eventually had to transition the MNIST import statements to Kaggle's format, which uses .csv files. 
Near the end of my work, someone suggested that I add the ability to save and reload a trained model, which I then did. The 
Github repo contains one such model that I trained and reloaded a few times to get the CNN up to 30 epochs over the dataset.

### Project's Result
A Jupyter Notebook as well as an ongoing Keras CNN model capable of additional training.
My Kaggle submission is in the Top 32% of submissions. My model achieved 99.157% accuracy after 30 epochs.
