
 
 <img width="1879" height="72" alt="generated_text (7)" src="https://github.com/user-attachments/assets/e1e29e2e-13df-45b0-bea9-5df349616d71" />



---

# 🔥 Welcome! 🔥

This repository contains the **Arduino source code** and **sound files** for the **Plasmagun Project**.

I've also made a **YouTube tutorial**, where I show you **how to build the device step by step**.
Some **electronics parts are briefly explained**, but the main focus is on **the building process**.

---

## <img width="35" height="38" alt="Youtube_logo" src="https://github.com/user-attachments/assets/b3975ed4-adde-4141-aac9-945f6a37d26c" /> YouTube Tutorial

👉 [Watch the tutorial on YouTube](https://www.youtube.com/@LyTack)

---

## 📂 What’s Inside

* ** <svg xmlns="http://www.w3.org/2000/svg" width="2" height="2" viewBox="0 0 1372.201 1372.684"><path fill="#00979D" stroke="#81C9CB" stroke-width=".932" stroke-miterlimit="10" d="M1371.701 686.024c0 378.658-306.972 685.605-685.549 685.605C307.451 1371.629.5 1064.682.5 686.024.5 307.455 307.451.483 686.152.483c378.594.001 685.549 306.972 685.549 685.541z"/><linearGradient id="a" gradientUnits="userSpaceOnUse" x1="-16.3" y1="16.071" x2="1354.901" y2="16.071" gradientTransform="matrix(1 0 0 -1 16.8 702.696)"><stop offset=".117" stop-color="#fff" stop-opacity="0"/><stop offset=".252" stop-color="#c0d1d3" stop-opacity=".153"/><stop offset=".387" stop-color="#91b3b7" stop-opacity=".306"/><stop offset=".52" stop-color="#6d9fa3" stop-opacity=".457"/><stop offset=".65" stop-color="#4d9195" stop-opacity=".604"/><stop offset=".776" stop-color="#30888b" stop-opacity=".746"/><stop offset=".895" stop-color="#148386" stop-opacity=".881"/><stop offset="1" stop-color="#008184"/></linearGradient><linearGradient id="b" gradientUnits="userSpaceOnUse" x1="-16.8" y1="16.071" x2="1355.401" y2="16.071" gradientTransform="matrix(1 0 0 -1 16.8 702.696)"><stop offset="0" stop-color="#fff" stop-opacity="0"/><stop offset=".153" stop-color="#c0d1d3" stop-opacity=".153"/><stop offset=".306" stop-color="#91b3b7" stop-opacity=".306"/><stop offset=".457" stop-color="#6d9fa3" stop-opacity=".457"/><stop offset=".604" stop-color="#4d9195" stop-opacity=".604"/><stop offset=".746" stop-color="#30888b" stop-opacity=".746"/><stop offset=".881" stop-color="#148386" stop-opacity=".881"/><stop offset="1" stop-color="#008184"/></linearGradient><path opacity=".5" fill="url(#a)" stroke="url(#b)" stroke-miterlimit="10" d="M1371.701 686.595c0 378.65-306.972 685.606-685.549 685.606C307.451 1372.201.5 1065.23.5 686.595.5 308.019 307.451 1.048 686.152 1.048c378.594.016 685.549 306.97 685.549 685.547z"/><g fill="#FFF"><path d="M947.959 931.196c-12.909 0-26.127-.929-39.127-2.864-108.978-15.554-181.848-93.822-222.665-153.989-40.946 60.166-113.811 138.512-222.74 154.045a275.864 275.864 0 0 1-39.133 2.785c-67.753 0-131.358-25.217-179.201-71.003-48.299-46.165-74.951-108.114-74.951-174.171 0-66.14 26.651-128.004 75.021-174.253 47.797-45.793 111.449-70.936 179.231-70.936 12.918 0 26.067.928 39.023 2.783 108.932 15.535 181.794 93.813 222.743 153.99 40.825-60.177 113.689-138.432 222.658-153.99 13-1.863 26.148-2.783 39.066-2.783 67.753 0 131.401 25.208 179.197 70.936 48.345 46.249 74.937 108.113 74.937 174.253 0 66.057-26.524 128.006-74.868 174.171-47.881 45.785-111.434 71.026-179.191 71.026M734.42 686.024c21.283 40.534 84.067 141.676 186.692 156.375 8.984 1.236 18.028 1.923 26.839 1.923 92.185 0 167.225-71.002 167.225-158.322s-75.023-158.321-167.291-158.321c-8.812 0-17.853.629-26.753 1.921-102.644 14.664-165.428 115.806-186.712 156.424M424.393 527.702c-92.308 0-167.36 70.998-167.36 158.321 0 87.305 75.021 158.322 167.245 158.322 8.852 0 17.897-.688 26.879-1.922 102.629-14.697 165.394-115.783 186.689-156.375-21.237-40.535-84.061-141.761-186.689-156.376-8.877-1.341-17.945-1.97-26.764-1.97"/><path d="M354.37 662.051h152.625v49.181H354.37zM1016.484 662.051h-51.671v-51.747h-49.348v51.747h-51.648v49.181h51.648v51.737h49.348v-51.737h51.671z"/></g></svg>
![arduino-1-logo-svg-vector](https://github.com/user-attachments/assets/524c7093-f113-40fb-9208-619aa3dbd38e) Arduino Code** – Clean, structured code with helpful comments
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


