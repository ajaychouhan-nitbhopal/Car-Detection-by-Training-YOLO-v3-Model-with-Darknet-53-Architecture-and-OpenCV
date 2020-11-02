# Car-Detection-by-Training-YOLO-v3-Algorithm-with-Using-OpenCV-and-Python
![Hits](https://hitcounter.pythonanywhere.com/count/tag.svg?url=https%3A%2F%2Fgithub.com%2Fajaychouhan-nitbhopal%2FCar-Detection-by-Training-YOLO-v3-Algorithm-with-Using-Darknet-OpenCV-and-Python)
![Hits](https://hitcounter.pythonanywhere.com/count/tag.svg?url=https%3A%2F%2Fgithub.com%2Fajaychouhan-nitbhopal%2FCar-Detection-by-Training-YOLO-v3-Model-with-Darknet-53-Architecture-and-OpenCV)
This is the code files for "Car Detection by Training YOLO v3 Algorithm with Darknet, Opencv and Python" on Car Detection [dataset](https://www.kaggle.com/sshikamaru/car-object-detection) by Ajay Chouhan.

## Overview

This is the code of Yolo v3 Algorithm which is trained on Car Detection Problem [dataset](https://www.kaggle.com/sshikamaru/car-object-detection). I used [Google Colab's](https://colab.research.google.com/notebooks/intro.ipynb#recent=true) GPU to train Yolo v3. After 1222 iterations I got 0.343448 avg loss then I stopped the training.

NOTE- I reformed original dataset according to [Darknet(framework used to run and train YOLO v3)](https://pjreddie.com/darknet/yolo/) 


## Dataset Overview
The data has been split into two groups:
1. training_images folder has 1001 images in which only 355 have car in it.
2. test_images folder has 175 images for testing model.
3. train_solution_bounding_boxes (1).csv file has Bounding boxes data of abovementioned 355 images.

NOTE- I used this CSV file to generate 355 individual .TXT files, then I made ZIP file of 355 Car's images and 355 TXT files combined. (This zip file is used to train the model). Normalisation is also done for the right annotations.
You can find the code for doing this process, in Repository as file named 'Code to make separated TXT files from CSV file.ipynb'

## Dependencies

[OpenCV](https://opencv.org/)

[Darknet](https://pjreddie.com/darknet/yolo/)

Install missing dependencies with [pip](https://pip.pypa.io/en/stable/)

## Usage
1. Train_YoloV3.ipynbis Jupyter Notebook which contains code for training YOLO v3 on Google Colab using GPU.
2. Train_YoloV3.py is Python file which contains python code of 'Train_YoloV3.ipynbis' file.
3. Code to make separated TXT files from CSV file.ipynb is jupyter notebook which contains code  to generate 355 individual .TXT files for their respected images. 
4. Car Detection True Negative Result 1.JPG, Car Detection True Negative Result 2.JPG, Car Detection True Positve Result 1.JPG, Car Detection True Positve Result 2.JPG are 4 Jpeg images which I got as result.

## Credits
This problem is taken from [Kaggle.com](https://www.kaggle.com/sshikamaru/car-object-detection)
I learned to use Google Colabs GPU to train YOLOv3 and object detection with OpenCV by [PySource](https://pysource.com/) 
