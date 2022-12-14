# ICVR-object-detection
### The goal of our object detection system is to correctly detect workers, their reflective vest and safety helmet
### The detection are based on [darknet framework](https://github.com/AlexeyAB/darknet)
### There are two ways to inference: cloning darknet framework, building and testing your image or using [darknet_inference.py](https://github.com/MikeMACintosh/Inference-Darknet-Yolov4-on-Python/blob/main/darknet_inference.py)

<pre/>
$ git clone https://github.com/AlexeyAB/darknet
</pre>

### To reproduce this through CLI load [darknet checkpoints](https://drive.google.com/drive/folders/16lyxCtGiIK4Bj22AD8-nmZniR5SGN35m) and run in darknet root this commands and paste path to image (last prediciton will be saved in predictions.jpg) or use [darknet_inference.py](https://github.com/MikeMACintosh/Inference-Darknet-Yolov4-on-Python/blob/main/darknet_inference.py):
<pre/>
$ wget https://drive.google.com/drive/folders/16lyxCtGiIK4Bj22AD8-nmZniR5SGN35m
$ ./darknet detector test obj.data yolo-obj.cfg backup/yolo-obj_5000.weights
</pre>

#### Keep in mind that to launch you will need to build darknet on your machine or in Google Collab and edit yolo-obj.cfg for your environment

![predictions](https://user-images.githubusercontent.com/85686842/196692771-948b7a46-1f1f-4124-9876-2d4efdcbc702.jpg)

#### Dataset in yolo format [google drive](https://drive.google.com/file/d/1BKMXnyPFT6uFWCSbyrZ7r5st9bCQwb2T/view) or [kaggle dataset](https://www.kaggle.com/datasets/mikhailma/railroad-worker-detection-dataset)

