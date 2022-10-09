## Voice-translator

Overview: 
This is real-time voice translator that can translate any input language spoken by the user to the language chosen by the user. This code uses googletrans==3.1.0a0 API, provided by google. It also uses the SpeechRecognition library, that recognizes the voice spoken by the user and saves it in .mp3 file format. First the user speakes the sentence to be translated and then it is recorded in audio file. This audio file is converted to text using gTTs API. Now this text is then translated to the target language and again it is converted to audio file using gTTs text to speech API. At last this audio is saved in captured_voice.mp3 file and played.

Prerequisites: i) Python version 3 or above 
              ii) numpy 
             iii) pip

In commond prompt run these commands: 

Step 1: pip install playsound==1.2.2  

Step 2: pip install SpeechRecognition 

Step 3: pip install googletrans==3.1.0a0

Step 4: pip install gTTs

Step 5: pip install gTTS-token

Step 6: pip install pyaudio

