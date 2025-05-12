A Federated Learning-Based Deep Learning Model for Multiclass Lung Image Classification
This project leverages federated learning to implement a privacy-preserving, decentralized deep learning model for the multiclass classification of lung images. Using ResNet-101 and Vision Transformer (ViT) as backbones, the model classifies medical images into categories such as COVID-19, pneumonia, hernia, infiltration, cardiomegaly, and other lung conditions — totaling 15 distinct classes — while ensuring that sensitive medical data remains securely distributed across multiple devices or institutions.

Key Features:
Federated Learning Framework: Enables decentralized training where data remains on local devices, preserving patient privacy and adhering to data protection regulations.

Dual Backbone Support – ResNet-101 & Vision Transformer (ViT):

ResNet-101: Pretrained on ImageNet, fine-tuned for robust feature extraction.

ViT: Leverages attention mechanisms for global context understanding and improved performance on high-resolution medical images.

Loss Function: Uses CrossEntropyLoss with class weights to handle severe class imbalance effectively.

Input Data: Accepts RGB lung images and applies comprehensive data augmentation (e.g., rotation, scaling, flipping) to boost model generalization and minimize overfitting.

Performance Metrics: Evaluates using accuracy, precision, recall, and F1-score, specifically designed for multiclass classification tasks in medical imaging.

Optimization Strategies:

Implements federated optimization algorithms (e.g., FedAvg).

Uses learning rate scheduling, weight decay, and dropout for robust and efficient training.

Web Application Integration:

Deploys the trained model into a user-friendly web interface.

Allows uploading of lung images for real-time prediction and visualization.

Supports graphical display of predictions and explanation maps (e.g., Grad-CAM or attention visualization).

Ensures secure, scalable access for clinics and researchers.

Objectives:
The primary objective is to build a collaborative, privacy-respecting AI solution for lung disease diagnosis through medical imaging. By combining federated learning, advanced deep learning architectures, and interactive web deployment, this project promotes data security, clinical applicability, and scalable diagnostic support without compromising patient confidentiality.
