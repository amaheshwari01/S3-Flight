
## How to set up the Quest Software
0. Make sure to have the Arduino IDE installed [instructions here](installIDE.md)
0. Go to the Flight SW repository release page ([link](https://github.com/howellivy/S3-Flight))
0. Download the latest "Source code (zip)" or clone the repository
0. Unzip the folder
0. Inside, you will find a "libraries" folder
0. Copy what is inside this folder to the Arduino libraries folder
    - Windows Location: C:\Users\{username}\Documents\Arduino/libraries
    - Mac OS Location: ~/Documents/Arduino/libraries
    - Linux Location: ~/Arduino/libraries

0. Navigate back to the Flight repository that you downlaoded and delete the libraries folder
0. Now you have the libraries installed!, and now you need to set up the Development board

## Set up Itsy Bitsy M4
0. Open the Arduino IDE (If you have not installed it yet, see the section for [installation](installIDE.md))
0. In the Arduino IDE open Settings, select "File -> Settings"
    - It may also be under "File -> Prefrences"
    - on MacOS it is under "Arduino IDE - Settings"
0. In the Aditional Boards Manager URL paste this: https://adafruit.github.io/arduino-board-index/package_adafruit_index.json
0. Close the Settings window and navigate to Boards Manager and search for "Adafruit SAMD Boards" and Install
0. Now you are all set up and can run the code!

## Running the code 
