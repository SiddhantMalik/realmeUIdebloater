To enable USB debugging on a Realme phone and install ADB on Windows, follow these steps:

1. Enable Developer Options: On your Realme phone, go to "Settings" and scroll down to "About Phone." Tap on it, then locate "Build Number." Tap on "Build Number" seven times continuously. This action will enable the Developer Options on your phone.

2. Enable USB Debugging: Go back to the main settings and scroll down to find "Additional Settings." Tap on it, then locate and tap on "Developer Options." Find "USB Debugging" in the Developer Options menu and toggle the switch to enable it. You may be prompted to confirm your action. Select "OK" or "Allow" to proceed.

3. Connect your Realme phone to your PC: Using a USB cable, connect your Realme phone to your Windows PC.

4. Install ADB on Windows:
   a. Download the ADB (Android Debug Bridge) installer for Windows from the official Android Developers website: https://developer.android.com/studio/releases/platform-tools.
   b. Extract the downloaded ZIP file to a folder on your computer, for example, "C:\adb" to make it easier to access.

5. Add ADB to system PATH:
   a. Open the File Explorer and navigate to the folder where you extracted the ADB files (e.g., "C:\adb").
   b. In the address bar of the File Explorer, type "cmd" and press Enter. This will open a Command Prompt window.
   c. In the Command Prompt window, type the following command and press Enter:
      ```
      setx /M PATH "%PATH%;C:\adb"
      ```
   d. Close the Command Prompt window.

6. Test ADB: Open a Command Prompt window by searching for "cmd" in the Start menu or pressing Win + R, typing "cmd," and pressing Enter. In the Command Prompt window, type the following command and press Enter:
   ```
   adb devices
   ```
   If ADB is correctly installed and the device is connected properly, you should see your Realme phone listed as a connected device.

USB debugging is now enabled on your Realme phone, and ADB is installed on your Windows PC. You can use ADB commands to interact with your device, such as installing apps, accessing the shell, transferring files, and more.

now click the donwnloaded file "debloater.bat"
