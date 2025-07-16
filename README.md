# AudioSpeech-To-Text-Converter

This GitHub repository contains a Python Streamlit app that utilizes machine learning to convert speech to text. The app allows users to upload audio files (in WAV or MP3 format) and uses the Speech Recognition library to perform speech recognition and convert the speech into text.

This GitHub repository contains a Python Streamlit app that utilizes machine learning to convert speech to text. The app allows users to upload audio files (in WAV or MP3 format) and uses the SpeechRecognition library to perform speech recognition and convert the speech into text.

Features:

Supports uploading audio files in WAV or MP3 format.
Automatic conversion of MP3 files to WAV format for compatibility with the SpeechRecognition library.
Utilizes the Google Web Speech API for speech recognition.
Displays the converted text on the Streamlit app's interface.
Requirements:

Python 3.7 or above
Streamlit
SpeechRecognition
PyDub
Instructions:

Clone or download this repository.
Install the required dependencies using 'pip install -r requirements.txt'.
Run the app with the command 'streamlit run app.py'.
Access the app through the provided URL and upload your audio file.
The app will convert the speech in the audio file to text using the Google Web Speech API.
Note: The quality of the speech-to-text conversion depends on the audio file's clarity and the underlying machine learning model.
