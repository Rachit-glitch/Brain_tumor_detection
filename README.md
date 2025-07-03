# Brain_tumor_detection
Brain tumor detection using CNN and VGG15
This project uses deep learning, specifically Convolutional Neural Networks (CNN), to automatically detect the presence of brain tumors from MRI images. Early detection of brain tumors is critical for treatment, and this model aims to support medical professionals.
The dataset consists of MRI brain scan images categorized into two classes: "yes" (tumor present) and "no" (no tumor). The data was split into training, validation, and test sets to ensure robust evaluation of the model. 
Images were resized to 150x150 pixels and normalized.
Data Augmentation techniques such as rotation, zoom, and flipping were applied to increase training data variability. 
We used the pre-trained VGG16 model wihtout the top layers for feature extraction. It is followed by fully connected layers for classification.
The model was trained for 10 epochs with early stopping to prevent overfitting. 

The model achieved approximately 89% accuracy on the test set. 
