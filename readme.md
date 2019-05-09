# LeapMotionProject

If you do not have Ubuntu-

On Windows- Install ubuntu in a Virtual Box and enable USB 2.0 Passthrough

Steps to get this project to work on Ubuntu 16

1. Download https://github.com/BlackLight/leap-sdk-python3

2. run `sudo apt-install make g++ swig libpython3-dev android-tools-adb android-tools-fastboot` in a terminal

3. run `sudo make; sudo make install` in the directory with the make file

4. Download NewLeapMotion.py and place it in the same directory as before

5. Navagate to https://www.leapmotion.com/setup/desktop/linux/ and download and set up leapmotion on ubuntu.

6. Plug in the leap motion to a usb, open a new terminal window, and run `sudo leapd`

7. Make sure that when you run `ADB devices` in a terminal your phone shows up if its plugged in

8. Run Cozmo on your phone in sdk mode

9. Run `python3 newLeapMotion1.py`
