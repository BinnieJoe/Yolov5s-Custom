# Yolov5s-Custom
This project is trained the yolov5s model using custom data and derived results.
For data preparation, I used the roboflow site.
The exercise was conducted in colab and the yolov5 model was imported through git clone.

## Dataset
The Roboflow dataset was used. To download the dataset, simply set the model you intend to train. The dataset structure is organized into images/labels. To build a custom dataset, you need to modify the data.yaml file to update the path, the number of classes, and the class names.

## Required libraries

All the required libraries have been included in the requirements.txt.file.

* PyTorch (torch)
* Torchvision (torchvision)
* Numpy (numpy)
* Matplotlib (matplotlib)
* Pillow (Pillow)
* Pandas (pandas)
* OpenCV (opencv-python)

## Install the Requirements

Install the required libraries using [pip](https://pip.pypa.io/en/stable/) package manager

`pip install -r requirements.txt`
