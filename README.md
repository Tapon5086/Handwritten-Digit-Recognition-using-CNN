# Handwritten-Digit-Recognition-using-CNN
This project is a real-time handwritten digit recognition system built with a Convolutional Neural Network (CNN) and OpenCV. It allows users to draw digits on a virtual canvas and get live predictions from a trained model based on the MNIST dataset.

# 🔍 Features
•🖌️ Interactive drawing canvas using OpenCV <br>
•🔢 Real-time digit prediction as you draw  <br>
•🧼 Clickable Clear button to reset the canvas  <br>
•🧠 Trained CNN model with over 97% accuracy <br>
•🖥️ Clean UI with predictions shown in the terminal only <br>

# 📁 Folder Structure
Handwritten-Digit-Recognition/ <br>
│<br>
├── model/<br>
│ └── digit_recognition_model.keras # Trained model file<br>
│<br>
├── train_model.py # Script to train and save the CNN model<br>
├── draw_predict.py # Main application for drawing and predicting<br>
|__requirements.py<br>
├── README.md # Project description and instructions<br>

# 🛠️ Installation
Clone the repository and install the required packages:<br>
<br>
git clone https://github.com/yourusername/Handwritten-Digit-Recognition.git<br>
cd Handwritten-Digit-Recognition<br>
pip install -r requirements.txt<br>

# ✅ And include the requirements.txt file like this:
# requirements.txt 
tensorflow<br>
opencv-python<br>
numpy<br>
# 🧠 Model Training
You can train the CNN model using train_model.py: <br>

python train_model.py <br>
This will: <br>

. Load the MNIST dataset <br>

. Train a CNN for 5 epochs <br>

. Save the model in model/digit_recognition_model.keras <br>
# 🚀 Run the Application
Once the model is trained, run the digit recognition app: <br>

python draw_predict.py<br>
Controls:<br>
• Draw using left mouse button<br>
• Prediction is printed in terminal automatically while drawing<br>
• Click "Clear" button to erase canvas<br>
• Press ESC to exit the application<br>
# 🖼️ Sample Demo
✅ Live digit prediction while drawing ✅ Easy-to-use interface built with OpenCV ✅ Model trained on the MNIST dataset
![image](https://github.com/user-attachments/assets/a192b97f-3de3-4e5f-ae7e-1c31175d140e)
# 📚 Skills Demonstrated
• Deep Learning with CNNs<br>
• Image preprocessing<br>
• OpenCV GUI handling<br>
• Real-time inference<br>
•Python scripting and modular design<br>
# 🤝 Acknowledgements
• MNIST dataset<br>
• TensorFlow and Keras team<br>
# 📌 Future Improvements
• Add support for touchscreen/stylus input<br>
• Display prediction confidence<br>
• Export drawn digit as an image<br>
# Author
Tapon Paul
