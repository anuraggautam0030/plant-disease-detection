# 🌱 AI-Based Plant Disease Detection & Recommendation System

An AI-based system for detecting plant diseases from leaf images using Deep Learning and Convolutional Neural Networks (CNNs).

The project is designed as an end-to-end AI application where a user can upload a plant leaf image, receive a disease prediction, view the confidence score, and get relevant prevention and treatment recommendations.

---

## 📌 Project Overview

Plant diseases can reduce crop quality and yield if they are not identified early.

This project aims to build a simple AI-based solution that helps identify plant diseases from leaf images using computer vision and deep learning.

The system is being developed to perform the following tasks:

- Accept a plant leaf image as input
- Preprocess the image before prediction
- Identify whether the leaf is healthy or diseased
- Classify the specific plant disease
- Display the predicted class
- Show model confidence
- Provide prevention recommendations
- Provide treatment recommendations
- Present the result through a web-based interface

---

## 🎯 Project Objective

The main objective of this project is to develop an end-to-end deep learning application for plant disease classification.

The project combines:

- Image processing
- Deep learning
- Convolutional Neural Networks
- Multi-class image classification
- Model evaluation
- Web application development

The goal is not only to build a classification model, but also to create a usable application around the model.

---

## 🧠 Deep Learning Approach

The core model is based on a Convolutional Neural Network (CNN).

CNNs are suitable for image classification because they can automatically learn visual features such as:

- Leaf texture
- Color variations
- Spots and lesions
- Shape patterns
- Disease-related visual symptoms

The model processes plant leaf images and predicts the most likely disease class.

The current CNN architecture is being developed using multiple convolutional blocks with increasing feature depth.

The model pipeline includes:

- Image resizing
- Pixel normalization
- Dataset splitting
- CNN feature extraction
- Global Average Pooling
- Dense classification layers
- Multi-class output prediction

---

## 📊 Dataset

The project uses the **PlantVillage dataset**.

The dataset contains plant leaf images across multiple crop species and disease categories.

The current dataset setup contains approximately:

- **38 classes**
- Healthy and diseased leaf categories
- Multiple crop species
- Color leaf images

The dataset is being used for:

- Training
- Validation
- Testing
- Model evaluation

Dataset files are not included in this public repository.

---

## ⚙️ Project Workflow

**Leaf Image → Image Preprocessing → CNN Model → Disease Classification → Confidence Score → Treatment & Prevention Recommendations → Flask Web Application**

### Workflow Breakdown

1. The user uploads a plant leaf image.
2. The image is resized to the model input size.
3. Pixel values are normalized.
4. The trained CNN processes the image.
5. The model predicts the most likely class.
6. A confidence score is calculated.
7. The predicted disease information is retrieved.
8. Prevention and treatment recommendations are displayed.
9. The result is shown through the web application.

---

## ✨ Main Features

- Plant leaf image upload
- Deep learning-based disease classification
- Multi-class prediction
- Confidence score display
- Healthy vs diseased identification
- Disease-specific recommendations
- Prevention suggestions
- Treatment information
- Simple Flask-based web interface
- Structured prediction pipeline

---

## 🛠️ Technologies Used

### Programming

- Python
- HTML
- CSS
- JavaScript

### Deep Learning & Machine Learning

- TensorFlow
- Keras
- Convolutional Neural Networks
- scikit-learn

### Data & Image Processing

- NumPy
- Pillow
- Matplotlib

### Web Development

- Flask

### Development Tools

- VS Code
- Python Virtual Environment
- Git
- GitHub

---

## 🧩 Project Architecture

The project is being structured into separate components for:

- Dataset handling
- Image preprocessing
- Model creation
- Model training
- Model evaluation
- Prediction
- Recommendation mapping
- Flask web application
- Frontend interface

This helps keep the project modular and easier to maintain.

---

## 📈 Model Development

The model development process includes:

- Loading image data
- Preparing class labels
- Creating training, validation, and testing sets
- Building a CNN model
- Training the model
- Monitoring validation performance
- Saving the trained model
- Evaluating predictions
- Integrating the model into the web application

The model architecture and training process are still being refined.

---

## 🌐 Web Application

A Flask-based web application is being developed for the project.

The planned interface allows users to:

- Upload a plant leaf image
- View the predicted disease
- View prediction confidence
- Check whether the leaf is healthy or diseased
- Read prevention recommendations
- Read treatment recommendations

The web application is intended to make the trained model easier to use without requiring direct interaction with Python code.

---

## 🚧 Current Project Status

**Status: In Development**

Completed or actively developed components include:

- Project structure
- Dataset inspection
- Dataset organization
- Train/validation/test splitting
- Image preprocessing pipeline
- CNN architecture
- Model training setup
- Class mapping
- Flask application structure
- Disease recommendation system

Further model training, evaluation, testing, and interface improvements are ongoing.

---

## 🔮 Planned Improvements

Future improvements may include:

- Improving model accuracy
- Comparing multiple CNN architectures
- Transfer learning
- Better model evaluation
- Confusion matrix analysis
- Improved user interface
- Better disease descriptions
- Expanded treatment recommendations
- Mobile-friendly web design
- Cloud deployment
- API-based prediction support

---

## 🔐 Source Code

The source code, training scripts, model files, configuration files, and development resources are maintained in a **private repository**.

This public repository is currently intended as a project overview and documentation page.

The source code may be made public later after the project is completed and cleaned for release.

---

## 👨‍💻 Developer

**Anurag Gautam**

B.Tech CSE (AI & ML)  
Central University of Karnataka

LinkedIn:  
[linkedin.com/in/anuraggautam0030](https://linkedin.com/in/anuraggautam0030)

---

## 📌 Project Type

Academic / Personal AI Project

**Focus Areas:**  
Artificial Intelligence · Deep Learning · Computer Vision · CNN · Flask · Image Classification
