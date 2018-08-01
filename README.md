# KITTI to tfrecords

This repo contains a script that I wrote in the progress of object detection with the tensorflow object detection API. It converts a dataset from the [KITTI format](http://www.cvlibs.net/datasets/kitti/) to a tfrecords file. 
Some of the images and groundtruth bounding boxes can be read out from the file and displayed for validation purposes.

# Usage:
 - Put all the images (.jpg .jpeg or .png) and the respective .txt in the same folder
 - Adjust paths in the first lines of the script to your needs
 - run dataset_conversion.py
 - repeat same progress for train/val data respectively

# References:
https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/using_your_own_dataset.md
https://github.com/yeephycho/tensorflow_input_image_by_tfrecord

# Credits:
[excelite](https://github.com/excelite)

# Requirements:
python2.7, Tensorflow > 1.5, matplotlib
