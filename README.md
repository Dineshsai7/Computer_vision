# Computer_vision_project
This project is a combination of 3 things,
1. Object detection.
2. Object Tracking.
3. Distance between the detected. Objects(Euclidian distance is calculated)
The model which we use here is YOLO which is taken from darknet which is pre-trained on 80 classes using the coco dataset.
Here we take only the Human class for object detection to detect people from the video and measure the distance between them to check whether they are practising Social-Distancing or not and when the distance is less between the subjects we can see the no. of violations happening in the video stream.
