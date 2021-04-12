# Face-Biometrics
Face Detcetion, Verification and Recognition using Python and Deep learning models 

## Face-Biometrics System

Identifying facial features from photo, video or live camera and comparing them with reference photo or set of photos to identify or authorize humans into premises or systems.



![image](https://user-images.githubusercontent.com/30498799/114339359-95243380-9b87-11eb-8f95-54d16bbec43a.png)


## STEPS:
1.	Detect the faces from the images with the help of bounding boxes.
2.	Preprocess the detected face to extract the key features.
3.	Model generates the embedding using the key features as the input.
4.	Embedding will be compared with the reference and identified or verified the person.


**Face Detection - Identify human faces in given set of images**

**Face Identification - Comparing the face in the image with all the registered faces in the database (One to Many face mapping)**

**Face Verification/Recognition - Verifying the detected face by finding a match from the registered faces in database (One to One face mapping)**



## Use Cases
1.  Attendance System
2.  Login authentication application
3.  Office security clearance
4.  Criminal Investigation
5.  Pension and Visa Verification (Especially to make sure the person is alive)

## MTCNN : Multi Task Cascaded CNN
It performs multiple tasks such as 
1.  Face classification
2.  BoudingBox regression
3.  Landmarks detection



