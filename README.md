# Banana Ripeness Classification

This project presents a comparative study of machine learning and deep learning models for banana ripeness classification based on image data.

## Problem
Accurate identification of fruit ripeness is important for retail and supply chain management. This project aims to classify bananas into three categories:
- Overripe
- Ripe
- Unripe

## Dataset
The dataset consists of 9,960 images collected over 12 days from 22 bananas captured under natural lighting conditions.

Classes are defined as:
- Stages 1–3 → Unripe
- Stages 4–6 → Ripe
- Stage 7 → Overripe

Dataset link: **[View Dataset](https://drive.google.com/drive/folders/154i5T3BSLcC-_kOYONwJSk2HDltBZY1B?usp=sharing)**

## Models Used
- Random Forest
- Convolutional Neural Network (CNN)
- EfficientNetB0
- ResNet50
- VGG16

## Results
The best performance was achieved by **ResNet50**:

- Accuracy: 0.98  
- Precision: 0.95  
- Recall: 0.97  
- F1-score: 0.96  

## Results Visualization
All key results are available in the `/results` folder:
- Confusion matrix
- Training/validation accuracy plot
- Model comparison table


## Notebooks (Run in Colab)
- Random Forest → [Open Notebook](https://colab.research.google.com/drive/1gaz34qxmNd96wUTGTwJin9259nelgUaV?usp=sharing)  
- CNN → [Open Notebook](https://colab.research.google.com/drive/1lTEJPQgtRwMNz_wdJ0-6Ggb-UOt9EcaG?usp=sharing)  
- EfficientNetB0 → [Open Notebook](https://colab.research.google.com/drive/1DdYXH6OaKLw5guQdkZcXBQ-hBwOHB_Gq?usp=sharing)  
- ResNet50 → [Open Notebook](https://colab.research.google.com/drive/1b7C5qEY0bcpK6vjh8izzwkZ0g96fcKxE?usp=sharing)  
- VGG16 → [Open Notebook](https://colab.research.google.com/drive/1jbhjfMAFgqAj7T0QKz5semlD12vw1Flm?usp=sharing)

## Academic Context
This project was developed as part of a Bachelor's thesis in Computer Engineering.

## Author
Dilbar Talantova
