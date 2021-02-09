# -GRIPFEB21-Snehal_Dhavale-

YOLO is a state-of-the-art, real-time object detection algorithm. In this notebook, we will apply the YOLO algorithm to detect objects in images. We have provided a series of images that you can test the YOLO algorithm on. 

We will start by loading the required packages into Python. We will be using OpenCV to load our images, matplotlib to plot them, autils module that contains some helper functions, and a modified version of Darknet. YOLO uses Darknet, an open source, deep neural network framework written by the creators of YOLO. The version of Darknet used in this notebook has been modified to work in PyTorch 0.4 and has been simplified because we won't be doing any training. Instead, we will be using a set of pre-trained weights that were trained on the Common Objects in Context (COCO) database. For more information on Darknet, please visit Darknet.

We will be using the latest version of YOLO, known as YOLOv3. We have already downloaded the yolov3.cfg file that contains the network architecture used by YOLOv3 and placed it in the /cfg/ folder. Similarly, we have placed the yolov3.weights file that contains the pre-trained weights in the /weights/ directory. Finally, the /data/ directory, contains the coco.names file that has the list of the 80 object classes that the weights were trained to detect.

