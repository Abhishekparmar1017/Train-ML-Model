Plant Disease Prediction using CNN

1. Importing Libraries & Dependencies

Used Keras and TensorFlow for deep learning.

Imported ImageDataGenerator for image augmentation.

Utilized ModelCheckpoint for saving the best model.

Matplotlib is used for visualization.

2. Data Loading & Augmentation

Mounted Google Drive to access datasets.

Defined training and validation data paths.

Applied image augmentation (rotation, shift, shear, zoom, flip, and rescale) for training.

Used flow_from_directory to load images from respective directories.

3. Model Architecture

Implemented a CNN model with:

4 Convolutional layers with increasing filters (32, 64, 128, 256) and MaxPooling.

Dropout layers (0.5, 0.1, 0.25) to prevent overfitting.

Fully connected layers (Dense) with ReLU activation.

Output layer with Softmax activation for 4-class classification.

4. Compilation & Training

Used Adam optimizer with a learning rate of 0.0001.

Used sparse_categorical_crossentropy as the loss function.

Trained for 100 epochs with validation data.

Saved the best model based on validation accuracy.

5. Model Evaluation & Visualization

Saved the trained model.

Plotted training accuracy vs. validation accuracy.

Plotted training loss vs. validation loss.

Outcome: The model is trained to classify cotton plant diseases effectively using deep learning techniques.

