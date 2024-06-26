# Plant Disease Classification using Deep Learning
<h2>Overview</h2>
This project aims to classify plant diseases using deep learning techniques. The model is trained on a dataset containing images of diseased and healthy potato plants, categorized into three classes: Potato Early Blight, Potato Late Blight, and Potato Healthy. The trained model can predict the disease category of a potato plant based on its image.

<h2>Dataset</h2>
The dataset used for training consists of images sourced from the PlantVillage dataset. It includes:

Potato Early Blight: Images of potato plants affected by early blight disease.

Potato Late Blight: Images of potato plants affected by late blight disease.

Potato Healthy: Images of healthy potato plants.

<h2>Model Architecture</h2>
The deep learning model is implemented using TensorFlow and Keras:


Input images are resized to 256x256 pixels and normalized.

Several convolutional layers followed by max-pooling layers are used for feature extraction.

The model includes dense layers for classification, with a softmax activation function for multi-class classification.

<h2>Training and Evaluation</h2>

The dataset is split into training, validation, and test sets.


Data augmentation techniques such as random flipping and rotation are applied to increase the robustness of the model.

The model is trained using the Adam optimizer with sparse categorical cross-entropy loss.


<h2>Performance</h2>
Performance metrics including accuracy, precision, recall, and F1-score are evaluated on the test set.

**Training Accuracy: 98.78%

Validation Accuracy: 100%

Test Accuracy: 99.21%**
