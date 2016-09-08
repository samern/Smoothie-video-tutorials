## This video is about : 

What does the USB connection do, and how to use it

## This video will teach the following things : 

* Difference between the USB and Ethernet connections
* What USB gives you
* How to wire
* How to install drivers if needed
* How to connect
* Troubleshooting

## Links 

The description for this video should contain the following links : 

* http://smoothieware.org/usb
* http://smoothieware.org/windows-drivers

Also add any other information that should be added

## Video plan

The video is composed of the following sections : 

* Introduction
* Wiring
* Driver
* Usage
* Troubleshooting

## Assets

Assets are pictures and videos to be displayed in the video.
Please here list and describe the various assets. They should be commited to github in this folder.

* One asset
* Another asset

## Video synopsis

### Introduction

You have several ways of talking to your Smoothieboard, the two main ones are Ethernet and USB.

It is recommended to use Ethernet instead of USB. 

Ethernet is more stable, while USB can have problems with communication errors and disconnections. 

This is rare, and does not happen to everybody, though, so if you want, you can try using USB.

Depending on your setup, you may even need to use USB to setup Ethernet ( to edit the configuration file and/or to find the IP address )

Just remember that if you run into disconnection problems, Ethernet will solve your issue very likely, so it should be your first thing to try.

### Wiring

Simply plug the USB cable into the Smoothieboard, and the other end of the cable into your computer {show}

A few things to be careful of to avoid USB disconnections : 

Make sure your USB cable is as short as possible ( less than 50 centimeters or two feet is ideal ), is shielded, and ideally has ferrite beads {show}.
Make sure your machine and the computer controlling it are plugged into the same power strip. {show, ideally}
Make sure your local electrical installation is not subject to variations and interference 
Make sure there are no large motors, fridges, neon bulbs or other strong sources of electrical interference in the same room.

If all of those rules are applied, USB will work fine in the vast majority of cases.

### Windows driver

If using Linux or Mac, just plug the USB cable into the computer and the Smoothieboard, and everything should work right out of the box.

If you are using Windows however, you need to install a driver.

You can find this driver at the following URL : http://smoothieware.org/windows-drivers [http://smoothieware.org/windows-drivers]

If you are using Windows 10, you do not need to install the driver, and installing the driver could cause trouble. 
For all older versions, the driver is required.

### Usage

Once the driver is installed, the Smoothieboard should be recognized both as a Mass Storage Device ( similar to a USB thumb drive ), allowing you to access the files on the SD cards {demonstrate}, as well as a Serial ( COM ) device, allowing you to send commands ( for example via Pronterface {demonstrate} ).

### Troubleshooting
If the printer controller software does not appear to recognize the Smoothie, check:
- Is there a COM port that the OS sees as the Smoothie?
- Is the baudrate too high?
- Do you have the wrong COM port (typically COM1 is NOT your printer)
- Does the COM port appear in Device Manager (Windows)?
- If running Windows 7, did the driver install properly (check Event Logs), if running Windows 10, drivers already there

If you are seeing an inability to run certain functions, it may be the baudrate, change or set to AUTO.
If you are running OctoPrint, try a full refresh if you just connected the USB (after you started the software)
If you are on OctoPrint, consider manually specifying the COM port instead of using the 'AUTO' setting
As a general rule, power up the printer, then connect the USB, then start the software.  Allow the board to initialize (a second or two) between power up and plugging into the computer

TODO?

## Authors

If you contribute to this video in any way, please add your name to this list : 

* Arthur Wolf
* Samer Najia

