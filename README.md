# Emotion Detection

Emotion Detection is a Flask-based web application integrated with Embeddable Watson AI libraries. The application utilizes a backend API to analyze text input for emotional content, identifying emotions such as anger, disgust, fear, joy, and sadness, and determining the predominant emotion. This API is ideal for integrating into applications requiring sentiment analysis or emotion detection functionalities.

![emotion_detection](https://github.com/user-attachments/assets/3ecd335f-fac8-416f-b23d-6c5b4116613b)

## Installation

**Note:** This application uses the Watson NLP library. Embeddable Watson AI libraries have been pre-installed on the [Skills Network Labs Cloud IDE](https://skills.network/lab-tools/cloud-ide) environment.

1. **Clone the repository**:
   ```bash
   git clone https://github.com/milantony05/emotion-detection.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd emotion-detection
   ```
3. **Install dependencies**:
   ```bash
   pip install flask, requests, pylint
   ```
4. **Run the application**:
   ```bash
   python server.py
   ```
5. **Accessing the application**:
   Open your web browser and go to `http://127.0.0.1:5000` or `http://localhost:5000`.

## Technologies Used

- Python
- Flask
- HTML
- JavaScript
- Watson NLP Library
