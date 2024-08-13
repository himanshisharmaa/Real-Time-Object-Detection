# Real-Time-Object-Detection using deep learning and OpenCV to work with video streams and video files.

* In this, Single Shot Detectors and MobileNets has been used. When combined together these methods can be used for super fast, real-time object detection .
* To load a pre-trained object detection network, dnn module is used. This will enable us to pass input images or frames through the network and obtain the output bounding box (x,y)-coordinates of each object or frames of the video.
* If we combine both the MobileNet architecture and the Single Shot Detector (SSD) framework, we arrive at a fast, efficient deep learning-based method to object detection.
* In this Caffe Version of the original Tensorflow implementation is used.
* MobileNet SSD has been trained on 20 classes that are:
  [ airplanes, bicycles, birds, boats, bottles, buses, cars, cats, chairs, cows, dining tables, dogs, horses, motorbikes, people, potted plants, sheep, sofas, trains,tv monitors]

## In order to run the "real_time_obj_detection.py" file run the following command:
    "python real_time_obj_detection.py --prototxt .\MobileNetSSD_deploy.prototxt.txt --model ./MobileNetSSD_deploy.caffemodel"
