# Python-Speech-Recognizer

Speech recognition is the process of converting spoken words to text. Python supports many speech recognition engines and APIs, including Google Speech Engine, Google Cloud Speech API.

Read more at 
https://pypi.python.org/pypi/SpeechRecognition/

#Installation
pip install SpeechRecognition

The SpeechRecognition module depends on pyaudio, you can install them from your package manager.
Speech Recognition with Google
The example below uses Google Speech Recognition engine, which I’ve tested for the English language.

For testing purposes, it uses the default API key.
To use another API key, use

r.recognize_google(audio, key="GOOGLE_SPEECH_RECOGNITION_API_KEY")
