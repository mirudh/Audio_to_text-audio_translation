Create a virtual environment using the below code:

python -m venv vnv
Activate the environment
Install the below packages:
1. speechRecognition
2. pydub
3. googletrans==3.1.0a0
4. gtts

The following procedures are followed for an audio to audio translation:

1. Reading the input .mp3 file and recognizing the audio using speech recognizer and converting the same to text
2. Using google translate, the following text is converted to a text of the desired language
3. The translated text is converted to audio using gtts library

To do the same just run the audio_to_text.ipynb file
audio.mp3 --> input file
final.mp3 --> output file
