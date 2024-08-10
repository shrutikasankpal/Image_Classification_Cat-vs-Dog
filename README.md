A. Data Preparation:
  1. Downloaded the dataset using Kaggle API.
  2. Unzipped and extracted the dataset for training and validation.

B. Load and Preprocess Data:
  1. Load training and validation images.
  2. Normalize image pixel values.

C. Build the Model:
  1. Create a CNN with convolutional, max-pooling, and dense layers.
  2. Add dropout layers to prevent overfitting.

D. Train the Model:
  1. Compile the model with the Adam optimizer.
  2. Train for 10 epochs and monitor accuracy and loss.

E. Evaluate the Model:
  1. Plot accuracy and loss curves for training and validation.

F. Test the Model:
  1. Load and preprocess a test image.
  2. Predict the class of the test image.
