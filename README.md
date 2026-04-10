# Pneumonia Detection using CNN

**Problem Descriptio**n

This project focuses on detecting pneumonia from chest X-ray images using a Convolutional Neural Network (CNN). The dataset contains pediatric chest X-rays categorized into Pneumonia and Normal classes.

**Dataset**

 - Total Images: 5,863
 - Categories:
    - Pneumonia
    - Normal
 - Split into:
    - Training
    - Validation
    - Testing

**Methodology**

*Preprocessing*

 - Images resized to 150×150
 - Pixel values normalized (0–1)

*Model Architecture*

 - 3 Convolution layers
 - MaxPooling layers
 - Fully connected Dense layers
 - Dropout for regularization
 - Sigmoid activation for binary output

**Results**

 - The CNN model learns spatial features from X-rays
 - Achieves good accuracy on validation and test data
 - Helps automate pneumonia detection
