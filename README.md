🌾 Overview

Rice crops are often affected by various leaf diseases, and early detection helps farmers prevent larger damage.
This deep-learning model automatically classifies images of rice leaves into different disease categories using CNN-based image recognition.

The project includes:

Data loading & preprocessing

Image normalization

CNN model (VGG16-based)

Training & validation

Confusion matrices

Accuracy & loss plots

Classification report

Class distribution visualization

🧠 Model Architecture (CNN – VGG16)

Base Model: VGG16 (without pre-trained ImageNet weights)

Input Size: 128 × 128 × 3

Layers Added:

Flatten

Dropout (0.5)

Dense(512, ReLU)

Dense(num_classes, Softmax)

Optimizer: Adam (lr = 0.0001)
Loss: Categorical Crossentropy
Batch Size: 32
Epochs: 20

🔧 Tech Stack

Python

TensorFlow / Keras

NumPy

Pandas

Matplotlib

Seaborn

PIL

Scikit-learn

📊 Visualizations
✔ 1. Accuracy & Loss Curves

Shows training vs validation performance.

✔ 2. Confusion Matrices

Training confusion matrix

Validation confusion matrix

Helps identify misclassified disease categories.

✔ 3. Class Distribution Plot

Visual overview of dataset balance.

✔ 4. Classification Report

Provides:

Precision

Recall

F1-score

Support

