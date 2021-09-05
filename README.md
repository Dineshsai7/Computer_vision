# Computer_vision_project
YOLO (You Only Look Once) is an algorithm for detecting objects. The object detection consists of determining the position on the image, as well as classifying those objects. The previous methods, such as the R-CNN, Fast-RCNN, Faster-RCNN others, are slow and difficult to optimize because each component must be trained separately.



This project is a combination of 3 things,

1. Object detection.

2. Object Tracking.

3. Distance between the detected. Objects(Euclidian distance is calculated)

The model which we use here is YOLO  which can detect over 9000 classes, but here i'am using the coco dataset.

Here we take only the Human class for object detection transfer learning process to detect person class from the video and measure the distance between them to check whether they are practicing Social-Distancing or not and when the distance is less between the subjects we can see the no. of violations happening in the video stream.
