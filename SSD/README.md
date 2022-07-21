# Single Shot Multibox Detector

This is the implementation of SSD Model that we tested in partial fullfillment of the Practice School-1 course. We followed this [video](https://www.youtube.com/watch?v=RFqvTmEFtOE). This is a pre-trained model implemented using the tensorflow object detection API. Please refer to the [project report](https://docs.google.com/document/d/1AKm7zPOjAwtr8jsscsVg2aYanqtrtskpkmU1CmkV0pM/edit?usp=sharing) if you want a detailed explanation.

## Test the Code

To run the code on your system just open ```ssdimplementation.ipnyb``` file and run the notebook. 

Currently the model is taking the ```busystreet.mp4``` as input, but if you want to check for other videos then provide the path of the video in the line ```cap=cv2.VideoCapture(<Insert Path to Video>)``` in the last cell of the notebook. You can also test the algorithm live by putting ```1``` instead of the path in the above line.

### Demo

![image](https://user-images.githubusercontent.com/77738119/177012258-184c8d95-a6f9-4265-88b8-a7e911ef2b9e.png)
