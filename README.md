# X-Ray-Detection

## Dataset
The dataset was taken from [Kaggle](https://www.kaggle.com/datasets/bmadushanirodrigo/x-ray-and-non-x-ray-image-classification-data). 

## Description
I worked with a team of five to create a model that can automatically identify whether an image is an X-ray or not. We used Python to process the images and built the model using TensorFlow, a popular tool for machine learning.

To improve the model's accuracy, we tried a few different techniques:
- L2 Regularization: This technique helps the model perform well with new images by avoiding mistakes from learning too much from specific details in the training data.
- Dropout: We occasionally turned off parts of the model during training to make it more flexible and better at recognizing various types of images.
- Batch Normalization: This approach helped the model learn faster by ensuring the training data was consistent throughout the process.
- Epoch Tuning: We tested different numbers of training cycles to find the best results without making the model too slow or inaccurate.

## Conclusion
The model reached a 98% accuracy in distinguishing X-ray images from others, suggesting it can reliably handle this task with minimal human involvement. By automating this process, organizations could reduce the time and cost spent on manually sorting images, making data management more efficient.
