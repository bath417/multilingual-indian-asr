Multilingual Indian ASR System
Project Overview

This project implements a Multilingual Indian Automatic Speech Recognition (ASR) System that converts speech from Indian languages into text and translates the recognized text into multiple languages.

The system uses the Whisper ASR model for speech recognition and supports languages such as Telugu and Tamil. The recognized text is then translated into multiple languages including English, Hindi, Tamil, and Telugu.

A simple web interface using Gradio allows users to upload speech audio and view multilingual text output.

Features

• Multilingual speech recognition
• Supports Indian languages like Telugu and Tamil
• Automatic speech-to-text conversion
• Multilingual translation of recognized text
• Interactive web interface using Gradio

Technologies Used

Python

Whisper ASR Model

Deep Translator

Gradio

Mozilla Common Voice Dataset

System Architecture
Speech Input
     ↓
Audio Preprocessing
     ↓
Whisper ASR Model
     ↓
Recognized Text
     ↓
Translation Module
     ↓
Multilingual Output
Dataset

Speech samples used in this project are obtained from the Mozilla Common Voice dataset, which provides speech recordings for various languages including Telugu and Tamil.

Installation

Install required libraries:

pip install openai-whisper
pip install gradio
pip install deep-translator
pip install librosa
pip install soundfile
Running the Project


Then open the interface in your browser and upload speech audio.

Example Output

Input speech (Telugu):

ఆదివారం సెలవు దినం

Output:

Recognized Text: ఆదివారం సెలవు దినం

English: Sunday is a day of rest  
Hindi: रविवार आराम का दिन है  
Tamil: ஞாயிற்றுக்கிழமை ஓய்வு நாள்  
Telugu: ఆదివారం సెలవు దినం
Handling Low-Resource Languages

Some Indian languages such as Tulu are considered low-resource languages due to limited datasets. In this project, low-resource scenarios are simulated by using small subsets of available datasets.

Applications

• Voice assistants
• Multilingual communication systems
• Accessibility tools
• Speech-based interfaces

Conclusion

This project demonstrates a Multilingual Indian ASR System capable of converting speech into text and translating it into multiple languages. It highlights the ability of modern ASR models to support multilingual speech processing.

Author

B. Prashanthi 
CSE Student
