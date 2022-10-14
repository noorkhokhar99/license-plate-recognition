# License plate Detection by YOLO

This repository contains a method to detect **Iranian vehicle license plates** as a representation of vehicle presence in an image. We have utilized **You Only Look Once version 3 (YOLO v.3)** to detect the plates inside an input image. The method has the advantages of high accuracy and real-time performance, thanks to YOLO v.3 architecture. The presented system receives a series of vehicle images and produces the processed image with added bounding-boxes containing the vehicles' license plates. The flow of how we have trained and tested the application is published in a paper accessible from the citation section.

![Sample output of the system](download._yolo_out_py.jpg "Sample Output")

## 🔨 Environment

- Python v.3
- You Only Look Once (YOLO) v.3
- A vehicle image dataset containing 3000+ samples

## 💡 How to employ?

You can download the weights file from [this](https://drive.google.com/file/d/1vXjIoRWY0aIpYfhj3TnPUGdmJoHnWaOc/ "this") link. It can also be downloaded from the weights folder (splitted files).

Test on a single image:

```
python object_detection_yolo.py --image=bird.jpg
```

Test on a single video file:

```
python object_detection_yolo.py --video=cars.mp4
```

Test on the webcam:

```
python object_detection_yolo.py
```


 

   This code is written at BigVision LLC. It is based on the OpenCV project. It is subject to the license terms in the LICENSE file found in this distribution and at http://opencv.org/license.html
