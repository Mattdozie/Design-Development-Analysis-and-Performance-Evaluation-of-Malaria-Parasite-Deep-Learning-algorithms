# Table of Contents

- [Overview](#overview)
- [Motivation](#motivation)
- [Technical Aspect](#technical-aspect)
- [Installation](#installation)
- [Technologies Used](#technologies-used)
- [Model Evaluation](#model-evaluation)
- [Report](#report)
- [Credits](#credits)

## Overview
Malaria, a deadly parasitic infection, poses a significant global health threat, causing over 400,000 deaths and 200 million infections annually. Despite extensive investments in new tools, many national malaria programs lack access to these resources. The burden of malaria persists due to emerging resistance to common treatments and urbanization trends. Accurate diagnosis remains a primary challenge, typically relying on examining blood samples for parasites. This project highlights the importance of fast and accurate diagnostics in malaria control strategies. Utilizing Convolutional Neural Networks (CNNs), particularly in the form of deep learning models, offers a promising solution. The study evaluates the design, development, and performance of CNN models compared to other pre-trained models like Xception, VGG19, and ResNet50 for classifying malaria-infected blood samples. By leveraging advanced technologies like CNNs, this project aims to improve malaria diagnosis and contribute to effective control strategies.

## Motivation
As an individual from a country with high malaria-associated deaths, the motivation for this project is driven by the urgent need to reduce global mortality rates. By leveraging advanced technology like Convolutional Neural Networks, I aim to enhance diagnostic accuracy and contribute to effective malaria management, ultimately saving lives worldwide.

## Technical Aspect
### Data Collection and Processing:
For this project, a dataset comprising 27,560 cell images in PNG format was gathered from Kaggle, evenly split between parasitized and uninfected samples. These images were originally captured using a Malaria screener smartphone app developed by researchers at the Lister Hill National Centre for Biomedical Communication in collaboration with NIH's National Institute of Allergy and Infectious Diseases and Mahidol-Oxford University.

### Data Preprocessing:
The images were uploaded and processed by resizing them to 200x200 pixels and labelled accordingly (parasitized = 0, uninfected = 1). This preprocessing facilitated standardized image sizes for efficient model learning. The dataset was then divided into training and test sets in a 7:3 ratio, ensuring adequate data for model training and evaluation.

## Installation
<div>
<img src="https://img.shields.io/badge/-TensorFlow-FF6F00?&style=for-the-badge&logo=TensorFlow&logoColor=white" />
<img src="https://img.shields.io/badge/-Keras-D00000?&style=for-the-badge&logo=Keras&logoColor=white" />
<img src="https://img.shields.io/badge/-Seaborn-388E3C?&style=for-the-badge&logo=Seaborn&logoColor=white" />
<img src="https://img.shields.io/badge/-Matplotlib-377EB8?&style=for-the-badge&logo=Python&logoColor=white" />
<img src="https://img.shields.io/badge/-NumPy-013243?&style=for-the-badge&logo=NumPy&logoColor=white" />
<img src="https://img.shields.io/badge/-Pandas-150458?&style=for-the-badge&logo=Pandas&logoColor=white" />
<img src="https://img.shields.io/badge/-OpenCV-5C3EE8?&style=for-the-badge&logo=OpenCV&logoColor=white" />
<img src="https://img.shields.io/badge/-PIL-659AD2?&style=for-the-badge&logo=PIL&logoColor=white" />
<img src="https://img.shields.io/badge/-scikit_learn-F7931E?&style=for-the-badge&logo=scikit-learn&logoColor=white" />
</div>

## Technologies Used
- Custom CNN Model
- Pre-trained Models (Xception, VGG19, ResNet50)

## Model Evaluation
This project endeavors to construct a robust deep learning framework for precise classification of malaria cell images. Four Convolutional Neural Network (CNN) models were developed for this purpose, with the initial model being custom-built, while the subsequent models utilized pre-trained architectures. Evaluation of performance metrics across these models is conducted to ascertain the optimal approach for achieving the project's objectives.
![image](https://github.com/Mattdozie/Design-Development-Analysis-and-Performance-Evaluation-of-Malaria-Parasite-Deep-Learning-algorithms/assets/100968289/3e8b9260-9682-4e57-9490-11b619b6e700)

## Report
The final report for the project can be viewed (<a href="Malaria Detection Deep Learning Models.pdf">[HERE]</a>#)

## Credits
