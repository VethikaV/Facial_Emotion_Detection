

]🎭 Facial Emotion Recognition using OpenCV and DeepFace

This project implements a **real-time facial emotion recognition system** using **OpenCV** for video capture and **DeepFace** for deep learning-based emotion analysis. It captures video through a webcam, detects faces using Haar Cascade classifiers, and predicts emotional states such as *happy*, *sad*, *angry*, *surprise*, and more. The recognized emotions are displayed live on the video stream, making the system interactive and visually informative.


🚀 Features

- Real-time face detection using Haar Cascades
- Emotion prediction using DeepFace's pre-trained deep learning models
- Live video streaming with emotion labels
- Lightweight and easy to run on standard systems
- Supports 7 emotions: **Happy, Sad, Angry, Surprise, Fear, Disgust, Neutral**

---

🛠️ Technologies Used

- **OpenCV** – for video capture and face detection  
- **DeepFace** – for emotion recognition  
- **Python** – core programming language  
- **Haarcascade XML** – for face detection  

---

## 📸 How It Works

1. Starts the webcam using OpenCV.
2. Detects faces in each frame using Haarcascade.
3. Extracts face region and sends it to DeepFace.
4. Predicts the dominant emotion.
5. Displays the face with a rectangle and the predicted emotion label.

---

## 🧠 Emotion Classes

- 😄 Happy  
- 😢 Sad  
- 😠 Angry  
- 😲 Surprise  
- 😐 Neutral  
- 😱 Fear  
- 🤢 Disgust  

---

## ▶️ How to Run

```bash
pip install opencv-python deepface
python emotion_detection.py
```

Make sure you have a webcam connected, and the `haarcascade_frontalface_default.xml` file in the same directory.

---

## 📂 Project Structure

```
├── emotion_detection.py
├── haarcascade_frontalface_default.xml
├── README.md
```

---

## 📌 Future Scope

- Support for multiple face tracking
- Emotion logging and trend analysis
- Web/mobile-based deployment
- Integration with virtual assistants and chatbots

---

Feel free to fork, contribute, or raise issues! 😊  
**Star ⭐ the repo if you found it helpful.**

---

Let me know if you want me to create the actual `README.md` content or help with uploading your project to GitHub.
