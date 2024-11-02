# Yolov5s-Custom
This project is trained the yolov5s model using custom data and derived results.
For data preparation, I used the roboflow site.
The exercise was conducted in colab and the yolov5 model was imported through git clone.

## Skills
- **Pytorch**: Performing fine-tuning to improve YOLOv5s model performance using custom datasets
- **Data Preparation and Preprocessing**: Effectively preparing and labeling datasets required for training using Roboflow
- **Google Colab Usage**: Conducting model training using GPU in cloud environment
- **Git and Version Control**: Managing code and models by cloning YOLOv5 model from GitHub

## Dataset
The Roboflow dataset was used. To download the dataset, simply set the model you intend to train. The dataset structure is organized into images/labels. To build a custom dataset, you need to modify the data.yaml file to update the path, the number of classes, and the class names.

## Usage
Use bash terminal or Powershell or Command Prompt

### For training
Change the training configuration (Epochs, Batch Size, Crop Size, Upscale Factor) in the script.

python train.py

### For testing
Change the testing configuration (Upscale Factor & Trained Model path) in the script.

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
