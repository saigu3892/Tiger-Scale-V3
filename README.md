# 🐯 Tiger-Scale-V3 - Track your 3D printing filament usage

[![](https://img.shields.io/badge/Download-TigerScale-blue)](https://github.com/saigu3892/Tiger-Scale-V3)

Tiger-Scale-V3 monitors your 3D printing filament. It connects to your printer setup to track how much material remains on your spools. This device uses the TigerTag open NFC standard to identify spools and provides real-time data on a built-in touchscreen. It helps you avoid running out of material during long prints.

## 📦 What you need
*   Windows computer (Windows 10 or 11).
*   USB-C cable for the connection.
*   One Tiger-Scale-V3 device.
*   A stable internet connection for initial setup.

## 📥 Getting the software
Visit [the official download page](https://github.com/saigu3892/Tiger-Scale-V3) to access the latest files. Click the link to go to the repository where you can find the installer for your Windows machine.

## 🛠️ Setting up your scale
1.  Connect your Tiger-Scale-V3 unit to your computer using the USB-C cable.
2.  Open the folder you downloaded from the website.
3.  Double-click the installer file.
4.  Follow the prompts on your screen to complete the installation.
5.  Wait for the progress bar to finish.
6.  Restart your computer if the installer asks you to do so.

## 🔌 Connecting the device
Once the software runs, you must link your device to your computer:
1.  Open the Tiger-Scale application from your start menu.
2.  Ensure the USB-C cable connects the scale to your computer.
3.  The application will detect the ESP32-S3 hardware automatically.
4.  Select your device from the list in the application window.
5.  Click the Connect button to finish the sync process.

## 💡 How to use the scale
Place your filament spool onto the scale platform. The dual PN532 NFC readers will scan the TigerTag. The 3.5-inch LVGL touchscreen shows the current weight and the remaining length of your filament. If the screen does not update, ensure the spool rests firmly on the platform. The battery powers the unit when you remove the USB cable, allowing you to move the scale around your workshop.

## ⚙️ Updating the firmware
The device supports over-the-air updates. Connect the scale to your Wi-Fi network using the touchscreen menu. The system checks for new versions of the software. If an update exists, the screen displays a notification. Select Update to install the latest features. Do not disconnect the power during this process.

## 🔧 Troubleshooting
If the scale does not show data:
*   Check the USB connection.
*   Verify the device shows power on the screen.
*   Restart the application on your computer.
*   Ensure the NFC tag faces the reader inside the base.

## 📖 Frequently Asked Questions
**Does this work with all filament brands?**
Yes, as long as you use TigerTag NFC labels on your spools.

**Can I run this on a Mac?**
The current installer supports Windows. Future versions may include support for other operating systems.

**How do I calibrate the weight?**
Use the Settings menu on the touchscreen. Place a known weight on the center of the platform and follow the calibration instructions.

**Is the battery included?**
The unit contains a rechargeable battery for portable use. Charge it via the USB-C port.

Keywords: 3d-printing, esp-web-tools, esp32, esp32-s3, filament, filament-scale, iot, lvgl, nfc, ota, platformio, pn532, rfid, scale, tigertag, web-serial