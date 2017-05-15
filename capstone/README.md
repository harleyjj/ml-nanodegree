# Machine Learning Nanodegree Capstone
## Multi-Digit Number Classification with Convolutional Neural Networks

Project uses TensorFlow, which requires Python 3.5.  Also uses Anaconda package, including Jupyter Notebook, and Pyplot, PIL, and Pickle

To replicate steps of project:

1) MNIST.ipynb downloads MNIST dataset and extracts data in addition to training

2) SVHN_preprocess.ipynb should be run before attempting to train multi-digit classifiers.  Downloads, extracts, preprocesses, and pickles

3) basic_model.ipynb is MNIST model altered to integrate 5 digit classifiers and different image sizes

4) standard_loss_trainer.ipynb model applies principles from Goodfellow architecture to MNIST model

5) weighted_loss_train.ipynb is the same as standard_loss, but integrates weights on digit classifiers in loss function

6) test_images_from_google.ipynb takes images from Test_Images folder, preprocesses them, and pickles them for testing with 3 multi-digit 
   classifiers, after training, saving, and restoring them first.  
