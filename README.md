# 🦷 Teeth Disease Classification Web App

![App Screenshot]
(<img width="1355" height="590" alt="image" src="https://github.com/user-attachments/assets/2ad466ed-4b29-46b4-9f33-f095d1173687" />)
*<p align="center">

A user-friendly web application for classifying teeth diseases into 7 categories. This tool leverages a fine-tuned VGG16 deep learning model and is deployed using Streamlit.

---

## 📋 Table of Contents
* [About The Project](#about-the-project)
* [Features](#✨-features)
* [The Model](#🤖-the-model)
* [Technologies Used](#-technologies-used)
* [How To Use](#-how-to-use)
* [Contact](#-contact)

---

## About The Project

This project provides an intuitive web interface to classify dental diseases from tooth images. The primary goal is to offer a simple, accessible tool for preliminary dental health assessment. By uploading an image, users can get an instant prediction regarding the tooth's condition, categorized into one of seven classes.

**The 7 classification categories are:**

* **Cas**

* **Cos**

* **Gum**

* **OC**

* **MC**

* **OLP**

* **OT**

---

## ✨ Features

* **Image-Based Classification:** Upload a `.jpg`, `.jpeg`, or `.png` image of a tooth.
* **Instant Predictions:** Get a real-time diagnosis from the deep learning model.
* **Simple UI:** Clean and straightforward interface built with Streamlit.
* **Powered by VGG16:** Utilizes a powerful, pre-trained Convolutional Neural Network (CNN) for high accuracy.

---

## 🤖 The Model

This application is powered by a **Convolutional Neural Network (CNN)** built upon the renowned **VGG16** architecture.

We employed a technique called **transfer learning** to achieve high accuracy without needing to train a massive network from scratch. The process involved:

* **Pre-trained Base:** We started with the original VGG16 model, which was pre-trained on the vast **ImageNet dataset**. This provides a strong foundation for recognizing general visual features.

* **Fine-Tuning Strategy:** To adapt the model for our specific task, we froze the weights of the early convolutional layers. We then made only the final four layers trainable. This strategy allows the model to retain its powerful low-level feature detectors while recalibrating its high-level pattern recognition specifically for identifying dental diseases.

* **Model Performance**
The fine-tuned model demonstrates excellent and robust performance, achieving the following accuracy scores:

* **Training Accuracy: 96.5%**

* **Validation Accuracy: 99.71%**

* **Testing Accuracy: 99.22%**
---

## 🛠️ Technologies Used

* **Backend & Model:** Python, TensorFlow, Keras
* **Web Framework:** Streamlit
* **Core Architecture:** VGG16

---

## 🚀 How To Use

1.  **Navigate** to the deployed application URL: [https://teeth-disease-classification-vgg16-fine-tuned-app-7xfh3yt7k8ac.streamlit.app/ ]
2.  **Upload an Image:** Click on the "Browse files" button to upload an image of a tooth.
3.  **Get the Prediction:** The model will automatically process the image and display the predicted disease category along with a confidence score.

---

## 📧 Contact

Ahmed Hosni - [ahmed.fee20us@gmail.com]

Project Link: [https://github.com/ahmedhosni-10/Fine-tuned-Teeth-Disease-Classification-VGG16 ]
