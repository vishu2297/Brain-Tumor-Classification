# Brain Tumor Classification Using Machine Learning
 
## About Brain Tumor Classification Project
In this machine learning project, we build a classifier to detect the brain tumor from the MRI scan images. By now it is obvious that this is a binary classification problem.
## Tools and Libraries used
In this project I use these tools and libraries:
- Python – 3.x
- TensorFlow – 2.4.1
- Keras – 2.4.0
- Numpy – 1.19.2
- Scikit-learn – 0.24.1
- Matplotlib – 3.3.4
- OpenCV – 4.5.2
## Steps to Develop Brain Tumor Classifier in Machine Learning
My approach to building the classifier like:
Perform Exploratory Data Analysis (EDA) on brain tumor dataset
Build a CNN model
Train and Evaluate our model on the dataset
## CNN - : 
A Convolutional Neural Network or CNN for short is a deep neural network widely used for analyzing visual images. These types of networks work well for tasks like image classification and detection, image segmentation. There are 2 main parts of a CNN:
- A convolutional layer that does the job of feature extraction
- A fully connected layer at the end that utilizes the output of the convolutional layers and predicts the class of the image.
For the brain tumor project, we are using the VGG16 state-of-the-art network model. There are a number of pre-trained models available for use in Keras.
When I trained the model I got 92.31% accuracy on the test set.
## Summary
In brain tumor classification using machine learning, we built a binary classifier to detect brain tumors from MRI scan images. We built our classifier using transfer learning and obtained an accuracy of 92.31% and visualized our model’s overall performance.
