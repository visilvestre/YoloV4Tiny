# YoloV4Tiny

The idea is to organize the code and be able to build YoloV4 Tiny from scratch to be modularized in docker later.

## From tutorial : https://colab.research.google.com/drive/1Z573xchN3LPslz-GtpZP8rhknJK-zyv5?usp=sharing#scrollTo=q2xRNY0gJVLa

    1) Clone darknet git repository onto the Colab VM
    2) Create yolov4-tiny and training folders in your drive
    3) Create & upload these files
        """
            What we need for training custom yolo detector
                a. Labeled Custom Dataset
                b. Custom cfg file
                c. obj.data and obj.names files
                d. process.py file (to create train.txt and test.txt files for training)
        """
        
        (a) Upload the Labeled custom dataset obj.zip file to the yolov4-tiny folder on your drive
        (b) Create your custom config file and upload it to your drive
        (c) Create your obj.data and obj.names files and upload them to your drive
        (d) Upload the process.py script file to the yolov4-tiny folder on your drive
        
    4) Mount drive and link your folder
    5) Make changes in the makefile to enable OPENCV and GPU
    6) Run make command to build darknet
    7) Copy files from your drive to the darknet directory
    8) Run the process.py python script to create the train.txt & test.txt files inside the data folder
    9) Download the pre-trained yolov4-tiny weights
    10) Training <font color="FF0000"> ( 5 Hidden Cells ) </font>
        Train your custom detector
        To restart your training (In case the training does not finish and you get disconnected)
    11) Check performance
        Check mAP (mean average precision)
    12) Test your custom detector
        Make changes to your custom config file
        Run detector on an image
        Run detector on a webcam image
        Run detector on a video
        Run detector on a live webcam
    My GitHub
        Yolov4-tiny custom training - https://github.com/techzizou/yolov4-tiny-custom_Training

    Converting Yolo to Tflite
        Start
        Float 16 Inferencing
        Float 16 Quantization
        Int 8 Quantization

    TECHZIZOU

