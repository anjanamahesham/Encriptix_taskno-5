# Encriptix_taskno-5
Face Recognition using ResNet-18 trained on an Avengers image dataset. The project includes data preprocessing, model training, and inference for identifying Avengers characters. Features quick and accurate identification, with potential for real-time applications and future enhancements.

Project Goals

The primary goal of this project is to develop a robust face recognition system using deep learning techniques. The system is designed to accurately identify individuals based on their facial features from images. It can be used for various applications such as security, authentication, and identification in different scenarios.

Methodology
This project is built on several key components:

Data Preparation: Images of faces are preprocessed using data augmentation techniques like random cropping, resizing, and horizontal flipping to enhance the training process.
Model Architecture: The ResNet-18 architecture is utilized, with modifications to the final fully connected layer to match the number of classes (individuals) in the dataset.
Training: The model is trained using a labeled dataset of faces. Cross-Entropy Loss is employed as the loss function, and Stochastic Gradient Descent (SGD) with momentum is used for optimization.
Inference: The trained model is used to make predictions on new images, identifying the person in the image based on the learned features.

Features
Efficient Search Capability: The model is optimized for quick inference, allowing for fast identification of individuals in real-time applications.
Modular Architecture: The project is organized into separate modules for data preparation, model training, and inference, making it easy to extend or modify.

License
This project is licensed under the MIT License. This means that you are free to use, modify, and distribute this software for both personal and commercial purposes as long as you include the original copyright notice and disclaimer. For more details, see the LICENSE file.
