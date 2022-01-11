# CIFAR10-Classification

![]()![cifar](https://user-images.githubusercontent.com/56751947/148966740-8c9aa6fe-1940-4fd5-86cc-dba18f0da6b5.png)

## About the Dataset:

The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images.

The dataset is divided into five training batches and one test batch, each with 10000 images. The test batch contains exactly 1000 randomly-selected images from each class. The training batches contain the remaining images in random order, but some training batches may contain more images from one class than another. Between them, the training batches contain exactly 5000 images from each class.

Here are the classes in the dataset, as well as 10 random images from each:
										
![cifar1](https://user-images.githubusercontent.com/56751947/148968498-c84ea9f2-ac5e-4c00-9ef2-70e9939f007b.jpg)

The classes are completely mutually exclusive. There is no overlap between automobiles and trucks. "Automobile" includes sedans, SUVs, things of that sort. "Truck" includes only big trucks. Neither includes pickup trucks.

## Model:

The classification of objects was done using Artificial Neural Networks and then Covolutional Neural Networks.
The Artificial Neural Network performed very poorly with an accuracy of 56% on the training set. After performing **Convolutional Neural Networks**, accuracy was increased to:

Train set = 82.72%

Test set = 70%


## Classification Report using ANN

![CIFAR3](https://user-images.githubusercontent.com/56751947/148972245-4a8b7a3e-dc9a-41f9-b6a3-e1fd80cc9972.jpg)


## Classification report using CNN

![cifar2](https://user-images.githubusercontent.com/56751947/148972317-28567a17-b124-4496-84d3-e705b7432786.jpg)


Here is the link to [Google Collab](https://colab.research.google.com/drive/1WlwW3aShJDfmsjK0rRu2oaX07jt6_QUN#scrollTo=srqHTm_-wRpi)
