# Malaria-Cells-Classification

This project uses the Machine Learning algorithms like K-Nearest Neighbors and implements a deep learning- Convolutional Neural Network with tensorflow using keras API. <br></br>
**DATA**
* This Dataset is taken from the official NIH Website https://ceb.nlm.nih.gov/repositories/malaria-datasets/. The dataset contains a total of 27,558 cell images with equal instances of parasitized and uninfected cells. As, there are equal number of instances for infected and uninfected images, the dataset is balanced. The data was collected as part of Malaria Screener research activity.
* The Dataset contains 2 folders – Parasitized and uninfected
* The images are colored with 3 channels- Red, Green and Blue (RGB) and are of diferent sizes in terms of pixels, so we resize every image to 32*32 pixel. This increases loading efficiency as well as maintains uniformity of data.
* Labels are created while loading images from respective folders.
    * Class 0 - Uninfected
    * Class 1 - Infected
* Loading - The images were loaded from the respective folders and were assigned a label of 0 (uninfected) and 1(infected) while loading.
* Resizing - To ensure uniform data, each image was resized to 32x32 pixels and loaded to numpy arrays.
* Shuffling - The images are loaded in an order, first infected cells, and then uninfected cells. To obtain a randomized dataset, we shuffle the images.
* Visualizing data- for better understanding. We can see deformed infected cells.

**KNN**
* Training and classification using KNN.
* Hyperparameter tuning using n-fold cross validation
* Evaluation 

**CNN**
* Training and classification using Convolutional Neural Network 
* Tuning and experimenting with different parameters and components of Neural Network
* Evaluation
