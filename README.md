
# 🖐️ Virtual Keyboard – Hand Gesture & Voice Controlled Typing  

## 📌 Project Description  
This project implements a **contactless virtual keyboard** that allows users to type using **hand gestures** and **voice input**.  
Using **OpenCV** and **MediaPipe**, the system detects hand landmarks and simulates key presses.  
Additionally, speech recognition enables **voice-to-text typing**, making the keyboard suitable for **hygienic and touch-free environments**.  

---

## 🚀 Features  
- ✋ **Hand Gesture Typing** – Real-time finger tracking to interact with virtual keys.  
- 🎤 **Voice Typing** – Converts spoken words to text when the microphone button is activated.  
- 🌍 **Translation Support** – Integrates language translation for multilingual typing.  
- 🖥️ **On-Screen Virtual Keyboard** – Interactive keyboard displayed using OpenCV.  
- 🧼 **Touchless Interface** – Designed for environments where hygiene is crucial.  

---

## 🛠️ Technology Stack  
- **OpenCV** – Video capture and rendering  
- **MediaPipe** – Hand landmark detection  
- **SpeechRecognition** – Converts voice to text  
- **Googletrans** – Translates spoken text into English  
- **PyAutoGUI** – Sends keystrokes to active applications  

---

## 🎯 Objectives  
- ✅ Develop a **contactless typing solution** to improve hygiene.  
- ✅ Design a **portable and space-saving** input method.  
- ✅ Minimize **device wear** by reducing physical touch.  

---

## ⚡ How It Works  
1. The **webcam** captures hand movements.  
2. **MediaPipe** detects hand landmarks to identify fingertip positions.  
3. Detected gestures trigger **key presses** on the virtual keyboard.  
4. Voice input is processed when the **"Mic" button** is tapped.  
5. Generated text is displayed or sent to the **active application**.  

---

## ✅ Functional Requirements  
- **Camera Interaction**: Detect and track hand position.  
- **Gesture Recognition**: Identify gestures for pressing keys.  
- **Virtual Keyboard Display**: Show interactive keys on screen.  
- **Voice Typing**: Convert speech to text and display it.  

---

## 🖥️ Installation & Setup  

### 1️⃣ Clone the repository  
```bash
git clone https://github.com/your-username/virtual-keyboard-hand-gesture.git
cd virtual-keyboard-hand-gesture
2️⃣ Create and activate a virtual environment
bash
Copy
Edit
python -m venv venv
Windows:

bash
Copy
Edit
venv\Scripts\activate
Linux/Mac:

bash
Copy
Edit
source venv/bin/activate
3️⃣ Install the required dependencies
bash
Copy
Edit
pip install -r requirements.txt
If you don't have a requirements.txt, manually install:

bash
Copy
Edit
pip install opencv-python mediapipe SpeechRecognition googletrans==4.0.0-rc1 pyautogui pywin32
4️⃣ Run the Virtual Keyboard
bash
Copy
Edit
python keybord.py
🔗 References
IEEE Fingertip Detection for Virtual Keyboard

Gesture-Based Keyboard (ICCUBEA 2023)

CNN-based Real-Time Hand Recognition
```
🤝 Contributors
- 👩‍💻 [Swathi M K](https://github.com/SwathiMK2004)
   ``` 
- 👩‍💻 [Piyu](https://github.com/piyu-123-106)
  ``` 
- 👨‍💻 [Supreet Gouda Hiregoudra](https://github.com/SupreetgoudaHiregoudra)  
