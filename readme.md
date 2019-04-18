# LeapMotionProject

Steps to get this project to work on Ubuntu 16

1. Download https://github.com/BlackLight/leap-sdk-python3

2. run `sudo apt-install make g++ swig libpython3-dev android-tools-adb android-tools-fastboot` in a terminal

3. run `sudo make; sudo make install` in the directory with the make file

4. Download NewLeapMotion.py and place it in the same directory as before

5. Plug in the leap motion to a usb, open a new terminal window, and run `sudo leapd`

6. Run Cozmo on your phone in sdk mode

7. Run `python3 newLeapMotion.py`
