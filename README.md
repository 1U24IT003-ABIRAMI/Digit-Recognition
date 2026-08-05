# 🔢 Handwritten Digit Recognition using Convolutional Neural Networks (CNN)

## 📌 Project Overview

This project develops a **Convolutional Neural Network (CNN)** to recognize handwritten digits from images. The model is trained on the **MNIST dataset**, which contains grayscale images of handwritten digits (0–9). The goal is to accurately classify each input image into its corresponding digit, demonstrating the effectiveness of deep learning in image recognition tasks.

---

## 📂 Dataset Description

The project uses the **MNIST (Modified National Institute of Standards and Technology)** dataset.

Dataset characteristics:

- Contains **70,000 grayscale handwritten digit images**.
- Image size: **28 × 28 pixels**.
- Digits range from **0 to 9**.
- Training images: **60,000**.
- Testing images: **10,000**.
- Pixel values range from **0 to 255**.

---

## 🛠 Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 🧠 CNN Architecture

The CNN model includes:

- Input Layer
- Convolutional Layers
- ReLU Activation
- Max Pooling Layers
- Flatten Layer
- Fully Connected (Dense) Layers
- Dropout Layer
- Softmax Output Layer

---

## 🔄 Project Workflow

1. Import required libraries
2. Load the MNIST dataset
3. Preprocess and normalize image data
4. Reshape images for CNN input
5. Encode output labels
6. Build the CNN architecture
7. Train the model
8. Evaluate model performance
9. Predict handwritten digits
10. Visualize prediction results

---

## 📊 Evaluation Metrics

The model performance is evaluated using:

- Accuracy
- Loss
- Confusion Matrix
- Training Accuracy
- Validation Accuracy
- Testing Accuracy

---
## 📝 Conclusion

This project demonstrates the effectiveness of **Convolutional Neural Networks (CNNs)** for handwritten digit recognition using the MNIST dataset. By automatically learning visual features from images, the CNN achieves accurate classification of handwritten digits without manual feature extraction.

The project highlights the importance of deep learning in computer vision and serves as a foundation for more advanced image recognition applications. Future enhancements such as deeper CNN architectures, transfer learning, and deployment as a web application can further improve performance and real-world usability.
