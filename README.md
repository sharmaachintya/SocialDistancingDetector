# SocialDistancingDetector

NOTE: I'VE NOT UPLOADED THE YOLOV3.WEIGHTS WEIGHT FILE AS IT IS BIGGER THAN 100 MB BUT HERE'S THE LINK SO THAT YOU CAN DOWNLOAD IT : https://pjreddie.com/darknet/yolo/

In this code I've implemented Social Distancing Detection in real time with the help of yolo-coco model.
First it will capture the frames from the camera, then it will detect the number of humans in the present frames and as soon as the number of humans gets more than 1, It will start calculating the distance between them. As soon as the distance between two humans gets lesser than the defined one the rectanges made on both human beings with the help of tracking turns their colour from green to red and the text changes from Normal to Red alert.
