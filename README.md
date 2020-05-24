## Udacity's Data Scientist Nanodegree Capstone Project: Dog Breed Classifier

### Project Overview

This project uses Convolutional Neural Networks (CNNs) and transfer learning in order to build a pipeline to process real-world, user-supplied images. Convolutional Neural Networks (CNNs) are commonly used to analyse image data. Transfer learning is a technique that allows to reuse a model across different tasks. The objective is that given an image of a dog, the algorithm will identify an estimate of the canine’s breed. If supplied an image of a human, the code will identify the resembling dog breed. If the algorithm can't identify the image as a human or dog, it will say so.

### Table of Contents

1. [Libraries](#libraries)
2. [File Descriptions](#files)
3. [Content](#contents)
4. [Findings](#findings)

### Libraries <a name="libraries"></a>

    Keras
    OpenCV
    Matplotlib
    Numpy

### File descriptions <a name="files"></a>

* dog_app.ipynb: Jupyter notebook containing the algorithm and process used to create it.
* dog_app.html: A copy of dog_app.ipynb in html format.
* Haarcascades folder: Xml file for use with the OpenCv face detector class.
* Various images: Images in jpg and jpeg format used to test the algorithm's predictions.


### Contents <a name="contents"></a>

The project is organized along the following steps:

    Intro
    Step 0: Import Datasets
    Step 1: Detect Humans
    Step 2: Detect Dog
    Step 3: Create a CNN to Classify Dog Breeds (from Scratch)
    Step 4: Create a CNN to Classify Dog Breeds (using Transfer Learning)
    Step 5: Write Your Algorithm
    Step 6: Test Your Algorithm

### Findings <a name="findings"></a>

* The model achieved a test accuracy of 77.99%, which is above the 60% established accuracy threshold.
* The model predicted the same two or three breeds when identifying an image as human. Therefore more variety is needed concerning the type of breeds the model predicts for humans. 
* Some of the breeds have similar colors and shapes but differ in size, as is the case between a Beagle and a Pointer or American Foxhound. Therefore the model needs to pick up subtle differences between similar breeds. 
* The model could use some improvements on its ability to classify pictures with noise. This is probably due to the images it was trained on.
