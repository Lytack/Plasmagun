# Powerful Plasmagun Project

Welcome!  
This repository contains the full Arduino source code and sound files used in the **Plasmagun** project.

I created a tutorial video on YouTube where I build the device and show how certain parts work.

---

## 📹 YouTube Tutorial

👉 [Watch the tutorial here](https://www.youtube.com/)  

---

## 📁 What’s inside

- 🔌 **Arduino Code** – Some parts of the code are commented to help you understand how it works  
- 🔊 **DFPlayer Mini Sounds** – All audio files  
- 🧠 Simple, clean structure and logic

---

## 🧩 Required Arduino Libraries

Make sure you install these libraries in the Arduino IDE before uploading the code:

- `Wire` (built-in)  
- `Adafruit SSD1306` by Adafruit  
- `Adafruit GFX` by Adafruit  
- `DFRobotDFPlayerMini` by DFRobot  
- `SoftwareSerial` (built-in)  
- `elapsedMillis` by Paul Stoffregen  
- `Adafruit BMP280` by Adafruit  
- `Adafruit BusIO` *(needed for BMP280)*  
- `AHT20` by Adafruit *(or similar compatible library)*  
- `TFLI2C` (TFMini LiDAR Library by Benewake – often as `.zip` from GitHub)

---

## 🛠 How to run the Code in Arduino

1. **Download and install Arduino IDE**  
   👉 https://www.arduino.cc/en/software

2. **Open Arduino IDE**  
   Go to **File → Preferences**, and enable:  
   - ✅ Line numbers  
   - ✅ Verbose output (optional for debugging)

3. **Install required libraries**  
   Go to **Tools → Manage Libraries...**  
   Search for each of the libraries listed above and click **Install**

4. **Kopie the Arduino code folder** from this repository in the IDE  

5. **Copy the entire `mp3` folder to a FAT32 formatted microSD card**

6. **Insert the microSD card into the DFPlayer Mini**

7. **Connect your Arduino via USB**

8. **Select your board and port**  
   - Go to **Tools → Board** and choose your Arduino model (e.g., Arduino Uno or Nano)  
   - Go to **Tools → Port** and select the correct COM port

9. **Upload the code**  
   Press **Upload** (🔼 Arrow button) and wait for the code to compile and transfer

---

## ⚠️ Note

The code works without any modifications — just make sure the `mp3` folder is saved on a microSD card and inserted into the DFPlayer Mini.

---

## 📜 License

This project is licensed under a **custom non-commercial license**:  
You are free to share, modify, and show this project **online**, but you must always credit the original author:  
**"Coded by LyTack"**

Commercial use is not allowed without written permission.  
Read the full terms in the [`LICENSE`](./LICENSE) file.

---

## 🤝 Credits

Created by **LyTack**
