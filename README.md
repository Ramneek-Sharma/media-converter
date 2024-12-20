# Media Converter: Video to Audio and Audio to Text
This project provides a Python-based media converter that performs the following tasks:
- Converts video files to audio files.
- Transcribes audio files into text.

## Installation
pip3 install ffmpeg
pip install moviepy
pip install SpeechRecognition pydub

## Workflow
- Video to Audio Conversion:
Use the moviepy library to extract audio from video files.

- Audio to Text Conversion:
Use the SpeechRecognition library to transcribe audio files into text.

##Example

-Convert Video to Audio:

Input a video file (e.g., example.mp4), and the script extracts audio as example.mp3.
<img width="425" alt="Screenshot 2024-12-21 at 3 35 39 AM" src="https://github.com/user-attachments/assets/71ea9bb3-ba14-45b2-a567-6bc554b37760" />
<img width="636" alt="Screenshot 2024-12-21 at 3 36 36 AM" src="https://github.com/user-attachments/assets/f9f72372-9dee-4a30-8f30-cc1c95489217" />
<img width="724" alt="Screenshot 2024-12-21 at 3 36 51 AM" src="https://github.com/user-attachments/assets/bb195522-2a2e-4eaf-a650-cf771eee197d" />
<img width="472" alt="Screenshot 2024-12-21 at 3 54 29 AM" src="https://github.com/user-attachments/assets/96842794-5406-4456-94ac-8588bb22ddaf" />



-Convert Audio to Text:
<img width="458" alt="Screenshot 2024-12-21 at 3 37 19 AM" src="https://github.com/user-attachments/assets/dedce0ae-f499-496e-869a-df97f513ccfb" />


Input the audio file (e.g., example.mp3), and the script generates a text file with the transcription.
