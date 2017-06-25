# Traffic-Sign-Classifier
> Please refer to: Self-Driving Car Engineer Nanodegree - Udacity, [Term 1 - Project 2](https://github.com/udacity/CarND-Traffic-Sign-Classifier-Project)

[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)


### Overview
This project uses a deep convolutional neural networks to classify traffic signs. 
The CNN model takes as input the [German Traffic Sign Dataset](http://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset) and understands road signs from images. The [notebook](Traffic_Sign_Classifier.ipynb) shows the code as well full results.   

### Dependencies
The code is stored in a [Jupyter Notebook](http://jupyter.org/) and requires **Python 3.5**. Please refer to the [project website](https://github.com/udacity/CarND-Traffic-Sign-Classifier-Project) for implementation details. 

### Preprocessing
The project pipeline includes functions to transform poor color in high contrast grey images.  
E.g.:
_No passing_
<img src="traffic-signs-pre-processing/NoPassing.png" width="480" alt="Combined Image" />

_Speed limit_
<img src="traffic-signs-pre-processing/SpeedLimit.png" width="480" alt="Combined Image" />

### Result
At the end, I obtain the following results:
* train set accuracy: near 100%  
* the validation set accuracy: 94%  
* the test accuracy: 85%
