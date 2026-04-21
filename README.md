# Phase3_day16

Tasks Completed

1. Model Export & Loading

The trained model was saved and prepared for deployment.
Steps:
Saved trained model in .h5 / .pth format
Created a model loading function
Ensured preprocessing pipeline matches training pipeline
This ensures consistent predictions during inference.

2. Streamlit App Interface Design

The user interface was created with:
Title and project description
Image upload feature
Predict button
Display of prediction result and confidence score

This makes the project interactive and user-friendly.

3. Image Preprocessing Pipeline

Implemented preprocessing steps:

Image resizing
Normalization
Batch dimension addition

These steps ensure the uploaded image is compatible with the model.

4. Real-Time Prediction Pipeline

Integrated model prediction with the UI:

Load uploaded image
Preprocess input
Run model inference
Display predicted class and confidence

The application successfully performs real-time predictions.
