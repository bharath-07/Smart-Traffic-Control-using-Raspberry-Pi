# Smart-Traffic-Control-using-Raspberry-Pi

Getting started:
               1.Install the sotware Raspbian Stretch in the Pi(I have used Raspberry Pi Model 3B v1.2)
                  Steps for installation:
                                         1.1 Format the SD card(use 16GB or greater,installation of software including OpenCV grabs a lot                                               of space) using the software from the given link https://www.sdcard.org/downloads/formatter/
                                         1.2 Once the formatting is complete download the Raspbian Stretch software from the given link
                                         https://downloads.raspberrypi.org/raspbian_full_latest
                                         1.3 Download and install software to burn the code into the SD card.
                                         https://www.balena.io/etcher/ (Recommended software)
                                         1.4 Now bootup the Pi by inserting the SD card
                                         1.5 Enter the username and password on bootup(Use the default username:pi Password:raspberry
                                         1.6 Set up the wifi settings.
                                         1.7 In order to use the pi using a virtual machine open Raspberry Pi configuration-->Preferences-                                             -->Interfaces--->Enable VNC Viewer . On the top right corner of the screen VNC  Symbol is                                              enabled which upon clicking it previews the IP address of the connected network.  
                                         (The above step is an extremely useful one!!!!!)
                                            1.7.1 Now download and install VNC viewer from the given link to operate the pi from a   
                                            virtual system.                                
                                         https://www.realvnc.com/en/connect/download/viewer/
                                            1.7.2 Once downloaded type the IP address of the connected pi in the VNC viewer .Now we can 
                                            operate the pi using the virtual system(basically your laptop rather than requiring a separate                                             display device,keyboard etc.
               2.Now installation of essential software is required to operate the Pi for image processing purposes.
               This is an extremely tedious process and requires lot of patience(A rough estimate of over 5 hours is required).
               I found the below link to be extremely useful in completing the process.
               https://www.pyimagesearch.com/2017/09/04/raspbian-stretch-install-opencv-3-python-on-your-raspberry-pi/
               3.Once OpenCV has been successfully installed the Pi is ready to be used.Copy and paste the contents of the folder       
               smarttraffic and paste it on the desktop of the Pi.
               4.Now use the virtualenv which was created during the installation process The below commands would suffice.
                 $ source ~/.profile
                 $ workon cv
                 $ python3 main1.py
                Note:To visualize the Traffic Light changes,ensure the GPIO pins in Pi are connected to leds on the breadboard using the pinout configuration 
               given in https://www.raspberrypi.org/documentation/usage/gpio/ .
               
               
                 
                 
                 
                                            
