# Face Landmarks Detection

This is a deep learning project that aims to detect facial landmarks in images using PyTorch. The model is based on the ResNet-18 architecture and is trained on the iBUG 300W Large Face Landmark Dataset.

![image](https://github.com/SubekSharma/Face_Landmarks_Detection/assets/71229363/446bb728-c8af-46e6-bf3a-adabecfd40a3)


## Table of Contents
- [Introduction](#introduction)
- [Requirements](#requirements)
- [Installation](#installation)
- [Dataset](#dataset)
- [Usage](#usage)
- [Acknowledgements](#acknowledgements)
- [License](#license)

## Introduction

Facial landmarks detection is an important task in computer vision and has various applications, including face recognition, emotion analysis, and facial expression synthesis. In this project, we use a deep learning model based on the ResNet-18 architecture to accurately predict 68 facial landmarks in an image.

## Requirements

- Python 3.x
- PyTorch
- torchvision
- NumPy
- Matplotlib
- OpenCV

## Installation

To install the required libraries, run the following command:

```bash
pip install torch torchvision numpy matplotlib opencv-python
```

## Dataset

The iBUG 300W Large Face Landmark Dataset contains images of faces along with their corresponding ground-truth facial landmarks annotations. The dataset is used for both training and testing the model.

You can download the dataset from the following link: [iBUG 300W Large Face Landmark Dataset](http://dlib.net/files/data/ibug_300W_large_face_landmark_dataset.tar.gz)

## Usage

To use the model for facial landmarks detection, you can follow these steps:

1. Clone this repository to your local machine.
2. Download the iBUG 300W Large Face Landmark Dataset and place it in the `data` directory.
3. Install the required libraries using the installation instructions above.



## Acknowledgements

I would like to thank the authors of the iBUG 300W Large Face Landmark Dataset for providing the valuable dataset for this project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
