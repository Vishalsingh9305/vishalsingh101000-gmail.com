# Potato-Disease-Classification


Gathered a large dataset containing images which were divided into three classes "Healthy", "Early blight" and "Late blight".

Data Preprocessing:
Resize all images to a consistent size suitable for input into the CNN.
Split the dataset into training, validation, and test sets.
Normalize the pixel values of the images (typically between 0 and 1) to ensure consistent training.

Model Architecture:
Designed a CNN architecture tailored for image classification. A typical CNN consists of convolutional layers, pooling layers, and fully connected layers.
The convolutional layers are responsible for extracting features from the input images.
Pooling layers reduce the spatial dimensions of the feature maps, making the network computationally efficient.
Fully connected layers at the end of the network classify the extracted features into different disease categories.

Model Training:
Trained the CNN using the training dataset. During training, the model adjusts its internal parameters to minimize the difference between its predictions and the actual labels.
Utilize techniques such as data augmentation to artificially increase the size of the training dataset and improve the model's ability to generalize.

Model Evaluation:
Evaluate the trained model's performance on the validation set using metrics like accuracy, precision, recall, and F1-score.
Adjust the model's hyperparameters (e.g., learning rate, batch size, number of layers) based on the validation performance to optimize its performance.

Testing and Deployment:
Once satisfied with the model's performance, evaluate it on the test set to assess its ability to generalize to unseen data.
Deploy the trained CNN as a predictive tool that can classify potato diseases in real-time or analyze large datasets of potato plant images.
