
Driver Behavior Detection using CNNs

Overview
Driver Behavior Detection using CNNs is a project aimed at classifying driver behavior from video footage using deep learning techniques, specifically Convolutional Neural Networks (CNNs). The project focuses on processing video frames captured from in-car cameras to identify behaviors such as distracted driving, lane departure, and aggressive driving.

Features
Data Collection: Video footage collection from in-car cameras or simulation environments.
Data Preprocessing: Frame extraction, resizing, and normalization for CNN input.
CNN Architecture: Implementing CNN architectures (e.g., ResNet, VGG) for behavior classification.
Training: Training CNN models on labeled video datasets.
Real-time Detection: Implementing real-time driver behavior detection using trained CNN models.

Usage
Data Collection: Set up in-car cameras or utilize simulation environments to capture driving footage.
Preprocessing: Extract frames from videos, resize them to fit CNN input requirements, and normalize pixel values.
Model Training: Train CNN models on the prepared dataset using train.py.
Real-time Detection: Implement real-time driver behavior detection using live video feeds with realtime_detection.py.
Contributing
Contributions are welcome! Please follow these steps to contribute to the project:

Fork the repository.
Create a new branch (git checkout -b feature/yourfeature).
Make your changes.
Commit your changes (git commit -am 'Add new feature').
Push to the branch (git push origin feature/yourfeature).
Create a new Pull Request.
