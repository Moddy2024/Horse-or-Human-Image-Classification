# Horse-or-Human-Image-Classification-using-CNN
I have trained a CNN for a  Binary Classification task. It's job is to classify and tell if it's a image of a Horse or Human. The datset has been created using Computer Generated Images(CGI) of Horses and Humans, created by Laurence Moroney. I trained the model with the computer-generated images of horses and humans and it's actually able to classify the real-world images of horses and humans. The CNN has 6 Convolution layers with 6 Max Pooling layers and 3 dropout layers on third, fifth and after flattening the CNN. I trained this on a GPU for 102 epochs this took about 48 mins. It didn't took much long as the dataset is not that huge.

# Dataset
The full set of images used for training are [here](https://storage.googleapis.com/laurencemoroney-blog.appspot.com/horse-or-human.zip) and the validation set is [here](https://storage.googleapis.com/laurencemoroney-blog.appspot.com/validation-horse-or-human.zip). You can even download it from the first cell of this notebook [horse-or-human.ipynb](https://github.com/Moddy2024/Horse-or-Human-Image-Classification/blob/main/horse-or-human%20.ipynb).

# Software requirements
To be able to run this you need to have installed
* [Tensorflow](https://www.tensorflow.org/tutorials)
* [Visual Keras](https://github.com/paulgavrikov/visualkeras)
* [Matplotlib](https://matplotlib.org/)
* [Numpy](https://numpy.org/)
* [Keras](https://keras.io/)
* [Scikit learn](https://scikit-learn.org/stable/)


# Key Files
* [horse-or-human.ipynb](https://github.com/Moddy2024/Horse-or-Human-Image-Classification/blob/main/horse-or-human%20.ipynb) - In this file it shows how I have moved some of the data from the validation set to the training set, I have also shown how the CGI data looks like. The training of the model is also done in this notebook, you can see the visualization of the CNN that has been used, I have created that using visual keras. In the last cell you can see how the data looks like after passing through the different layers of the Convolutional layers.
* [trained models](https://github.com/Moddy2024/Horse-or-Human-Image-Classification/tree/main/trained%20models) - Out of all the 10 models saved. I kept the best two models in this folder they are available in h5 and pth format.
* [prediction.ipynb](https://github.com/Moddy2024/Horse-or-Human-Image-Classification/blob/main/prediction.ipynb) -  Using any one of the trained model files from the above folder and images from the below folder, this predicts if it's a picture of a horse or a human.
* [test data](https://github.com/Moddy2024/Horse-or-Human-Image-Classification/tree/main/test%20data) - Here I have added some of the images that I have randomly saved from the internet which I have used for testing the models.

# Training and Validation Image Statistics
The training set contains of 500 rendered images of various species of horse in multiple poses in multiple locations. It also includes 527 rendered images of humans in different poses and backgrounds. There is a diversity of humans, so there are both men and women and Asian, Black, South Asian, and Caucasians present in the training set. The validation set adds six different figures to ensure breadth of data. The size of the images in both the set are 300×300 they have been created using CGI.




