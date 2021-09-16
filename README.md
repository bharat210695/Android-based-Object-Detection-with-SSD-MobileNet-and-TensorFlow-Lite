An Android Based Object Detection with Audio Feedback to assist Visually Imapaired Person.

# Overview

This is a camera app that continuously detects the objects (bounding boxes and
classes) in the frames seen by your device's back camera,The application allows us to identify and locate surrounding objects in an image or video from a mobile camera to assist visually impaired users.To recognize instances of a predefined set of object classes (e.g. {people, cars, bikes, animals}) and describe the locations of each detected object in the image using a bounding box.The output of the result as  an audio speech so that the visually impaired person could hear.
Using a quantized
[MobileNet SSD](https://github.com/tensorflow/models/tree/master/research/object_detection)
model trained on the [COCO dataset](http://cocodataset.org/) and using TensorFlow Lite Library[https://www.tensorflow.org/] with Text-to-Speech API for voice output. 

# Original (https://github.com/tensorflow/models/tree/master/research/object_detection) android
version then added speechtotext api with application






