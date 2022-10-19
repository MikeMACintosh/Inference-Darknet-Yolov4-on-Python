# ICVR-object-detection
### The goal of our object detection system is to correctly detect workers, their reflective vest and safety helmet
### The detection are based on [darknet framework](https://github.com/AlexeyAB/darknet)

### To reproduce this through CLI load [darknet checkpoints](https://drive.google.com/drive/folders/16lyxCtGiIK4Bj22AD8-nmZniR5SGN35m) just run in darknet root this commands and paste path to image (last prediciton will be saved in predictions.jpg):
<pre/>
$ wget https://drive.google.com/drive/folders/16lyxCtGiIK4Bj22AD8-nmZniR5SGN35m
$ ./darknet detector test obj.data yolo-obj.cfg backup/yolo-obj_5000.weights
</pre>

#### Keep in mind that to launch you will need to build darknet on your machine or in Google Collab and edit yolo-obj.cfg for your environment

![predictions](https://user-images.githubusercontent.com/85686842/196692771-948b7a46-1f1f-4124-9876-2d4efdcbc702.jpg)

#### Dataset in yolo format [here](https://drive.google.com/file/d/1BKMXnyPFT6uFWCSbyrZ7r5st9bCQwb2T/view)

