
# 🖌️ MNIST Digit Recognition GUI with CNN

A simple yet powerful GUI application that allows users to draw digits on a canvas and get real-time predictions using a Convolutional Neural Network (CNN) trained on the MNIST dataset.

## 🧠 Features

- Digit drawing canvas using Tkinter
- Predicts handwritten digits (0–9) using a CNN
- Automatically trains and saves a model (`mnist_cnn.h5`) if not already present
- Clean UI with Clear and Predict buttons
- Confidence score displayed with prediction

## 🚀 How It Works

1. Draw a digit (0–9) on the canvas.
2. Click **Predict** to see the model's prediction and confidence.
3. Click **Clear** to reset the canvas and try again.

## 🧰 Tech Stack

- Python 3
- TensorFlow / Keras
- Tkinter
- Pillow (PIL)
- NumPy

## 🧪 Model Architecture

```
Conv2D(32, 3x3) → ReLU → MaxPooling
→ Conv2D(64, 3x3) → ReLU → MaxPooling
→ Flatten → Dense(64, ReLU)
→ Dense(10, Softmax)
```

- Trained for 3 epochs, batch size: 128
- Dataset: MNIST

## 📦 Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/mnist-digit-draw.git
cd mnist-digit-draw
```

2. Install required packages:

```bash
pip install tensorflow pillow numpy
```

3. Run the application:

```bash
python mnist_cnn.py
```

The app will train and save a model (`mnist_cnn.h5`) if not already found.

## 📁 File Structure

```
mnist_cnn.py         # Main app file (GUI + ML logic)
mnist_cnn.h5         # CNN model file (auto-generated)
```

## ✍️ Author

Ausaf Ansari

## 📝 License

This project is licensed under the MIT License.



https://github.com/user-attachments/assets/59c89949-3b32-4544-bf3c-326970d3960a

