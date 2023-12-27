# SpeechRecognition

## Introduction
This notebook demonstrates a process for voice cloning and text replacement using the TorToiSe library for text-to-speech synthesis. The main steps include extracting text from an uploaded audio file, replacing specific words in the text, and cloning the voice with the modified text.

Dependencies
Before running the notebook, ensure that the required dependencies are installed. You can install them using the following command:


### !pip install SpeechRecognition torchaudio tor-toise

Usage Instructions
### 1. Extract Text from Audio
Upload your WAV audio file when prompted.
The notebook will use the SpeechRecognition library to convert the audio to text.
### 2. Replace Words in the Text
Enter the word you want to replace and the replacement word when prompted.
The notebook will output the modified text.
### 3. Clone Voice with Modified Text
Download the pretrained model by running the provided cell.
Optionally, upload your own voice clips for cloning.
Generate speech with the custom voice for the modified text.
Play the generated audio, combining the original and TTS parts.
### 4. Additional Voice Cloning (Optional)
Optionally, you can perform additional voice cloning with a different custom voice.
Follow the steps for uploading your own voice clips.
Generate speech with the custom voice for the modified text.
Combine the audio_before, generated speech, and audio_after to create the final audio.
## Notes
Ensure that the uploaded audio files are in WAV format and are 6-10 seconds long.
The quality of the voice cloning can be adjusted using the preset mode ("ultra_fast," "fast," "standard," "high_quality").
The notebook uses the TorToiSe library for voice cloning, which may involve downloading additional models from the HuggingFace hub.
