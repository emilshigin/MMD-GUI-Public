# MMD-GUI

- ⚠️ As of 07/29/2024 the code has been made private. Access available upon request. 
- A compiled `.exe` version of the application is now available.

## 🎯 Objective
- Retrieve information from VR headset devices  
- Push files to the device over USB

## 🛠️ Technologies
- Python
- Tkinter (GUI)
- `adb-shell[usb]` (USB communication)
- PyInstaller (build `.exe`)
- Inno Setup (build installer)

---

# 🎬 Demos & Features

## 🖥️ Production Page

### Features:
- Supports hot-swapping multiple devices
- Clicking any address field copies it to clipboard for easy logging

### 🔍 Scan Button Features
Press "Device Scan" after plugging in a headset to:
- Retrieve MAC Address
- Retrieve Bluetooth Address
- Retrieve Internal Serial Number
- Automatically install APKs and push files (configured in Settings)

#### 📸 *Device Scan Button Demo:*  
<img src="https://github.com/user-attachments/assets/3f47916a-4329-434c-8f82-30020145fc3e" alt="Demo of device scanning and information retrieval" width="600">

Demo notes:
- At the start, no device is plugged in  
- A new device is plugged in before pressing "Device Scan"  
- Real-time feedback is shown under the button  
- Final log entry: `"All Processes Finished"`  
- Demo ends by copying device info to Notepad

---

## ⚙️ Settings Page

### 🔄 Changing Startup Page
<img src="https://github.com/user-attachments/assets/99e6762f-0c4a-45bf-a535-611c11a5f6ec" alt="Setting startup behavior" width="600">

### 📁 Selecting Folder to Upload
<img src="https://github.com/user-attachments/assets/13b1ad74-4309-415d-bba1-49e5f76c2fde" alt="Selecting folder and configuring uploads" width="600">

- When a selected file is not in the backup directory, a copy is made
- Switching device tabs updates the file set to be installed

---

## 🧪 Setup Instructions

1. Clone the repository (or request access)
2. Install dependencies:
   ```bash
   pip install -r dependencies.txt
