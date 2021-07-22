
# eye
--------

It is difficult to make a model that functions as a human eye. Object detection, face recognition, depth calculation, object tracking ... tasks are difficult to do by a single ML model.  In this project, I am trying to combine all computer vision models to mimic the human eye i.e single function that do all computer vision tasks.


<img src="/githubimages/demo.gif" alt="GitHub badge" />



## Install

To install the current release
```shell
$python3 -m venv venv
$source venv/bin/activate
$pip3 install requirements.txt

$pip3 freeze > requirements.txt # after add some feature freeze all dependencies

```

## Usage

Move toward project folder
```shell
$ cd eye
```

Run single function that do computer vision tasks.

```shell

$ python inference.py

```

## Hardware devices

1. [Coral tpu](https://coral.ai/) for object detection
2. [Intel® RealSense™ Depth Camera D435](https://www.intelrealsense.com/depth-camera-d435/) for calculating the depth of an image
3. [Face recognition library](https://pypi.org/project/face-recognition/) for face recognition
4. Object tracking custom algorithm for object tracking
    





