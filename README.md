# detecting-iligal-u-turn-using-yolov8
We will use yolov8 to develop a machine learning technology that automatically detects illegal stopping vehicles that stop for more than 5 minutes and illegal U-turn vehicles that cross the solid yellow line. In case noise occurs in the cctv image, a large amount of learning materials were used and several yolo versions were used toimprovethespeed.

#we used google colab for machine learning. and get a images and videos via MScoco and cctv videos from korea police website. 
than for detect lines we used HSV, Canny Edge detection, HoughLine 
this three method neccesery for detect line. and after that cheking moving methrial use use 
yolov8 and opencv together. (might opencv could deleted in the final version)

normal cars making bbox with a green line and iligal cars shine with a red bbox. 
yellow bbox showing us when cars stop state with a yellow line more than 5min. 


