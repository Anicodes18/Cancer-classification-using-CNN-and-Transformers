Link to the dataset which is available on Kaggle:

[Cancer Image dataset](https://www.kaggle.com/datasets/aniketranecodes/cancer-image-dataset)



In order to run the code file, an anaconda environment needs to be setup with all the required libraries and python packages along with the dependencies. For doing this, an environment creation file named cancer-classification.yml containing all the required packages has been provided.

Before running the command for environment creation ensure that the working directory for anaconda is set to the folder location in which you have placed the cancer-classification.yml file.



Just simply run the following commands given below in anaconda prompt:

conda env create-f cancer-classification.yml



After creating the environment, activate it using the command given below:

conda activate cancer-classification


# Cancer Classification using CNNs and Vision Transformers

## Overview

This project focuses on the classification of histopathological cancer images using deep learning techniques, specifically Convolutional Neural Networks (CNNs) and Vision Transformers (ViTs). The aim of the project is to accurately identify and classify cancerous tissue patterns from medical imaging data while exploring advanced deep learning methodologies to improve model generalization and performance.

The project was developed as part of my MSc in Data Analytics thesis at the National College of Ireland.

---

## Objectives

- Develop deep learning models for medical image classification
- Compare the performance of CNNs and Vision Transformers
- Explore transfer learning and few-shot learning techniques
- Evaluate embedding representations and image variability
- Monitor and optimize model training performance
- Improve model generalization on unseen medical imaging data

---

## Technologies Used

- Python
- PyTorch
- FastAI
- TensorBoard
- Scikit-learn
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook

---

## Project Structure

```text
Cancer-classification-using-CNN-and-Transformers/
│
├── notebook/               # Jupyter notebooks
├── images/                 # Project screenshots and outputs
├── models/                 # Model-related files
├── runs/                   # TensorBoard logs
├── .gitignore
├── requirements.txt
└── README.md

