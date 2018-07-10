# Vehicle and License Plate Detection
## Packages
Clone and download [Tensorflow models](https://github.com/tensorflow/models).\
Follow [Object Detection API](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/installation.md) for detailed procedure.\
Clone and download this repository and place it in the ```tensorflow/models/research/object_detection/``` folder.

## About
This model consists of 3 classes-
1. numberplate
2. car
3. vehicle
We created a dataset of 500 mixed images manually by using [LabelImg](https://github.com/tzutalin/labelImg).
We have already trained the model with the help of [Custom Object Detection API Tutorial](https://pythonprogramming.net/custom-objects-tracking-tensorflow-object-detection-api-tutorial/).

## Run
For detection in videos, run
```
video.py
```
For detection in static images, run
```
vehicle-lp-detection.ipynb
```
