Music Recommendation System using Facial Expression Recognition (FER)

📖 Overview

This project presents an intelligent Music Recommendation System that uses Facial Expression Recognition (FER) to recommend songs based on the user's current mood. By analyzing facial expressions in real-time through the device's camera, the system suggests a playlist that matches the detected emotion, enhancing the user's listening experience.

🎯 Objectives

Detect user's mood using facial expressions.

Recommend music that resonates with the detected mood.

Provide an interactive and personalized music experience.

🛠️ Technologies Used

Python (for backend and ML model implementation)

OpenCV (for image capturing and preprocessing)

TensorFlow / Keras (for facial expression recognition model)

scikit-learn (for emotion classification)

Flask (for creating the web application - optional)

HTML, CSS, JavaScript (for frontend - optional)

📸 How it Works

Capture Image: OpenCV captures the user's face through the webcam.

Detect Emotion: The FER model processes the image and predicts the user's emotion.

Recommend Music: Based on the detected emotion, a song or playlist is suggested from a pre-organized local folder or fetched from Spotify API.

Play Music: The system plays the recommended music automatically.

😄 Emotions Supported

Happy

Sad

Angry

Neutral

📋 Requirements

Python 3.7+

OpenCV

TensorFlow / Keras

numpy
pygame (for music playback)
