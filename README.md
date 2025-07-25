
<img width="733" height="67" alt="generated_text (11)" src="https://github.com/user-attachments/assets/7799132c-36ab-4fd0-879d-8875d9ac60b5" />


---

# <img width="45" height="45" alt="image-from-rawpixel-id-6430893-png" src="https://github.com/user-attachments/assets/68af7046-94d3-46a5-a16d-fc9388d49aa5" /> Welcome!

This repository contains the **Arduino source code** and **sound files** for the **Plasmagun Project**.

I've also made a **YouTube tutorial**, where I show you **how to build the device step by step**.
Some **electronics parts are briefly explained**, but the main focus is on **the building process**.

---

## <img width="35" height="38" alt="Youtube_logo" src="https://github.com/user-attachments/assets/b3975ed4-adde-4141-aac9-945f6a37d26c" /> YouTube Tutorial

👉 [Watch the tutorial on YouTube](https://www.youtube.com/@LyTack)

---

## 📂 What’s Inside

* 	 <img width="17" height="17" alt="arduino-1-logo-png-transparent" src="https://github.com/user-attachments/assets/4795ee23-0323-4f13-8065-d5c10e393d4f" />​​ 	**Arduino Code** – Clean, structured code with helpful comments
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


