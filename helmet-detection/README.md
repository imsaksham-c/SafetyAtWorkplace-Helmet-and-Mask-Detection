# Helmet Detection

In this projct I have created and trained an AI model to automate the monitoring of whether people are wearing hardhat/helmet on construction site, labs, roads(2 wheelers), etc.

## Steps - 
1. Data Collection
2. Data Pre-Processing wrt YOLO
3. Train YOLOv3
4. Obtain weights & cfg file
5. Test the Model

## Dataset - 
https://drive.google.com/drive/folders/12WtXQyM-7jWvWPtCXZlnycsIK72ClHgu
Download the dataset along with the annotation file (as req.)

## Training YOLOv3
For training custom YOLO please follow the [Darknet](https://github.com/AlexeyAB/darknet) procedure.

## Trained Model File
https://drive.google.com/drive/folders/1LK8v6VrBXLYUIVgmB__xxoVM1HiQfkEz?usp=sharing
Download the model file and place it in the model folder in helmet-detection folder

## Testing the Model
For testing, I have created an intractive notebook with all the details and results displayed.
Please open Predict.ipynb

Enjoy :)

## Here are some test results
![Image1](https://github.com/imsaksham-c/SafetyAtWorkplace-Helmet-and-Mask-Detection/blob/master/helmet-detection/test-result/1.png)
![Image2](https://github.com/imsaksham-c/SafetyAtWorkplace-Helmet-and-Mask-Detection/blob/master/helmet-detection/test-result/2.png)
![Image3](https://github.com/imsaksham-c/SafetyAtWorkplace-Helmet-and-Mask-Detection/blob/master/helmet-detection/test-result/3.png)
