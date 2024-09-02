# Helmet Detection using YOLO

## Project Description

The Bike Helmet Detection project leverages the power of YOLO (You Only Look Once), a state-of-the-art object detection algorithm built on Convolutional Neural Networks (CNNs), to identify whether a person is wearing a helmet while riding a bike. By processing images in real-time, the system efficiently detects and classifies the presence of helmets, ensuring safety compliance and enhancing road safety.

## Technologies Used

- **cv2**: OpenCV library for computer vision tasks
- **cvzone**: A library that simplifies the integration of OpenCV and YOLO
- **math**: Mathematical functions and utilities
- **YOLO**: Object detection algorithm for real-time processing
- **ultralytics**: YOLO implementation library

## Dataset Information
## Download the dataset from drive and upload it on your drive the use google colab for opening the .ipynb file because colab gives support of GPU for training that is faster than CPU training so use colab.
The dataset used for this project consists of images categorized into:

- **Training**: Contains images and labels for training the model
- **Validation**: Contains images and labels for validating the model during training
- **Testing**: Contains images and labels for evaluating the model's performance

Each of these folders is further divided into two subfolders:

- **Images**: Raw image data
- **Labels**: Annotation files with object information

## Results

The model is capable of making predictions by processing both images and videos as input. It detects and classifies the presence of helmets, providing real-time feedback on helmet usage.

## Acknowledgments

- **YOLO and Ultralytics**: Thanks to the developers and contributors of YOLO and the Ultralytics library for providing a powerful framework for object detection.
- **OpenCV and cvzone**: Appreciation for the libraries that facilitate image processing and integration with YOLO.
- **Community Support**: Gratitude to the open-source community and resources that assisted in developing and refining the model.

