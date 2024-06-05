
# Skin Cancer Detection

This project aims to develop a deep learning model for classifying skin lesions at an early stage to aid in the accurate diagnosis of skin cancer and support clinical decision-making. The model is trained on the HAM10000 dataset, which consists of over 10,000 dermatoscopic images of skin lesions, along with metadata such as age, gender, and lesion type.

## Overview
Skin cancer is one of the most common types of cancer worldwide, with melanoma being a particularly severe form. Early detection of skin cancer is crucial for effective treatment and prevention of further spread. This project leverages the power of Convolutional Neural Networks (CNNs) to analyze dermatoscopic images and classify skin lesions into seven different categories: melanocytic nevi, melanoma, benign keratosis-like lesions, basal cell carcinoma, actinic keratoses, vascular lesions, and dermatofibroma.
## Methodology
The project involves the following key steps:

1. Data Preprocessing: The dataset is preprocessed, including image resizing, normalization, and data augmentation techniques to enhance the model's generalization capabilities.
2. Model Architecture: A CNN model is designed with multiple convolutional layers, max-pooling layers, and dense layers to extract features from the images and classify the skin lesions.
3. Model Training: The CNN model is trained using the augmented image data, with techniques such as early stopping and K-fold cross-validation to prevent overfitting and ensure robust performance.
4. Model Evaluation: The trained model is evaluated on a test set, and its performance is assessed using metrics such as accuracy, precision, recall, and F1-score. A confusion matrix is also generated to analyze the model's misclassifications.
## Results
The CNN model achieved an impressive overall accuracy of 97.91% in classifying skin lesions, demonstrating the effectiveness of deep learning techniques in medical image analysis. The model's performance is further validated through detailed evaluation metrics and visualization of the training process.
## References
1.	https://www.kaggle.com/code/ashutoshvarma/image-classification-using-svm-92-accuracy/notebook 

2.	https://www.nature.com/articles/sdata2018161

3.	https://www.kaggle.com/code/hozifanasef/ham10000-cnn-skin-cancer-type-detection 

4.	https://github.com/mkowalsky97/Skin_Cancer_Detection/blob/main/Main.ipynb 
