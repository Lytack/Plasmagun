
# 🔥 <img width="1879" height="72" alt="generated_text (2)" src="https://github.com/user-attachments/assets/e1e29e2e-13df-45b0-bea9-5df349616d71" />



---

**Welcome!**

This repository contains the **Arduino source code** and **sound files** for the **Plasmagun Project**.

I've also made a **YouTube tutorial**, where I show you **how to build the device step by step**.
Some **electronics parts are briefly explained**, but the main focus is on **the building process**.

---

## 🎥 YouTube Tutorial

👉 [Watch the tutorial on YouTube](https://www.youtube.com/@LyTack)

---

## 📂 What’s Inside

* **🔌 Arduino Code** – Clean, structured code with helpful comments
* **🔊 DFPlayer Mini Sounds** – All required audio files
* **🧠 Simple Logic** – Easy to understand and modify

---

## 🧰 Required Arduino Libraries

Please install the following libraries in the Arduino IDE before uploading the code:

| Library               | Source/Note                                         |
| --------------------- | --------------------------------------------------- |
| `Wire`                | Built-in                                            |
| `Adafruit SSD1306`    | By Adafruit                                         |
| `Adafruit GFX`        | By Adafruit                                         |
| `DFRobotDFPlayerMini` | By DFRobot                                          |
| `SoftwareSerial`      | Built-in                                            |
| `elapsedMillis`       | By Paul Stoffregen                                  |
| `Adafruit BMP280`     | By Adafruit                                         |
| `Adafruit BusIO`      | Needed for BMP280                                   |
| `AHT20`               | By Adafruit (or compatible)                         |
| `TFLI2C`              | Benewake TFMini LiDAR Library *(available as .zip)* |

---

## 🚀 How to Run the Code

1. **Install the Arduino IDE**
   👉 [https://www.arduino.cc/en/software](https://www.arduino.cc/en/software)

2. **Prepare the IDE**
   Go to **File → Preferences** and enable:

   * ✅ Line Numbers
   * ✅ Verbose Output (optional, for debugging)

3. **Install Libraries**
   Open **Tools → Manage Libraries...** and install the libraries listed above.

4. **Load the Code**
   Copy the Arduino code from this repository into the IDE.

5. **Prepare the Sounds**
   Copy the entire `mp3` folder onto a **FAT32 formatted microSD card**.

6. **Insert the microSD card into the DFPlayer Mini.**

7. **Connect your Arduino via USB.**

8. **Select your board and COM port:**

   * **Tools → Board** → Choose your Arduino model (e.g., Uno, Nano)
   * **Tools → Port** → Select the correct COM port

9. **Upload the code**
   Press **Upload** (🔼) and wait until the transfer is complete.

---

## ⚠️ Important Notes

* The code works **out of the box**.
* Make sure the `mp3` folder is correctly placed on the microSD card.
* Insert the card into the **DFPlayer Mini** before running the system.

---

## 📄 License

This project is licensed under a **custom non-commercial license**:

You may **share, modify, and showcase** this project **online**, but you must **credit the original author**:
**"Coded by LyTack"**

**Commercial use is not permitted without written permission.**
Full terms are available in the [`LICENSE`](./LICENSE) file.

---

## 🙌 Credits 


<img width="360" height="97" alt="generated_text (4)" src="https://github.com/user-attachments/assets/2fb42d78-e5de-419a-932a-e24c4d67e8ce" />


