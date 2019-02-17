# Face-Recognition using Tensorflow in Google Colaboratory
## Summary
In this project, I am using TensorFlow's Object Detection API to Recognise faces of people of different age group.Currently in this project, I have introduced only 2 classes.
I trained my model using Google Colaboratory because it is free for everyone as well as for those people who cannot afford costly GPU's. I did this project to understand how a CNN can be trained in our own way to detect/classify new objects with the help of a pretrained model.
**Note: Here I used TensorFlow Object Detection API repository from GitHub and Faster-RCNN-Inception-V2-COCO model from TensorFlow's model zoo.
## Steps to follow
- Upload files in google drive
- Connect with google colaboratory and google drive

 ![](extras/Screenshot%20from%202019-02-17%2000-52-26.png)
- Once you start the google colab notebook from your drive, you have to mount your google drive with the google colab by typing some commands.
- You have to change some settings like use python3 and use GPU for whole project.

![](extras/Screenshot%20from%202019-02-17%2001-11-08.png) 
- Once you are assigned to a GPU of Google Colab cloud service, you can use it only for a limited time.(I guess 12 hrs but it is more than enough). What ever dependencies you have downloaded in previous session will not be availabe in new session.
- The rest of the steps that I have follwed were given under reference.
I have also uploaded Tensorflow_OD.ipynb were you can see the steps I followed.

#Errors
- While generating tfrecords

 ![](OD_errors/Screenshot%20from%202019-02-13%2017-02-56.png)
I installed tensorflow just before running tfrecord generating command line.
- Other images of the errors has been uploaded along with this project. It was mainly due to installation of protobuf compiler version. exporting PYTHONPATH was also a problem so that i have to give it another way which is given in Tensorflow_OD.ipynb file.
 
#Reference
1. [Object Detection API repository](https://github.com/tensorflow/models)
2. [For downloading models](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/detection_model_zoo.md)
3. [Steps that I followed](https://github.com/EdjeElectronics/TensorFlow-Object-Detection-API-Tutorial-Train-Multiple-Objects-Windows-10#1-install-tensorflow-gpu-15-skip-this-step-if-tensorflow-gpu-15-is-already-installed)
4. [For labelling Image](https://github.com/tzutalin/labelImg)
5. [Others](https://facebookresearch.github.io/TensorComprehensions/introduction.html)
