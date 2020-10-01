# Python-AI-Virtual-Assistant

## Project description
### pyttsx3
* `pyttsx3` is a text-to-speech conversion library in Python. Unlike alternative libraries, it works offline, and is compatible with both Python 2 and 3
* #### Installation
   `pip install pyttsx3`
   
   If you recieve errors such as No module named `win32com`.client, No module named win32, or No module named win32api, you will need to additionally install `pypiwin32`.
* #### Usage :
    import pyttsx3 <br />
    engine = pyttsx3.init() <br />
    engine.say("I will speak this text") <br />
    engine.runAndWait()
### speech_recognition
8 Library for performing speech recognition, with support for several engines and APIs, online and offline.
* #### Installation
   `pip install SpeechRecognition`
   
   
* #### Usage :
    import speech_recognition as sr <br />
    engine = pyttsx3.init('sapi5') <br />
    voices = engine.getProperty('voices') <br />
    engine.setProperty('voice', voices[0].id) <br />
    Recognize speech input from the microphone <br />

    
![a i -face](https://user-images.githubusercontent.com/53833750/94780233-bc829280-03e5-11eb-803f-4823bdbcec0c.gif)
