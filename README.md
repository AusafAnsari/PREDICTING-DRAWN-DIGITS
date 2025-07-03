🖌️ MNIST Digit Recognition GUI with CNN
A simple yet powerful GUI application that allows users to draw digits on a canvas and get real-time predictions using a Convolutional Neural Network (CNN) trained on the MNIST dataset.

🧠 Features
Digit drawing canvas using Tkinter

Predicts handwritten digits (0–9) using a CNN

Automatically trains and saves a model (mnist_cnn.h5) if not already present

Clean UI with Clear and Predict buttons

Confidence score displayed with prediction

🖼️ Demo

(Add your own screenshot or GIF here)

🚀 How It Works
Draw a digit (0–9) on the canvas.

Click Predict to see the model's prediction and confidence.

Click Clear to reset the canvas and try again!

🧰 Tech Stack
Python 3

TensorFlow/Keras

Tkinter

PIL (Pillow)

NumPy

🧪 Model Architecture
text
Copy
Edit
Conv2D(32) → MaxPooling2D →
Conv2D(64) → MaxPooling2D →
Flatten → Dense(64) → Dense(10 Softmax)
Trained on the MNIST dataset

3 epochs, batch size: 128

📦 Installation
Clone the repo:

bash
Copy
Edit
git clone https://github.com/your-username/mnist-digit-draw.git
cd mnist-digit-draw
Install dependencies:

bash
Copy
Edit
pip install tensorflow pillow numpy
Run the app:

bash
Copy
Edit
python mnist_cnn.py
The app will train a new CNN model if mnist_cnn.h5 is not found.

📁 File Structure
bash
Copy
Edit
mnist_cnn.py        # Main application file
mnist_cnn.h5        # Trained model (auto-generated)
✍️ Author
[Your Name]
Feel free to contribute, star the repo, or report any issues!

📝 License
This project is licensed under the MIT License.



https://github.com/user-attachments/assets/59c89949-3b32-4544-bf3c-326970d3960a

