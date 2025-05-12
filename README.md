A Federated Learning-Based Deep Learning Model for Multiclass Lung Image Classification

This project leverages federated learning to implement a privacy-preserving, decentralized deep learning model for the multiclass classification of lung images. Using ResNet-101 and Vision Transformer (ViT) as backbones, the model classifies medical images into categories such as COVID-19, pneumonia, hernia, infiltration, cardiomegaly, and other lung conditions — totaling 15 distinct classes — while ensuring that sensitive medical data remains securely distributed across multiple devices or institutions.

Key Features: Federated Learning Framework: Enables decentralized training, where data stays on local devices, ensuring privacy.
              Dual Backbone Support – ResNet-101 & Vision Transformer (ViT):
              ResNet-101: Pretrained on ImageNet, fine-tuned for robust feature extraction.
              ViT: Leverages attention mechanisms for global context understanding and improved performance on high-resolution medical images.

Loss Function: Utilizes CrossEntropyLoss with class weights to handle class imbalance effectively.

Input Data: Processes RGB lung images with data augmentation to improve generalization and prevent overfitting.

Performance Metrics: Evaluates the model using accuracy, precision, recall, and F1-score, specifically tailored for multiclass classification tasks.

Optimization Strategies: Implements federated optimization techniques, learning rate scheduling, and weight decay, dropout for efficient and robust training.

Web Application Integration (Using Flask):
Deploys the trained model into a user-friendly web interface built with Flask, a lightweight and efficient Python web framework.
Allows users (e.g., clinicians or researchers) to upload lung images for real-time prediction and visualization of results.
Provides backend support for federated updates, making it easy to integrate local predictions and model training components if needed.

Objectives: The primary goal of this project is to develop a privacy-preserving and collaborative solution for lung condition detection using medical imaging. By utilizing federated learning, institutions can collaboratively train a robust model without sharing sensitive patient data, promoting data security and accessibility.
