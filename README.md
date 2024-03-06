# YouTube Audio Transcriber using OpenAI's Whisper Model
This project automates the transcription process of YouTube videos using OpenAI's Whisper model. It downloads audio from YouTube links, segments the audio, removes silent parts, transcribes each segment using the Whisper model, and generates a CSV file with the transcriptions.

## Project Overview
The goal of this project is to simplify the transcription of YouTube videos by leveraging state-of-the-art AI models. It provides a user-friendly interface for initiating the transcription process and handles the complexities of audio processing and model integration.

## Code Files
1. GenerateSubtitles.py: Downloads YouTube audio, transcribes audio segments, and saves transcriptions to a CSV file.

2. Librosa_silence.py: Removes silent segments from audio files.

3. Main.py: GUI application for running the subtitle generation process.

4. Transcript_segment_classification.py: Segments and transcribes audio files using the Whisper model.

5. Youtube_audio.py: Downloads audio from YouTube videos.

6. run.py: Main script to execute the subtitle generation process.

## Usage
Run run.py to launch the GUI application.
Input a CSV file containing YouTube video links.
Click on "Generate Subtitles" to initiate the transcription process.
The transcriptions will be saved to a CSV file named transcription_output.csv.

## Note
The Whisper model requires significant computational resources and time for transcription.
Ensure the provided CSV file contains valid YouTube video links.
Please be patient as the transcription process may take time depending on the video length.

## Dependencies
whisper
pydub
librosa
pytube
moviepy
tkinter
