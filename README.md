1️⃣What does this project do?

This project implements a Convolutional Neural Network (CNN) to classify images from the Fashion-MNIST dataset into 10 different clothing categories.

2️⃣ Why was this project built?

The project was built to practice deep learning concepts, build a well-structured CNN, and evaluate model performance with proper metrics and minimal overfitting.

3️⃣ What dataset is used?

Fashion-MNIST dataset

60,000 training images, 10,000 test images

Image size: 28x28 grayscale

10 clothing classes: T-shirt/Top, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, Ankle boot

4️⃣ What technologies and tools are used?

TensorFlow / Keras

NumPy

Matplotlib

Scikit-learn

5️⃣ What is the model architecture?

Conv2D (32 filters) + BatchNormalization + ReLU

Conv2D (64 filters) + BatchNormalization + ReLU

MaxPooling2D

Conv2D (128 filters) + BatchNormalization + ReLU

MaxPooling2D

Flatten → Dense (128 units) + ReLU → Dropout (0.3)

Output Layer (Softmax – 10 classes)

6️⃣ How was the model trained?

Optimizer: Adam

Loss Function: Sparse Categorical Crossentropy

Validation Split: 20%

Data Augmentation: Random Horizontal Flip

EarlyStopping callback used (restore best weights)

Epochs: up to 40

7️⃣ What are the results?

Training Accuracy: 95.3%

Test Accuracy: 93%
The model generalizes well with minimal overfitting (≈2% gap between training and test accuracy)
Bassam Mostafa
