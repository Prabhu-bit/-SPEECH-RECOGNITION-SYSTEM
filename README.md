# SPEECH-RECOGNITION-SYSTEM

This project presents the development of a cloud-based audio transcription system that is capable of handling multiple audio file formats and automatically detecting the spoken language before converting it into accurate text. Designed to run in Google Colab using Python, this system allows users to upload audio files in formats such as .wav, .mp3, and .ogg, transcribe the content using Google's speech recognition API, and export the final results in a structured text file. The project combines several powerful open-source libraries including SpeechRecognition, pydub, ffmpeg, and langdetect to ensure smooth and reliable processing.

The transcription process begins by allowing users to upload multiple audio files simultaneously. Many real-world audio datasets contain various formats, and to handle this, the project includes an automatic format conversion step. This is done using the pydub library, which converts any non-WAV files into mono-channel, 16kHz .wav format—optimized for speech recognition. This ensures compatibility and accuracy during the transcription phase.

Once the audio files are standardized, the system utilizes the SpeechRecognition library with Google’s Web Speech API to perform speech-to-text conversion. This API is known for its robustness and multi-language support. After the transcription is completed, the project employs the langdetect library to analyze the transcribed text and automatically detect the spoken language. This feature makes the system dynamic and flexible, eliminating the need for users to manually specify the language beforehand.

One of the most significant strengths of this project is its ability to handle multilingual content, making it ideal for applications in diverse linguistic environments. Whether the audio is in English, Hindi, Tamil, or Spanish, the system can process and understand the content with high accuracy, provided that the audio quality is clear. This versatility opens the door for real-world applications such as educational lecture transcription, multilingual interview processing, multilingual voice assistant logs, or subtitles generation for videos.

The final transcription results—including the filename, detected language, and recognized text—are consolidated into a plain text file (transcriptions.txt). This file can be easily downloaded from the Colab environment and shared for further use, making the system highly portable and collaborative.

Overall, this project demonstrates a practical implementation of natural language processing (NLP) and speech recognition technologies in a user-friendly and scalable format. It is designed with both technical and non-technical users in mind, using a no-install, cloud-based environment that simplifies experimentation and deployment. By supporting multiple audio formats, multiple languages, automatic language detection, and downloadable transcription outputs, the project serves as a powerful tool in bridging the gap between spoken and written communication. It can be extended in the future with features like speaker diarization, emotion detection, or integration with real-time audio streams.

#OUTPUT

![Image](https://github.com/user-attachments/assets/45524108-34ec-47b6-a0c8-3c02f9fdee3d)

![Image](https://github.com/user-attachments/assets/94848fde-7a6e-45fc-95ea-dd00bed6a537)


