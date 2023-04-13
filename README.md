# Custom Object Detection using Tensorflow API

[![TensorFlow 2.8](https://img.shields.io/badge/TensorFlow-2.8-FF6F00?logo=tensorflow)](https://github.com/tensorflow/tensorflow/releases/tag/v2.8.0)
[![Python 3.10.6](https://img.shields.io/badge/Python-3.10.6-3776AB)](https://www.python.org/downloads/release/python-360/)

This Project is used to train custom object detection using Tesorflow api
(Supervised Learning )Creating accurate machine learning models capable of localizing and identifying
multiple objects in a single image remains a core challenge in computer vision.
The TensorFlow Object Detection API is an open source framework built on top of
TensorFlow that makes it easy to construct, train and deploy object detection
models.
This project is trained solely for small dataset of class dog

<p align="center">
  <img src="result_19.png" width=140 height=195>
</p>

### Tensorflow 2.x
Here I particularly used ssd_resnet101_v1_fpn_640x640_coco17_tpu-8.tar.gz 
But a model of own choice can be used from model zoo
*   <a href='g3doc/tf2_detection_zoo.md'>
        TensorFlow 2 Model Zoo</a><br>
        
<h2>Links:<img src = "https://media1.giphy.com/media/JZ40cnfnN11KycrvMF/giphy.gif?cid=ecf05e47a0n3gi1bfqntqmob8g9aid1oyj2wr3ds3mg700bl&rid=giphy.gif" width = 64> </h2>
 Collaboratory link:
https://colab.research.google.com/drive/1bBMWKeAUsNU3In-MrqhCvQBZDktJpRCM?usp=sharing <br>
Drive Link with all the files and dataset used:
https://drive.google.com/drive/folders/1ecJA16_up1alKoik0mSzQimf39yN_zBU?usp=sharing

# Deployment
- To clone copy the following command in your terminal and start development.

```sh
git clone git@github.com:nidhiss29/ObjectDetction.git
```

-Download Zip folder

-Open Colab file 

-Upload Dataset and files on colab session

-Files to be uploaded  - all .py files, pipeline.config file and pbtxt files along with dataset 


<h2>References:</h2>
Documentation:https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/training.html

<h2>Report</h2>
<a href='obj-det project report.pdf'>Project Report</a>
