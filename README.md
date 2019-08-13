# dogBreed_Classifier
this is a project provided by Udacity to classify dog breeds.

This repositery contains 3 files:
1- dog_app.ipynb.json
2- dog_app.html
3- folder with images to test the classifier.

the following libraries are used:

from sklearn.datasets import load_files       
from keras.utils import np_utils
import numpy as np
from glob import glob
import random
import cv2                
import matplotlib.pyplot as plt     
from keras.applications.resnet50 import ResNet50
from keras.preprocessing import image                  
from tqdm import tqdm
from keras.applications.resnet50 import preprocess_input, decode_predictions
from PIL import ImageFile                            
from keras.layers import Conv2D, MaxPooling2D, GlobalAveragePooling2D
from keras.layers import Dropout, Flatten, Dense
from keras.models import Sequential
from keras.callbacks import ModelCheckpoint  
from extract_bottleneck_features import *
from extract_bottleneck_features import *
import os





