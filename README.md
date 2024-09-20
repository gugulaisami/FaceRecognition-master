# A face recognition software 
This project involves developing a face recognition software based on the YOLOv5 module and a laptop camera. The focus is on identifying who the person is. The recognized person is captured as an image and stored in an openGauss database, along with the time and name of the person.

# Using pytorch, applying the following 2 methods to achieve face recognition:
1. yolocv5+facenet+svm
2. HOG+dlib+svm

# For the first method, I referred to a Tutorial on CSDN:
https://blog.csdn.net/qq_41334243/article/details/107425492

# For the second method, I referred to a blog on CSDN:
https://blog.csdn.net/qq_41334243/article/details/107425492

# Reproduce Your Training
Download [celeba](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html) and [yolov5](https://github.com/ultralytics/yolov5), install [Apex](https://github.com/NVIDIA/apex) and run command below. I used yolov5s for training,you can use other weights to train your own model.

# Requirements
Python 3.7 or later with all `requirements.txt` dependencies installed, including `torch >= 1.5`. To install run:
```bash
$ pip install -U -r requirements.txt
```