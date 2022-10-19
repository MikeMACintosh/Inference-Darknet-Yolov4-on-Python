# ICVR-object-detection
### The goal of our object detection system is to correctly detect workers, their reflective vest and safety helmet
### The detection are based on [darknet framework](https://github.com/AlexeyAB/darknet)

#### The image below clearly demonstrate detection example:)
#### To reproduce this through CLI load [darknet checkpoints](https://drive.google.com/drive/folders/16lyxCtGiIK4Bj22AD8-nmZniR5SGN35m) just pust in darknet root this command:
<pre/>
wget https://drive.google.com/drive/folders/16lyxCtGiIK4Bj22AD8-nmZniR5SGN35m
./darknet detector test obj.data yolo-obj.cfg backup/yolo-obj_5000.weights
</pre> 
![predictions](https://user-images.githubusercontent.com/85686842/196692771-948b7a46-1f1f-4124-9876-2d4efdcbc702.jpg)
