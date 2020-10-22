# Image-Segmentation-and-Crowd-Density-Estimator

YOLO :
YOLO papers: Redmon et al., 2016 (https://arxiv.org/abs/1506.02640) and Redmon and Farhadi, 2016 (https://arxiv.org/abs/1612.08242)
YOLO ("you only look once") is a state-of-the-art, real-time object detection algoritm because it achieves high accuracy while also being able to run in real-time. This algorithm "only looks once" at the image in the sense that it requires only one forward propagation pass through the network to make predictions. After non-max suppression, it then outputs recognized objects together with the bounding boxes.

YOLO uses Darknet, an open source, deep neural network framework written by the creators of YOLO. The version of Darknet used in this notebook has been modified to work in PyTorch 0.4 and has been simplified because training was not done. Instead, a set of pre-trained weights that were trained on the Common Objects in Context (COCO) database is used.

Non-max suppression : 
Filter for selecting the right boxes is called non-maximum suppression (NMS).
Non-max suppression uses the very important function called "Intersection over Union", or IoU. 
YOLO uses Non-Maximal Suppression (NMS) to only keep the best bounding box.

OpenCV to load images.
matplotlib to plot them.

