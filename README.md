# American-Sign-Language-Detection-and-Recognition
This project was done for my 7th semester minor project.
This project aims to achieve American Sign Language Detection using CNN based human computer interface. It also has feature like real time webcam detection.

### Dataset Used

The dataset used in this project are all collected by self. Also there are many datasets available in Kaggle.

### Specific Packages

* opencv-python~=4.7.0.68
* cvzone~=1.5.6
* mediapipe~=0.9.1.0
* Be sure to install python version 3.10 as mediapipe isnt supported in the latest versions.

### Data Collection
* First create a folder names 'Data' and sub folders having name 'A' , 'B',.....'Z' so that the data can be stored in their respective folder.
* Once created run collect.ipynb in vscode/Pycharm and press the alphabet that data you want to collect. Example, if you are showing symbol of 'A' press A and it will store inside A.

### Data Training
Then training can be done in two ways:
* 1st way is by using https://teachablemachine.withgoogle.com/train/image
* 2nd way is by LSTM algorithm in train.ipynb file

Now create a folder named 'Model'.
* Then after training place the file inside Model Folder.

Now run the program through main.py
  `python main.py`
