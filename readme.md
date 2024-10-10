# S3 Flight Software


[Installation/Setup Guide](setup.md)


## Running the code 

0. Make sure to complete the [Installation/Setup Guide](setup.md) first and have this reposotory downloaded
0. Navigate to where you downloaded this repository
0. Move the Quest_CLI folder outside the current folder and move it to somewhere else where you are keeping your code
0. Navigate to `~/Projects/Quest_CLI/` and double-click `Quest_CLI.ino`
0. Connect a development board to your computer using a USB cable
0. Click "Tools -> Port -> /dev/ttyACM0 (Adafruit ItsyBitsy M4 (SAMD51))"
    - It may be called something different based on your platform, but one way to check is unplug, see what ports are avalible, and then plug it back in and see the new one that was added
0. Click "Tools -> Boards -> Adafruit SAMD Boards -> Adafruit ItsyBitsy M4" to set the baord
0. Click Tools -> Serial Monitor
0. To the right of the "Message" text box, there is a dropdown menu. If it says "New Line", select "Carrage Return" instead.
0. Click "Sketch -> Upload" (or press Ctrl+U or press the arrow at the top of the screen)
0. Wait a few seconds for the code to compile and upload.
0. If all goes well, the serial monitor should output something similar to the following:

        Verify successful
        System Boot Version XX
        Compiled Date => XX
        Source file => XX

        Free Memory = XX HEX or XX DEC
        Input 'T' to enter test within 15 seconds

0. You can now type a `T` and hit `<Enter>` to start test mode. If you don't hit `T` fast enough, hit the RESET button on the development board to reboot and output the prompt again.


