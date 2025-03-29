MNIST Classification with TensorFlow 🚀

📌 Project Overview
This project builds a Deep Learning model using TensorFlow to classify handwritten digits from the MNIST dataset. The model achieves 96.26% test accuracy after training on 5 epochs.

📂 Dataset
The MNIST dataset consists of 60,000 training and 10,000 test grayscale images.

Each image is 28×28 pixels, representing a digit from 0 to 9.

Data is normalized (scaled to 0-1) for better performance.

🛠️ Technologies Used
Python

TensorFlow & Keras (for deep learning)

TensorFlow Datasets (tfds) (to load MNIST)

NumPy (for numerical computations)

📜 Implementation Details
1️⃣ Load the MNIST Dataset

Data is loaded using tensorflow_datasets with as_supervised=True.

2️⃣ Data Preprocessing

Images are normalized (divided by 255.0).

Training data is shuffled (BUFFER_SIZE=1000) for randomness.

Data is batched (BATCH_SIZE=100) for efficient training.

3️⃣ Model Architecture

Input Layer: Flattens the 28×28 image into a 784-dimensional vector.

Hidden Layers:

Layer 1: 50 neurons, ReLU activation

Layer 2: 50 neurons, ReLU activation

Output Layer: 10 neurons (softmax activation) for digit classification.

4️⃣ Training the Model

Loss Function: sparse_categorical_crossentropy (for multi-class classification).

Optimizer: Adam (adam).

Epochs: 5

5️⃣ Testing the Model

The model achieves 96.26% test accuracy after evaluation.

For any queries please contact
Email :pranavanilkumar44@gmail.com  | Github : Pranav-Anil44
