# Face-Detection-and-Training-algorithm
This is a face detection algorithm guide. So, that everyone be able to detect faces and include their own creativity.
step1:- install anaconda.

step1.1:- create a new environment.

step1.2:- enter the new environment created.

step1.3:- open anaconda prompt.

step1.4:- enter the new environment.
              #conda activate <new env_name>
  
step1.5:- pip install pillow,tkinter,opencv,pandas,numpy,tensorflow.
              (better to install them individually)
              
step1.6:- goto anaconda and install jupyter notebook and launch it.

step2:- goto the project folder.

step3:- create a notebook and create a data folder inside project folder and inside data folder create a test folder and train folder.

step4:- copy the haar cascade xml file from github and paste it on the project folder.
          	opencv/haarcascade_profileface.xml at master · opencv/opencv (github.com)



step5:- write face detection and data collection code using haar feature extractor xml file.
·        use detectMultiScale() to see the x,y,w,h coordinates of the face.
·        use these coordinates to crop collect only face of the subject, this will
         decrease errors.
·        Create a Dataset folder inside the project folder
·        There will be two folders inside Dataset folder i.e Train and Test respectively.
step6:- write an algorithm to make a model for identifying face using keras.
·        give the folder location where the sudject folders are situated.
·        train the model using upto 4 arbitary cutoff or more for better test results.
step7:- write an algorithm that will be able to detect face aswell as recognise the face using the keras model prepared on 'step6'.
