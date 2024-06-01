# Traffic Density Estimation Using YOLOv8
This project leverages the YOLOv8 object detection model to estimate traffic density in real-time video streams. By accurately detecting and counting vehicles within specified regions, the system provides valuable insights into traffic flow patterns and congestion levels.

## Key Features:

- Real-time Vehicle Detection: Utilizes YOLOv8's state-of-the-art object detection capabilities to identify and localize vehicles in video frames.
- Traffic Density Estimation: Counts vehicles within defined areas to assess traffic density levels.
- Traffic Intensity Classification: Classifies traffic as "Heavy" or "Smooth" based on a predefined threshold.
- Visualization: Provides visual representations of vehicle detections and traffic density estimations.
- Cross-Platform Deployment: Exportable in ONNX format for deployment on various platforms and environments.

## Project Overview:

The project involves the following steps:

- Model Selection and Assessment: Select a pre-trained YOLOv8 model and evaluate its initial performance on the COCO dataset.
- Dataset Selection: Select a specialized vehicle dataset with top-view images and annotations in YOLOv8 format.
- Model Fine-Tuning: Fine-tune the YOLOv8 model using transfer learning on the vehicle dataset.
- Model Evaluation: Analyze learning curves, confusion matrix, and performance metrics to assess model accuracy and generalization.
- Inference and Generalization: Test the model on validation images, unseen test images, and a test video.
- Real-Time Traffic Density Estimation: Implement an algorithm to count vehicles and analyze traffic intensity in real-time.
- Model Export: Export the fine-tuned model in ONNX format for cross-platform deployment.

## Results:

The fine-tuned YOLOv8 model achieved impressive results on the validation set, with high precision, recall, and mAP scores. It accurately detected and counted vehicles in real-time video streams, providing valuable insights into traffic density and intensity.

## Acknowledgements:
- Ultralytics for developing the YOLOv8 model
- Dataset: https://www.kaggle.com/datasets/farzadnekouei/top-view-vehicle-detection-image-dataset/code
