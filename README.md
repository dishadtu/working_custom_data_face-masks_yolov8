# working_custom_data_yolov8

This repo explains the custom object detection training using Yolov8. 
It is perhaps the simplest example to work with also. 

So essentially I am using the default yolo weights.
Then running the Yolo on the custom data set (because the default dataset used in Yolo does not address face mask images) which generates custom weights best.pt. 

The tests took around 25mins or so to run with the GPU support.
I ran a similar test with yolov3 on my laptop and it was still running after 2 days ....

The goal is to detect a person is using mask or not and if using a mask, whether he/she is using it in wrong way. 
I am using "Face Mask Dataset" from kaggle which is already available in yolo format. https://www.kaggle.com/datasets/maalialharbi/face-mask-dataset?resource=download

I have referred https://github.com/Balakishan77/Yolov8-Custom-Object-Detetction/tree/main extensively for this. So all thanks to the person.

I have made some corrections to the file path and have also added an image to better understand the file structure that one needs to have in Google Drive.
I have also added the test file to be used (test-for-masks.mp4) and the resultant file after testing (test-for-masks(1).mp4)

[Image for Masks](https://github.com/dishadtu/working_custom_data_yolov8/blob/main/Screenshot%202023-07-26%20at%203.01.43%20PM.png)
