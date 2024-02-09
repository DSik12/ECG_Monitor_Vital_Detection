# ECG_Monitor_Vital_Detection

## Overview

This project focuses on extracting vital information from Electrocardiogram (ECG) monitor images using various computer vision and machine learning techniques. The goal is to develop a system capable of automatically extracting vital signs, such as heart rate, from ECG monitor images, facilitating medical analysis and diagnosis.

## Features

- **YOLO Training & Prediction**: Train YOLO (You Only Look Once) model on annotated ECG monitor dataset for object detection and obtain predictions on all images.

- **Annotate and Augment Data**: Annotate and augment data using tools like Roboflow to improve model training and performance.

- **Cropping with Bounding Box**: Identify and crop regions of interest within the ECG monitor images based on high-probability bounding boxes.

- **Edge Detection & Boundary Detection**: Apply edge detection techniques to identify wave edges and boundaries within the ECG monitor images.

- **Image Transformation**: Transform images from report format to ECG monitor format using rule-based cropping, background removal, and conversion to black and white.

- **Data Augmentation Pipeline**: Create a pipeline for data augmentation including rotation and cropping to diversify the dataset.

- **CNN Model Training**: Train a Convolutional Neural Network (CNN) model with specified hyperparameters for normal vs. abnormal classification.

- **Segmentation and Contour Detection**: Utilize segmentation models to extract and monitor regions of interest within the ECG monitor images.

- **Optical Character Recognition (OCR)**: Employ OCR technology to extract textual information such as vital signs from defined regions within the ECG monitor images.

- **PDF Report Generation**: Generate formatted PDF reports containing medical insights extracted from the analyzed ECG monitor images.

