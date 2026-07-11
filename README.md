# 🛁 Yur Bathroom

An automated smart bathroom control system with an integrated heating management unit. This IoT-based project combines micro-controllers, custom circuitry, and physical product design to optimize water temperature regulation and user comfort.

---

## ⚡ Key Features

- **Automated Heating Regulation:** Closed-loop PID temperature control via water-safe thermal sensors.
- **Smart Safety Cut-offs:** Automated emergency shut-offs to prevent overheating or dry running.
- **Custom Physical Enclosure:** Tailor-made, waterproof 3D-modeled casing for system component protection.
- **User Interface Panel:** Real-time temperature readout and tactile control responses.

---

## 📐 Project Structure & Components

The repository is divided into two primary engineering domains:

### 1. 🧠 Hardware & Firmware (Arduino / C++)
The system runs on an **ATmega328P (Arduino)** platform, handling low-level hardware interactions with real-time stability.
- **Languages & Tools:** C++, Arduino IDE / PlatformIO
- **Key Modules:** Temperature monitoring, relay control loops, safety interrupt handlers, and display updates.

### 2. 🧱 Mechanical Design (3D CAD Models)
The physical housing and structural mounts are engineered to withstand high humidity environments.
- **Formats Included:** `.STEP` (for CAD modifications) and `.STL` (ready for 3D printing).
- **Design Focus:** Ergonomics, passive ventilation for electronics, and splash-proof sealing.

---

## 🚀 Getting Started

### Hardware Assembly
1. Refer to the schematics provided in the `/hardware` directory.
2. Connect the temperature sensor probes and the heating element relay to the specified Arduino pins.
3. Ensure proper electrical isolation between high-voltage heating units and low-voltage control circuits.

### Firmware Flashing
1. Open `/firmware/smart_bath.ino` in your preferred IDE.
2. Install necessary library dependencies (e.g., OneWire, DallasTemperature for sensors).
3. Select your board type and upload the code via USB.

---

## 🛠️ Tools & Technologies Used

- **Microcontroller:** Arduino Platform (ATmega328P)
- **Programming:** C / C++ (Embedded)
- **Mechanical Design:** 3D CAD Modeling (SolidWorks / Fusion 360 / Inventor / Kompas)
- **Manufacturing:** FDM 3D Printing (PETG/ABS recommended for humidity resistance)

---

## 📸 Media & Gallery
<p align="center">
  <img src="https://github.com/loanelly/Yur-Bathroom/blob/main/Model%202%20pre%20relese/ObshyZborScreenshot.png" width="50%" alt="LOOCK" />
  <img src="https://github.com/loanelly/Yur-Bathroom/blob/main/Project-Versions/Brain/Ur-Bathroom-Brain%20V%201.1/Construct/Screenshots/opera_Eaa8KB0pD8.png" width="41%" alt="BRAIN" />
</p>

---
<p align="center">
  Crafted with ❤️ by hand <a href="https://github.com/loanelly">loanelly</a>.
</p>

<p align="center">
  <img src="https://github.com/loanelly/Readmess/blob/main/SomeCstGifs/cute-cat-cat-on-throne.webp" height="42" valign="middle"/>
</p>
<div align="center">

