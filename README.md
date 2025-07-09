# loan-eligibility
This project explores the application of image classification using a Convolutional Neural Network (CNN) to categorize images of flowers into five distinct classes: daisy, dandelion, rose, sunflower, and tulip. The model is built and trained using TensorFlow and Keras within a Google Colab environment, leveraging a custom dataset stored on Google Drive. The workflow spans dataset preparation, model architecture design, training, and evaluation.

__Core Objectives
- Train a CNN model to classify flower images into five categories
- Leverage image augmentation and preprocessing to enhance model generalization
- Evaluate model performance using training accuracy and loss metrics
- Demonstrate prediction capability on unseen flower images

#Workflow Summary
__Data Loading
- Mounted Google Drive in Colab to access image data
- Loaded image dataset structured in subdirectories by flower type
- Used Keras ImageDataGenerator to flow images from directories with augmentation
- Preprocessing and Augmentation
- Applied image rescaling, rotation, zoom, shear, and flipping for training set
- Normalized pixel values across both training and test images

__Model Architecture
- Built a sequential CNN with convolution, max pooling, dropout, and dense layers
- Used ReLU activations and Softmax for multi-class output
- Trained the model over 30 epochs

__Evaluation
- Achieved approximately 83.5% training accuracy
- Reviewed training and validation accuracy/loss plots to assess overfitting
- Identified potential overfitting due to increasing validation loss

__Prediction
- Used trained model to predict classes of new flower images provided by the user

#Technology Used
- TensorFlow/Keras – for building and training the CNN
- Python – for scripting and data processing
- NumPy – for array operations
- Google Colab – for execution environment
- Matplotlib – for plotting accuracy/loss
