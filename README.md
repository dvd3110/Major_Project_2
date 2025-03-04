# Major_Project_2

**Workflow of the Code:**<br><br>
Mount Google Drive : 
Accesses dataset files from Google Drive.<br>

Define Dataset Paths : 
Specifies directories for training, testing, and validation datasets.<br>

Import Libraries : 
Loads necessary libraries for deep learning, image processing, and visualization.<br>

Set Image Processing Parameters:
Defines image size and batch size for training.<br>

Initialize Image Data Generators:
Prepares images for training and validation with data augmentation.<br>

Create Training & Validation Generators:
Loads images from directories and applies preprocessing.<br>

Set Up Callbacks:
Implements learning rate reduction, early stopping, and model checkpointing.<br>

Load Pretrained Xception Model:
Uses a pretrained model (without top layers) as a feature extractor.<br>

Build the Final Model:
Adds additional layers for classification and sets output size.<br>

Compile the Model:
Uses Adam optimizer and categorical cross-entropy loss.<br>

Train the Model:
Runs training for 50 epochs using training and validation data.<br>

Visualize Training Performance:
Plots loss and accuracy curves for training and validation.<br>

Save the Trained Model:
Stores the trained model in Google Drive.<br>

Define Image Preprocessing Function:
Converts images into model-compatible format.<br>

Load & Predict Single Image:
Processes a single image and predicts its class.<br>

Display Predicted Image & Class:
Shows the image with its predicted class.<br>

Repeat Prediction for Multiple Images:
Manually predicts classes for multiple individual images.
