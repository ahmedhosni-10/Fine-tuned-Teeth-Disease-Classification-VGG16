#Fine-tuned Teeth Disease Classification using VGG16 🦷
This project is AI model for classifying common teeth diseases from images. It leverages a fine-tuned VGG16 deep learning model and is deployed using Streamlit, providing an easy-to-use interface for users.

Features ✨
Image-based Classification: Upload a clear image of a tooth.

Instant Prediction: The model quickly predicts one of the following conditions:

-Cas

-Cos

-Gum

-OC

-MC

-OLP

-OT

Simple Web Interface: Built with Streamlit for a clean and interactive user experience.

Model Architecture 🔬
The core of this application is a Convolutional Neural Network (CNN) based on the VGG16 architecture.

Transfer Learning: The model uses weights pre-trained on the ImageNet dataset.

Fine-Tuning: The top layers of the VGG16 model were replaced with custom fully-connected layers and fine-tuned on a specific dataset of teeth images to adapt it for this classification task. This approach allows the model to achieve high accuracy without requiring an enormous dataset from scratch.
