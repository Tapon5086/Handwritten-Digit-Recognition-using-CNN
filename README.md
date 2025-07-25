

```markdown
# 🖐️ Handwritten Digit Recognition using CNN

A real-time handwritten digit recognition system built with a **Convolutional Neural Network (CNN)** and **OpenCV**. This project allows users to draw digits on a virtual canvas and get instant predictions using a model trained on the **MNIST dataset**.

---

## 🔍 Features

- 🖌️ Interactive drawing canvas using OpenCV  
- 🔢 Real-time digit prediction as you draw  
- 🧼 Clickable **Clear** button to reset the canvas  
- 🧠 Trained CNN model with **over 97% accuracy**  
- 🖥️ Predictions displayed cleanly in the terminal  

---

## 📁 Folder Structure

Handwritten-Digit-Recognition/
│
├── model/
│   └── digit\_recognition\_model.keras    # Trained CNN model
│
├── train\_model.py                       # Script to train and save the model
├── draw\_predict.py                      # Application for drawing and predicting
├── requirements.txt                     # Required Python packages
└── README.md                            # Project documentation

````

---

## 🛠️ Installation

1. **Clone the repository:**

```bash
git clone https://github.com/yourusername/Handwritten-Digit-Recognition.git
cd Handwritten-Digit-Recognition
````

2. **Install the dependencies:**

```bash
pip install -r requirements.txt
```

---

## ✅ `requirements.txt`

```
tensorflow
opencv-python
numpy
```

---

## 🧠 Model Training

To train your own CNN model:

```bash
python train_model.py
```

This will:

* Load the **MNIST** dataset
* Train the CNN for **5 epochs**
* Save the trained model to `model/digit_recognition_model.keras`

You can also use the included pretrained model directly without training.

---

## 🚀 Run the Application

Start the real-time digit recognition interface:

```bash
python draw_predict.py
```

**Controls:**

* ✍️ Draw using **left mouse button**
* 📤 Prediction is printed **automatically** in the terminal
* 🔄 Click **"Clear"** to reset canvas
* ❌ Press **ESC** to exit

---

## 🖼️ Sample Demo

✅ Live digit prediction while drawing
✅ Easy-to-use interface built with OpenCV
✅ Model trained on the MNIST dataset

![image](https://github.com/user-attachments/assets/a192b97f-3de3-4e5f-ae7e-1c31175d140e)

---

## 📚 Skills Demonstrated

* 🤖 Deep Learning with CNNs
* 🖼️ Image preprocessing
* 🧠 Real-time inference using OpenCV
* 🧩 Python scripting and modular design
* 🖱️ GUI handling with OpenCV

---

## 🤝 Acknowledgements

* [MNIST dataset](http://yann.lecun.com/exdb/mnist/)
* [TensorFlow](https://www.tensorflow.org/) and [Keras](https://keras.io/) team

---

## 📌 Future Improvements

* 💻 Add support for touchscreen/stylus input
* 📊 Show prediction confidence in real-time
* 🖼️ Option to export drawn digit as an image

---

## 👨‍💻 Author

**Tapon Paul**
[GitHub](https://github.com/Tapon5086)

---

⭐ If you found this project useful, please **star** the repository and share it with others!

```

Let me know if you'd like a version with badges (e.g., TensorFlow version, license, etc.) or a link to deploy the app using Streamlit Cloud.
```
