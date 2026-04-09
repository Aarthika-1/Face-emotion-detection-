Real-Time Face Emotion Detection

This project is a Real-Time Face Emotion Recognition System built using Python, OpenCV, NumPy, and TensorFlow. It captures video from your webcam and predicts human emotions based on facial expressions.

🚀 Features
🎥 Real-time webcam face detection
🧠 Emotion prediction using trained deep learning model
⚡ Fast and lightweight implementation
🏷️ Displays emotion label on screen
🧰 Technologies Used
Python
OpenCV (cv2)
NumPy
TensorFlow / Keras
📁 Project Structure
emotion-detection/
│
├── emotion_model.h5     # Trained model file
├── main.py              # Main Python script
├── README.md            # Project documentation
⚙️ Installation
Clone the repository:
git clone https://github.com/your-username/emotion-detection.git
cd emotion-detection
Install required libraries:
pip install opencv-python numpy tensorflow
▶️ How to Run
python main.py
Webcam will open 📷
Emotion will be displayed on the screen

Press ESC to exit.

🧠 Model Details
Input shape: 48x48 grayscale image
Preprocessing:
Resize image
Convert to grayscale
Normalize pixel values
Output:
Emotion categories:
Angry 😠
Happy 😊
Sad 😢
Surprise 😲
Neutral 😐
📌 Code Explanation (Short)
Capture video using OpenCV
Resize and preprocess frame
Predict emotion using TensorFlow model
Display result using cv2.putText()





