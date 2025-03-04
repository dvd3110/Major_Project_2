# Major_Project_2

**Workflow of the Code:**<br>
Mount Google Drive:
Accesses dataset files from Google Drive.

Define Dataset Paths:
Specifies directories for training, testing, and validation datasets.

Import Libraries:
Loads necessary libraries for deep learning, image processing, and visualization.

Set Image Processing Parameters:
Defines image size and batch size for training.

Initialize Image Data Generators:
Prepares images for training and validation with data augmentation.

Create Training & Validation Generators:
Loads images from directories and applies preprocessing.

Set Up Callbacks:
Implements learning rate reduction, early stopping, and model checkpointing.

Load Pretrained Xception Model:
Uses a pretrained model (without top layers) as a feature extractor.

Build the Final Model:
Adds additional layers for classification and sets output size.

Compile the Model:
Uses Adam optimizer and categorical cross-entropy loss.

Train the Model:
Runs training for 50 epochs using training and validation data.

Visualize Training Performance:
Plots loss and accuracy curves for training and validation.

Save the Trained Model:
Stores the trained model in Google Drive.

Define Image Preprocessing Function:
Converts images into model-compatible format.

Load & Predict Single Image:
Processes a single image and predicts its class.

Display Predicted Image & Class:
Shows the image with its predicted class.

Repeat Prediction for Multiple Images:
Manually predicts classes for multiple individual images.
