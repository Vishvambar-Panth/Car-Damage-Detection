# Car Damage Detection using Deep Learning

Automated detection of car exterior damages and subsequent quantification(damage severity) of those would help used car dealers (Marketplace) to price cars accurately and fast by eliminating the manual process of damage assessment. We have developed a **CNN model from scratch** to classify the damages and their severity
## Dataset
The dataset was taken from Kaggle repository. [Link to the dataset](https://www.kaggle.com/lplenka/coco-car-damage-detection-dataset)

The dataset that we used has a collection of about 1200 images with two broad categories-**Damage**, and **Severity**.

Damaged - 2 classes with labels ‘**Damaged**’ and ‘**Whole**’.

Severity - 2 classes with labels ‘**Severe**’ and ‘**Minor**’.
## Google Colab Tutorial

Colab is a Google’s free cloud service which will let you run your deep learning or machine learning models in cloud. Add the dataset to your Drive and start coding.

### GPU Setting

Edit > Notebook settings or Runtime>Change runtime type and select GPU as Hardware accelerator

### Install Libraries

!pip install or !apt-get install

[Tensorflow](https://blog.tensorflow.org/2018/05/colab-easy-way-to-learn-and-use-tensorflow.html) tutorial
```
!pip3 install tensorflow==1.8
!pip3 install keras
```

## Code Snapshots
img src="https://github.com/Vishvambar-Panth/Car-Damage-Detection/blob/main/car.png" width="400" height="500">
