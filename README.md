# 🎙️ Multilingual Indian ASR System

<div align="center">

![Python](https://img.shields.io/badge/Python-3.8+-blue?style=for-the-badge&logo=python)
![Whisper](https://img.shields.io/badge/OpenAI-Whisper-412991?style=for-the-badge&logo=openai)
![Gradio](https://img.shields.io/badge/Gradio-UI-orange?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

**Convert Indian language speech to text — and translate it into multiple languages instantly.**

</div>

---

## 📌 Project Overview

This project implements a **Multilingual Indian Automatic Speech Recognition (ASR) System** that converts speech from Indian languages into text and translates it into multiple languages.

- 🔊 Uses **OpenAI Whisper ASR** for accurate speech recognition  
- 🌐 Supports **Telugu** and **Tamil** speech input  
- 🔁 Translates recognized text into **English, Hindi, Tamil, and Telugu**  
- 🖥️ Simple **Gradio web interface** for easy interaction  

---

## ✨ Features

| Feature | Description |
|---|---|
| 🎤 Multilingual ASR | Recognizes speech in Telugu and Tamil |
| 🔁 Auto Translation | Translates output into 4 languages |
| 🌐 Web Interface | User-friendly Gradio UI |
| 📦 Easy Setup | Simple pip installation |
| 📊 Low-Resource Support | Handles limited-data language scenarios |

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| 🐍 Python | Core programming language |
| 🤖 Whisper ASR | Speech-to-text conversion |
| 🌍 Deep Translator | Multilingual text translation |
| 🖥️ Gradio | Interactive web interface |
| 🗣️ Mozilla Common Voice | Speech training dataset |

---

## 🧠 System Architecture
```
🎤 Speech Input
       ↓
🔧 Audio Preprocessing
       ↓
🤖 Whisper ASR Model
       ↓
📝 Recognized Text
       ↓
🌍 Translation Module
       ↓
🌐 Multilingual Output
```

### Stage-by-Stage Breakdown

| Stage | Description |
|---|---|
| 🎤 **Speech Input** | User provides audio in Telugu or Tamil |
| 🔧 **Preprocessing** | Audio converted to required format & sampling rate |
| 🤖 **Whisper ASR** | Multilingual model converts speech → text |
| 📝 **Recognized Text** | Raw transcribed text is generated |
| 🌍 **Translation** | Text is translated into multiple languages |
| 🌐 **Final Output** | Results displayed in English, Hindi, Tamil, Telugu |

---

## 📂 Dataset

Speech samples are sourced from the **[Mozilla Common Voice Dataset](https://commonvoice.mozilla.org/)**, which includes:

- 🗣️ **Telugu** recordings  
- 🗣️ **Tamil** recordings  

This dataset helps evaluate the system's multilingual recognition capabilities.

---

## ⚙️ Installation
```bash
pip install openai-whisper
pip install gradio
pip install deep-translator
pip install librosa
pip install soundfile
```

---

## ▶️ Running the Project
```bash
python app.py
```

> After running, a **Gradio link** will be generated.  
> Open it in your browser and **upload audio to test the system**.

---

## 📊 Example Output

**Input Speech (Telugu):**
```
ఆదివారం సెలవు దినం
```

**Output:**
```
✅ Recognized Text : ఆదివారం సెలవు దినం

🇬🇧 English  : Sunday is a day of rest
🇮🇳 Hindi    : रविवार आराम का दिन है
🌿 Tamil    : ஞாயிற்றுக்கிழமை ஓய்வு நாள்
🌸 Telugu   : ఆదివారం సెలవు దినం
```

---

## 🌍 Handling Low-Resource Languages

Some Indian languages like **Tulu** have limited speech data available.  
This project simulates low-resource scenarios using **small subsets of available datasets** to evaluate performance under constrained conditions.

---

## 🚀 Applications

- 🎙️ **Voice Assistants** — Regional language support  
- 🌐 **Multilingual Communication** — Cross-language understanding  
- ♿ **Accessibility Tools** — Help for hearing or speech impaired  
- 📱 **Speech-based Apps** — Mobile and web integrations  

---

## 🏁 Conclusion

This project demonstrates a working **Multilingual Indian ASR System** capable of:

✅ Recognizing Indian language speech  
✅ Translating it into 4 major languages  
✅ Serving results through an interactive web UI  

It highlights how modern **multilingual models** can support India's diverse linguistic landscape.

---

## 👩‍💻 Author

**B. Prashanthi**  
🎓 CSE Student  

---

<div align="center">
⭐ If you found this project useful, consider giving it a star!
</div>
