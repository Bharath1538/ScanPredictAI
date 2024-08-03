ScanPredictAI: AI-Powered Disease Detection
Welcome to ScanPredictAI! This project is designed to provide accurate disease detection from CT scan images using advanced AI models. This repository contains the code for a web application built with Streamlit that allows users to upload medical images and receive predictions on possible diseases.

Table of Contents
Introduction
Features
Installation
Usage
Models
License
Introduction
ScanPredict leverages deep learning models to classify medical images into various disease categories. The current implementation supports predictions for brain tumors, breast ultrasound anomalies, and lung cancer.

Features
Brain Tumor MRI Classification: Predicts glioma, meningioma, pituitary tumors, or no tumor.
Breast Ultrasound Classification: Detects benign, malignant, or normal conditions.
Lung Cancer Detection: Classifies images as squamous cell carcinoma, large cell carcinoma, adenocarcinoma, malignant cases, benign cases, or normal.
Installation
Follow these steps to set up the project locally:

Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/ScanPredict.git
cd ScanPredict
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Download the pretrained models and place them in the appropriate directory.

Usage
To run the application, execute the following command:

bash
Copy code
streamlit run app.py
Upload a medical image through the web interface, select the appropriate model, and get instant predictions along with confidence levels.

Models
This project includes three models for different types of medical image classifications:

Brain Tumor MRI: Detects different types of brain tumors.
Breast Ultrasound: Classifies ultrasound images for breast cancer detection.
Lung Cancer: Identifies different types of lung cancer.
Ensure you have the models downloaded and placed correctly in the project directory:

Brain Tumor MRI: Brain Tumor MRI Dataset/Trained model/glioma_model.pth
Breast Ultrasound: best_model.pth
Lung Cancer: Trained model/trained_model.pth
License
This project is licensed under the MIT License. See the LICENSE file for details.
