# UTC_2738_STEER

A PlatformIO firmware for the Seeed Studio XIAO ESP32-S3 Plus, part of the Maker Starter Kit.

![Project Image](image.png)

## Hardware
- **Main Board:** [Seeed Studio XIAO ESP32-S3 Plus](https://www.seeedstudio.com/XIAO-ESP32S3-p-5627.html)
- **Expansion Base:** [Seeed Studio XIAO Expansion Board Wiki](https://wiki.seeedstudio.com/Seeeduino-XIAO-Expansion-Board/)

## Features
- **Board Bring-up:** Automated diagnostic tests for OLED, RTC, and WiFi.
- **Clock & Weather:** Live NTP clock and Singapore weather updates.
- **Configurable:** Feature blocks can be toggled via compile-time switches.

## Development Setup

### 1. Prerequisites
- **Visual Studio Code:** Download and install from [code.visualstudio.com](https://code.visualstudio.com/).
- **PlatformIO IDE Extension:** Install the PlatformIO IDE extension from the VS Code Marketplace.

### 2. Cloning the Project
You can clone this repository directly within VS Code or via the terminal.

**Via VS Code:**
1. Press `Ctrl+Shift+P` (or `Cmd+Shift+P` on macOS) to open the Command Palette.
2. Type `Git: Clone` and press Enter.
3. Paste the repository URL: `https://github.com/SustainableLivingLab/UTC_2738_STEER.git`
4. Select a local folder to save the project and click **Open** when prompted.

**Via Terminal:**
```powershell
git clone https://github.com/SustainableLivingLab/UTC_2738_STEER.git
```

### 3. Opening the Project
1. Open Visual Studio Code.
2. Click on the **PlatformIO** icon on the left sidebar (looks like an ant).
3. Select **Pick a folder** (or **Open Project**) and navigate to the `UTC_2738_STEER` directory.

### 4. Building and Uploading
- **Build:** Click the **Checkmark** icon in the VS Code status bar.
- **Upload:** Click the **Right Arrow** icon in the VS Code status bar.
- **Serial Monitor:** Click the **Plug** icon in the VS Code status bar.

### 5. Command Line Usage
If you prefer using the terminal, always use the absolute path to the PlatformIO executable as configured for this environment:
- **Build:**
  ```powershell
  C:\Users\teren\.platformio\penv\Scripts\pio.exe run --environment seeed-xiao-esp32-s3-plus
  ```
- **Upload:**
  ```powershell
  C:\Users\teren\.platformio\penv\Scripts\pio.exe run --target upload --environment seeed-xiao-esp32-s3-plus
  ```
- **Monitor:**
  ```powershell
  C:\Users\teren\.platformio\penv\Scripts\pio.exe device monitor
  ```

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Copyright
© 2026 SL2 - Sustainable Living Lab
[Sustainable Living Lab (SL2)](https://www.sl2square.org)

**Version:** 0.1.0
