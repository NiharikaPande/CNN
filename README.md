Melanoma Detection Assighnment 
This Project will help to build a CNN model to detect melanoma


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here. - This project helps to identify melanin disease by analysing using CNN Model
- What is the background of your project? - This project is based on CNN Model
- What is the business probem that your project is trying to solve? - It will help doctors to identify the cancerous skin disease
- What is the dataset that is being used? Dataset is taken from International Skin Imagining Collaboration

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions from my project
- Class which has the least number of samples is Squamous Cell 
- Classes which dominates the data in terms proportionate number of samples is Pigmented benign keratosis

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
	import pathlib
	import tensorflow as tf
	import matplotlib.pyplot as plt
	import numpy as np
	import pandas as pd
	import os
	from glob import glob
	import PIL
	from tensorflow import keras
	from tensorflow.keras import layers
	from tensorflow.keras.models import Sequential
	from tensorflow.keras.layers import Dense, Dropout, Activation, Flatten, BatchNormalization, Conv2D, MaxPooling2D
	from tensorflow.python.keras.layers import Dense, Dropout, Activation, Flatten,  Conv2D, MaxPooling2D 
	from keras.layers import Dense, Dropout, Flatten, Conv2D, MaxPool2D
	from tensorflow.keras.layers.experimental.preprocessing import Rescaling
	from keras.preprocessing.image import ImageDataGenerator
	from tensorflow.keras.regularizers import l2
	from tensorflow.keras.models import Sequential
	from keras.callbacks import ReduceLROnPlateau
	from keras.utils.np_utils import to_categorical # convert to one-hot-encoding





<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by... Upgrad
- References if any... icgi
- This project was based on [CNN Model].


## Contact
Created by [@NiharikaPande] - feel free to contact me!


