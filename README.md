This depository is modified from original [darknet](https://github.com/AlexeyAB/darknet). I add some functions to crop the detected objects and save them into a folder when processing video.

Environment:
opencv 3.4: https://zhuanlan.zhihu.com/p/276010938

Usage:

./darknet detector demo cfg/coco.data cfg/yolov4.cfg weights/yolov4.weights  traffic-016.mp4 -dont_show -out trafficout.json -out_filename res.avi


You can also use the command below:

./darknet detector demo cfg/coco.data cfg/yolov4.cfg weights/yolov4.weights  traffic-016.mp4 -dont_show -i 3

-i 3 is to specify gpu.


The results will be saved into the folder traffic-016 (which is the prefix of the traffic-016.mp4)
