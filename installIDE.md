## How to install the Arduino IDE on windows

0. Download Arduino IDE from [here](https://www.arduino.cc/en/software)
0. Open the .exe file and follow on-screen instructions to complete installation
0. If on Windows, you will need to install a driver to connect to the board:
    - Open [this link](https://github.com/adafruit/Adafruit_Windows_Drivers/releases) in a browser
    - Click "adafruit_drivers_X.X.X.X.exe" to download it
    - Double-click "adafruit_drivers_X.X.X.X.exe"
    - Click "I Agree", "Next", "Close" to get the driver installed

## How to install the Arduino IDE on MacOS
0. Download Arduino IDE from [here](https://www.arduino.cc/en/software)
    - Make sure to download correct version, Intel vs Apple Silicon
0. Open the .dmg file and drag to the applications folder


## How to install the Arduino IDE on Linux

0. Download Arduino IDE from [here](https://www.arduino.cc/en/software)
0. Choose "Linux AppImage 64 bits (X86-64)"
0. The file "arduino-ide_2.1.1_Linux_64bit.AppImage" will be saved to your Downloads folder
0. Run these commands in a terminal

        cd ~/Downloads/
        chmod +x arduino-ide_*
        ./arduino-ide_*

0. The Arduino IDE should open



0. Click "File->Preferences"
0. Paste the following into the "Additional Board URLs" textbox:

        https://adafruit.github.io/arduino-board-index/package_adafruit_index.json

0. Click "Ok" to close the Preferences window
0. Click "Tools -> Board -> Boards Manager"
0. Search for "Arduino SAMD Boards" and click "Install"
0. Wait a few minutes for the installation to complete
0. Next, search for "Adafruit SAMD Boards" and click "Install"
0. Wait a few minutes for the installation to complete
0. Reopen the Arduino IDE
    - Click "File -> Quit"
    - Run these commands in a terminal

          cd ~/Downloads/
          chmod +x arduino-ide_*
          ./arduino-ide_*

0. Select "Tools -> Board -> Adafruit SAMD boards -> Adafruit ItsyBitsy M4 (SAMD51)"
0. Done with setup! Continue to a different section.