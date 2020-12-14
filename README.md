This depository is modified from original [darknet](https://github.com/AlexeyAB/darknet). I add some functions to crop the detected objects and save them into a folder when processing video.

Usage:
./darknet detector demo cfg/coco.data cfg/yolov4.cfg weights/yolov4.weights  traffic-016.mp4 -dont_show -out trafficout.json -out_filename res.avi
