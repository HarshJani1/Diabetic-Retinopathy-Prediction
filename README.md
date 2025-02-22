# Diabetic-Retinopathy-Prediction
# About
Diabetic retinopathy (DR) is an eye condition that damages the retina due to high blood sugar levels. It's the leading cause of blindness in working-aged adults.This project uses neural networks to predict retinal blindness.
# Dataset
you can use this dataset available on kaggle: https://www.kaggle.com/c/diabetic-retinopathy-detection/data 
This dataset has over 35000 images of retina. The images in the dataset come from different models and types of cameras, which can affect the visual appearance of left vs. right.Pertaining to the preprocessing section, this data is also very noisy, and requires multiple preprocessing steps to get all images to a useable format for training a model.
#PreProcessing of Images
We can scale down all images to 256x256.images without retinopathy were only mirrored and images that had retinopathy were mirrored and roatated 90, 120, 180, and 270 degrees.
After that a new CSV file is created for the augmented dataset which maps each image to a DR level.
# Result 
This model predicts the binary classification whether the provided image has diabetic retinopathy or not with accuracy of 82%.
