# Fake-vs-Real-Face-Detector
A deep learning model that basically acts as a discriminator between real and fake faces. This implementation includes two models, one model is in implemented using TensorFlow and the other is implemented using PyTorch.


# Setup
## Dataset
  * It is basically a dataset from the Kaggle website named Fake-Vs-Real-Faces (Hard)[^1].  
  * The is relatively small which includes in total 1288 face images. 
  * The number of fake samples is 700 and the number of real samples is 589.
[^1]: [Fake-Vs-Real-Faces (Hard)](https://www.kaggle.com/datasets/hamzaboulahia/hardfakevsrealfaces)
## Input
  * The input size was chosen to be 128x128 (WidthxHeight).
  * The images are in RGB format.
## Common Hyperparameters
  * Both models use Adam optimizer during the training process with a learning rate of 0.001.
  * Both models were trained for 8 epochs.
  * Adam optimizer was used in both.

## Results
  * It showed a test accuracy of 98.06% in TensorFlow implementation.
  * It showed a test accuracy of 99.59% in PyTorch implementation.
  * This shows that Pytorch delivered better generalized results than TensorFlow.


## Technologies
- Python
 
- Google Colab
   
- TensorFlow
  
- PyTorch


    
