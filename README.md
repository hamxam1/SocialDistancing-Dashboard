# SocialDistancing-Dashboard

In a world recovering from the shock of COVID-19, it has become increasingly important to practice social distancing. A deep understanding of the pandemic shows how one person's negligence can cause widespread harm which will be hard to negate. So, using Computer Vision and Deep Learning might help monitor the practice of social distancing.

The application detects people who are close by and not adhering to the distancing norms and marks them in RED bounding boxes, signifying risk. Others, are in GREEN.

The Dashboard at the right, gives a visual representation of the data. The number next to the GREEN and RED icons are the number of SAFE and RISK people. Whereas, the BLACK is the total number of people in the frame.

The Pie Chart at the top just plots the SAFE vs AT RISK persons in the frame.

*** 


### Usage:


python socialDistanceDashboard.py

***

### Changes:

-The input can be a video file and needs to be updated on line number 198:

           filename = "videos/test.mp4" 

I have not included the weights as a part of the repository as it is quite big (236MB). You can download it at https://pjreddie.com/media/files/yolov3.weights and add it to the folder - "yolo-coco" as a part of the repository. I have mentioned the folder path on line number 203, and can be changed.
