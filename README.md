# Skin Cancer Classification using ISIC Dataset

Skin cancer is the most common human malignancy and is primarily diagnosed visually, beginning with an initial clinical screening, followed by dermoscopic analysis, and potentially a biopsy and histopathological examination. Early detection plays a crucial role in treatment and outcomes. Automated classification of skin lesions from images is a challenging task due to the fine-grained variability in the appearance of skin lesions.

This project aims to develop an automated model to classify skin lesions into two categories (benign or malignant) using deep learning techniques.

## Dataset

The dataset used in this project is taken from the **ISIC (International Skin Imaging Collaboration) Archive**, which contains a large number of images of skin lesions. For this project, the dataset includes:

- **Benign** moles: 1800 images
- **Malignant** moles: 1497 images

All images are resized to a low resolution of **224x224x3** (RGB) to make the classification task more manageable.

## Classes

The task involves classifying a skin lesion as one of the following two classes:

1. **Benign**: Non-cancerous skin moles
2. **Malignant**: Cancerous skin moles (e.g., melanoma)

## Problem Overview

The goal of this project is to create a deep learning model that can accurately classify skin lesions into **benign** or **malignant** categories based on their visual appearance. Given the fine-grained nature of the task, the model needs to handle subtle variations in the texture, color, shape, and structure of the lesions.

### Evaluation Metric

Since the dataset is **balanced** (equal number of benign and malignant lesions), the evaluation metric used to assess the model's performance is **accuracy**, which is calculated as:

![Uploading image.png…]()

