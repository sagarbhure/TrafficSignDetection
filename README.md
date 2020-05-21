# Implementing TrafficSignNet, our CNN traffic sign classifier
We’ll discuss the concept of traffic sign classification and recognition, including the dataset we’ll be using to train our own custom traffic sign classifier.
![alt text](https://github.com/sagarbhure/TrafficSignDetection/blob/master/maxresdefault.jpg)
Traffic sign classification is the process of automatically recognizing traffic signs along the road, including speed limit signs, yield signs, merge signs, etc. Being able to automatically recognize traffic signs enables us to build “smarter cars”.

Traffic sign recognition is just one of the problems that computer vision and deep learning can solve. The Keras Framework used to develop CNN model for traffic signal classification. 
![alt text](https://github.com/sagarbhure/TrafficSignDetection/blob/master/TrafficSignNet.png)

### Our Traffic Sign DataSet

The dataset we’ll be using to train our own custom traffic sign classifier is the German Traffic Sign Recognition Benchmark. [GTSRB Kaggle](https://www.kaggle.com/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign). Download the dataset and keep it in workind directory.

The benchmark has the following properties:
* Single-image, multi-class classification problem
* More than 40 classes
* More than 50,000 images in total
* Large, lifelike database

In the real-world, traffic sign recognition is a two-stage process:
* **Localization**: Detect and localize where in an input image/frame a traffic sign is.
* **Recognition**: Take the localized ROI and actually recognize and classify the traffic sign.
### Installation and Setup
```
$ pip install opencv-contrib-python
$ pip install numpy
$ pip install scikit-learn
$ pip install scikit-image
$ pip install imutils
$ pip install matplotlib
$ pip install tensorflow==2.0.0 # or tensorflow-gpu
```

### Prject Structure

Working Directory should have: following structure.
![alt text](https://github.com/sagarbhure/TrafficSignDetection/blob/master/folder_preview.PNG = 250x250)

### Result
As you can see, our traffic sign classifier is correctly recognizing our input traffic signs!

![alt text](https://github.com/sagarbhure/TrafficSignDetection/blob/master/19.png)
![alt text](https://github.com/sagarbhure/TrafficSignDetection/blob/master/7.png)
