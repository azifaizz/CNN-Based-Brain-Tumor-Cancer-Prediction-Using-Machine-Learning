# 🧠 Brain Tumor Prediction Using Machine Learning
## CONTACT ME FOR DATASET REQUEST

Email: aseelfaizzin1@gmail.com

## Table of Contents
- [Project Description](#project-description)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Model Training](#model-training)
- [Installation & Usage](#installation--usage)
- [Screenshots](#screenshots)
- [Contact](#contact)
- [License](#license)

---

## Project Description
This project is an **Automated Brain Tumor Classification system** using **Deep Learning**.  
It allows users to upload an MRI scan and predicts whether a tumor is present or not.  

The main goals of the project:
- Provide **fast and accurate diagnosis** to assist doctors.
- Reduce **manual errors** and **analysis time**.
- Deploy a working **web application** for real-time predictions.

The system leverages a **Convolutional Neural Network (CNN)** trained on a dataset of over 3,000 brain MRI images. It includes advanced techniques such as image augmentation, ModelCheckpoint, and ReduceLROnPlateau callbacks to ensure **high model performance and stability**.

---

## Features
- Real-time MRI scan analysis
- Binary classification: Tumor / No Tumor
- High-Performance CNN architecture
- Robust preprocessing & data augmentation
- Web interface for easy testing
- Confidence score for predictions
- Full pipeline from training to deployment

---

## Technologies Used
- **Python** – Programming language  
- **TensorFlow & Keras** – Deep learning framework for model building  
- **NumPy & Pandas** – Data manipulation  
- **Matplotlib** – Visualization of training results  
- **ImageDataGenerator** – Real-time data augmentation  
- **Streamlit** – Web app deployment  
- **.h5** – Model file format for Keras  

---

## Dataset
The dataset contains **brain MRI scans** with tumor and non-tumor images.  

> ⚠️ **Note:** Dataset is not included due to size.  
> To get access, please send a mail to: **aseelfaizzin1@gmail.com**

---

## Model Training
- Input Images: 128x128 RGB  
- Architecture: Convolutional Neural Network (CNN)  
- Preprocessing:  
  - Rescaling (normalization)  
  - Image augmentation (rotation, zoom, flips, etc.)  
- Callbacks:  
  - `ModelCheckpoint` – saves best model  
  - `ReduceLROnPlateau` – reduces learning rate on plateau  
- Output: Binary (Tumor / No Tumor)  
- Saved Model: `BrainTumorClassifier.h5`  

---

## Installation & Usage

1. Clone the repository:

```bash
git clone https://github.com/YourUsername/BrainTumorPrediction.git
cd BrainTumorPrediction
