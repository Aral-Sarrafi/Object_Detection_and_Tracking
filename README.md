# Vehicle Detection and Tracking

With in this project a simple object detection and tracking pipeline is implemeted to detect cars in a video stream. The outline of the project is as follows:

### 1. Data Visualization
### 2. Feature Extraction
### 3. Training the Support Vector Machine (SVM)
### 4. Sliding Window Approach
### 4. Objection Detection on Images
### 5. Object Detection on Video Stream

In the next couple of paragraph each of the sections will be discussed in detail.

### 1. Data Visualization

The vehicle and non vehicle image data sets were used to train the SVM calssier. This data set contains 8792 images of vehicles and 8968 non-vehicle images. All the images are RGB 64*64 images.The number samples per class in very close that garantees that the trained classifies will not be biased toward any of the classes. The figure below shows some example of images from this data set.
