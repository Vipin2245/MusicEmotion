# 🎵 MusicEmotion – Emotion-Based Music Recommendation System

An intelligent web application that recommends music based on the **user’s facial emotions** in real time.  
Using **Deep Learning**, **Computer Vision**, and **Flask**, MusicEmotion detects your mood through your webcam and plays music that matches your current emotion — making your listening experience smarter and more personalized.

---

## 🚀 Features

- 🎭 **Emotion Detection:** Uses a CNN-based facial expression recognition model built with TensorFlow/Keras to detect emotions such as *Happy, Sad, Angry, Neutral,* and *Surprised*.
- 🎧 **Dynamic Music Recommendation:** Suggests and plays songs directly from the integrated MEGA cloud based on detected emotion.
- ⚡ **Real-Time Processing:** Processes webcam input in real-time using **OpenCV** for accurate emotion capture.
- 🌐 **Interactive Web Interface:** Built with **Flask**, **HTML**, **CSS**, and **JavaScript** for smooth and responsive user experience.
- ☁️ **Cloud Integration:** Fetches songs from **MEGA Cloud Storage** for scalable and efficient access.
- 🧠 **High Accuracy:** Achieved **~92% accuracy** on test data for emotion classification.

---

## 🧰 Tech Stack

| Category | Technologies Used |
|-----------|------------------|
| **Frontend** | HTML, CSS, JavaScript |
| **Backend** | Flask (Python) |
| **Machine Learning** | TensorFlow, Keras |
| **Computer Vision** | OpenCV |
| **Cloud Storage** | MEGA Cloud |
| **Dataset** | Custom dataset with 5,000+ labeled facial emotion images |

---

## ⚙️ How It Works

1. **Capture Emotion:**  
   The webcam captures a frame of the user’s face.

2. **Detect Emotion:**  
   The image is processed using OpenCV, and a trained CNN model classifies the emotion.

3. **Fetch Song:**  
   Based on the detected emotion (e.g., *Happy*), a corresponding playlist is fetched from MEGA Cloud.

4. **Play Music:**  
   The song is streamed through the Flask web interface automatically.

---

