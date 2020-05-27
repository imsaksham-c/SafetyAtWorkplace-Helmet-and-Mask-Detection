# DetectingMask-Helmet-SafetyAtWorkplace
Creating an AI engine that is capable of predicting whether a person is wearing a face mask and a safety helmet at work place like construction sites, labs etc.

## Implementation-
# Framework - PyTorch, YOLOv3
I have divided the problem in 2 different problems
1. Detecting Helmet
2. Detecting Mask

### 1. Helmet Detection
In this problem I have used YOLOv3 for training my custom object(Helmet) detection. I have trained YOLO model from scratch which detects Helmet in an image with very accuracy. 
For more information about training & installation open helmet-detection folder.

Dataset - https://storage.googleapis.com/openimages/web/visualizer/index.html?set=train&type=detection&c=%2Fm%2F0zvk5

### Mask Detection
In this problem I have used classification technique to differenciate/classify between face with mask or face without mask images. I have trained MobileNetV2 using Transfer learning for this problem. The accuracy achieved for training set is 98% and for validation 95%.

Dataset - I have used a small dataset for thsi problem, and the dataset is included in the mask-detection folder.

For more info go to mask-detection folder.

### For more information about the training & accuracy go to respective folders -
### 1. For Helmet Detection Problem - go to helmet-detection folder
### 2. for Mask Detection Problem - go to mask-detection folder

For the final task, I have combined both the model in a single file - 
For visualizing the final result open final_predicy.ipynb file.

### Some Sample Results - 
![Image1](https://github.com/imsaksham-c/DetectingMask-Helmet-SafetyAtWorkplace/blob/master/test_result/1.png)
![Image2](https://github.com/imsaksham-c/DetectingMask-Helmet-SafetyAtWorkplace/blob/master/test_result/2.png)
![Image3](https://github.com/imsaksham-c/DetectingMask-Helmet-SafetyAtWorkplace/blob/master/test_result/3.png)
![Image4](https://github.com/imsaksham-c/DetectingMask-Helmet-SafetyAtWorkplace/blob/master/test_result/4.png)
