# 😄 Real-Time Face Emotion Recognition

A real-time facial emotion recognition system built using **TensorFlow**, **OpenCV**, and the **FER-2013 dataset**. This project detects human facial expressions like happy, sad, angry, surprise, etc., directly from webcam video feed.

## 📌 Features

- Real-time emotion detection via webcam
- Trained on FER-2013 dataset
- Emotion classification: 😄 Happy, 😢 Sad, 😠 Angry, 😲 Surprise, 😐 Neutral, 😟 Fear, 😨 Disgust
- Uses **CNN (Convolutional Neural Networks)** for classification
- **Haar Cascade** for face detection
- Clean and simple UI with bounding box and emotion label

## 🛠️ Tech Stack

- Python
- TensorFlow / Keras
- OpenCV
- NumPy / Pandas
- FER-2013 Dataset

## 📂 Dataset

The model is trained on the [FER-2013](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data) dataset, which contains grayscale facial images labeled with emotions.

## 🧠 Model Architecture

- Input: 48x48 grayscale images
- 4 Convolutional layers with ReLU activation
- MaxPooling & Dropout layers
- Dense layers with Softmax for emotion classification

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/face-emotion-recognition.git
   cd face-emotion-recognition
   
2. Install dependencies
     pip install -r requirements.txt
   
4. Run the app
     python real_time_emotion_detection.py
   
5. Train the model
     python train_model.py

🎥 Demo

📈 Accuracy
  Achieved ~78% validation accuracy on FER-2013 after training for 50 epochs.

📁 Folder Structure

face-emotion-recognition/
│
├── model/                  # Trained model (.h5)
├── dataset/                # FER-2013 dataset (if locally stored)
├── real_time_emotion_detection.py
├── train_model.py
├── requirements.txt
└── README.md

🤝 Contribution
Feel free to open issues or pull requests if you'd like to improve this project!
   
