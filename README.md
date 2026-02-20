# Voice Language Translator (Python GUI)

This project is a simple attempt to solve a real-life problem — **understanding different languages easily**.
I built this desktop application using Python to translate text or speech from one language to another and even **listen to the translated result**.

The idea was to explore how multiple technologies like speech recognition, translation APIs, and text-to-speech can work together in one application.

##  Why I Built This

While learning Python, I wanted to move beyond theory and create something practical that people actually use in daily life.
Language translation is something we all rely on, so I decided to build my own version to understand:

* How real applications handle user input
* How APIs can be integrated into software
* How voice processing works
* How to design a GUI-based application from scratch

This project helped me understand how different components connect to form a complete workflow.

##  What This Application Can Do

✔ Translate text between multiple languages
✔ Take voice input using a microphone
✔ Convert speech → text → translated text
✔ Read the translated result aloud
✔ Provide an easy-to-use graphical interface
✔ Demonstrate real-time interaction between user and system

##  Tech Stack Used

* **Python** – Core programming language
* **Tkinter** – Building the graphical user interface
* **SpeechRecognition** – Capturing and processing voice input
* **deep-translator** – Handling language translation
* **gTTS (Google Text-to-Speech)** – Generating speech output
* **playsound** – Playing translated audio
* **Pillow** – Improving UI visuals

---

## 📷 Application Preview
<img width="805" height="712" alt="multilang snap" src="https://github.com/user-attachments/assets/408e1244-a3d9-4a5b-b44b-36f2875ef246" />

##  How to Run This Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/language-translator.git
cd language-translator
```
### 2️⃣ Install Required Libraries

```bash
pip install deep-translator
pip install gTTS
pip install pillow
pip install SpeechRecognition
pip install pyttsx3
pip install pyaudio
pip install playsound==1.2.2
```
### 3️⃣ Run the Application

```bash
python Translator.py
```
##  How It Works (Behind the Scenes)

1. The user types text or speaks into the microphone.
2. SpeechRecognition converts voice input into text.
3. The deep-translator library translates the text into the selected language.
4. gTTS converts the translated text into speech.
5. The application plays the audio so the user can hear the result.

##  What I Learned From This Project

* Integrating multiple Python libraries into one workflow
* Handling real-time input and output in GUI applications
* Debugging environment and dependency issues
* Designing user-friendly desktop interfaces
* Understanding how translation and speech systems interact

##  Future Improvements

I plan to enhance this project by adding:

* Translation history storage
* Dark/Light mode UI
* Auto language detection
* Export translated text to file
* Better UI styling and responsiveness

---

Author-Riya
