# Description
## As of 07/29/2024 The code has been privated - Can show upon requests

## Objective:
* Get information from VR Headset Devices 
* Push files onto the headset

## Technology
* Python
* TKinter
* adb-shell[usb]
* pyinstaller (Make an exe file)
* Inno (Make an installer)

# Demos And Features
## Production Page
### Fetures:
* Supports hot swapping devices for multiple device configurations. 
* Clicking on any of the Address puts the address into the Clipboard to record device info.
  
### Scan Button Fetures:
Press "Device Scan" after pluging in a device to computer to get:
* MAC Address 
* Bluetooth Address 
* Internal Serial Number 
* Installs Apks and Pushes files (Configured in the Settings page) 

### *Device Scan Button Demo:*  
<img src="https://github.com/user-attachments/assets/3f47916a-4329-434c-8f82-30020145fc3e" alt="GIF of pressing device scan and retreaving info from diffrent devices" width="600">

At the start of the demo no devices was pluged in. \
Between pressing "Device Scan" a new device was plugged in. 
Feedback to the user is placed under the device scan. \
The feedback is in real time. \
Last entry is always "All Porcesses Finished". \
We end the demo by copying the device information into notepad. 

## Settings Page 
### *Changing Start Up Page* 
<img src="https://github.com/user-attachments/assets/99e6762f-0c4a-45bf-a535-611c11a5f6ec" alt="GIF of how to set upload files " width="600">

### *Selecting Folder to Upload* 
<img src="https://github.com/user-attachments/assets/13b1ad74-4309-415d-bba1-49e5f76c2fde" alt="GIF of how to changing stratup page in the settings options " width="600">

* When a selected file is not in the backup directory a copy is made
* Select the device tabs to update what files are installed  
  
### Set Up Application:
* Remenber to install all the dependencies from the dependancies.txt
* In the backup folder make a folder for each device w\ the device name 
* For git

