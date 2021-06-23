# Hand detection with tensorflow object detection api
## Introduction
- Hand detection system that detects human hands and tracks the distance between
hands and safety line. and when hands cross the safety line it will generate an alert alarm and stop shredder machine.
- It will help to prevent an accident in the shredder machine So that the laborers do not lose their hands.
## for data gathering
- I have gathered data from Kaggle and some of my own dataset.
## for data annotation
- I have used `LabelImg` image annotation tool.
## model training
- I have trained tensorflow object detection model `ssdlite_mobilenet_v2`.
### project demo:

![Hnet-image (4)](https://user-images.githubusercontent.com/47352327/100866953-48e51c00-344e-11eb-8bbc-4e97f1b09059.gif)
