Anti-Drone Surveillance System Using YOLOv7
Description
This repository contains the code and resources for an Anti-Drone Surveillance System developed using the YOLOv7 model. The system is designed to detect and classify airborne objects, particularly drones, in real-time. Leveraging a custom dataset of 20,000 images, the model was trained and fine-tuned to achieve a high accuracy of 93%, making it highly effective for surveillance and security applications.

Features
Real-Time Drone Detection: The system can process video streams and images in real-time to identify drones and other airborne objects with high precision.
Custom YOLOv7 Model: Built on the YOLOv7 architecture, the model has been customized and trained on a large dataset specifically curated for drone detection.
High Accuracy: Achieved an accuracy of 93% with strong performance metrics across precision, recall, and F1 score.
Scalable and Flexible: The project is designed to be easily scalable, with scripts and notebooks for training, validation, and inference.
Dataset
The dataset consists of 20,000 labeled images with various classes representing different types of drones and other airborne objects. The images were split into training and validation sets, with annotations in YOLO format.

Training and Inference
The model was trained using PyTorch with YOLOv7 on a multi-GPU setup. The repository includes all the necessary scripts and notebooks to:

Train the model from scratch or fine-tune with transfer learning.
Validate the model on the test set.
Run inference on new images or video streams.
Results
After extensive training, the model demonstrated strong performance:

Accuracy: 93%
Precision: 0.92
Recall: 0.94
F1 Score: 0.93
Inference Time: 15ms per image on average
Installation
To get started, clone the repository and install the required dependencies listed in requirements.txt. Detailed instructions for setting up the environment, training the model, and running inference are provided in the documentation.

Usage
Training: Use train.py to start training the model on your dataset.
Inference: Run detect.py to perform real-time detection on new images or video streams.
Contributions
Contributions to improve the system are welcome. Please submit a pull request or open an issue to discuss potential changes.

License
This project is licensed under the MIT License.
