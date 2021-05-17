# Cassava-Leaves-Classifier
Kaggle competition project - creating image classifier. The model recognizes cassava leaves diseases belonging to 5 classes.

In this project I decided to use transfer learning. I experimented with a few models: Xception, Inception and VGG19. I have gained the best results using VGG19 though. 

The project can be summarized in a few simple steps:
1. Importing the dataset
2. Creating Train and Validation generators and augmenting the images
3. Initializing the VGG19 model
4. Fitting the model on the train data and evaluating on validation data.

I was using TensorFlow.
