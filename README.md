# Pocket-tts-st-bridge
This is a SillyTavern bridge service that allows Pocket-TTS to act as an OpenAI TTS compatible service for generating voice responses.

## Install
Requires Python 3.11+  
Recommended: Use Virtual env (https://docs.python.org/3/tutorial/venv.html)  
Installation: `pip install -r requirements.txt`  

## Usage
Command: `python server.py`

## Misc
Serves to localhost:5050 (also: 127.0.0.1:5050 )  
Configuration in SillyTavern:  
TTS Provider: `OpenAI Compatible`  
Default Voice: Any except disabled (Author recommends `azelma`)  
Provider Endpoint: `http://127.0.0.1:5050/`  
Model: `pocket-tts`  
Available voices: `alba,marius,javert,jean,fantine,cosette,eponine,azelma`  
  
For audio samples/voice testing, got to http://127.0.0.1:5050/ after running the service.
