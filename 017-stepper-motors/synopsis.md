## This video is about : 

Describe here what this video is about

## This video will teach the following things : 

* Introduction : You need to first watch the video about power supplies and stepper motor power input
* What is a stepper motor, how does it work
* What is a stepper motor driver, it controls a motor, smoothie controls it, you control smoothie with gcodes
* What is microstepping
* Wiring : How to correctly wire a stepper motor to the board ( pairs, and how to figure them out : datasheet, resistance, touching wires and rotating )
* There is a limit at 2A, if you need more, you need to use an external driver
* The voltage rating of the stepper motors is not important, provide 12 or 24v
* How to crimp
* Configuration : Which stepper motor driver output is which axis
* How to configure current in config, and how to figure out the right value
* How to calculate steps per mm
* How to setup the steps per mm
* How to setup the direction
* Testing : Configure and test one motor at a time
* Never connect or disconnect a motor while the power supply is powered on, it can kill the driver [ideally, demonstrate, we can send a board]
* How to test each motor
* What to do if it doesn't work

This video is not about : providing power to the stepper motor power input, this is covered in another video

## Links 

The description for this video should contain the following links : 

* http://smoothieware.org/3d-printer-guide#toc3
* http://homepage.cs.uiowa.edu/~jones/step/

Also add any other information that should be added

## Video plan

The video is composed of the following sections : 

* Introduction
* Wiring
* Configuration
* Testing
* Usage
* Troubleshooting

## Assets

Assets are pictures and videos to be displayed in the video.
Please here list and describe the various assets. They should be commited to github in this folder.

* One asset
* Another asset

## Video synopsis

Here add the text for this specific video
Introduction
-Show diagram of motor alongside interior of motor, describe how it works
-Show the difference between a Unipolar and Bipolar motor
-Discuss the wiring (4, 6, 8) and how you would pair any wires (if any)
-Explain the idea behind steps, microsteps
Drivers
-Show different types of motor drivers (A's and D's)
-Walk through the important parts (potentiometer, pins)
-WARN about orientation and difference between drivers
-Heatsink!!!
Microstepping
-Explain stepping
-Explain levels of microstepping
-Show example of how that may be set on the board
Wiring
-Which wires go where. A/A+, B/B-, how to pair connect up a 6 wire and 8 wire motor, how to make a connector using Molex or just pins
-What happens if the motor spins in the wrong direction (fix in config, flip the connector?)
-Setting the current on the stepper driver
Configuration
-Calculations needed
-Where to set in configuration file
-How to adjust the direction (tie in to the above)
Testing
-Jogging each axis, one at a time
Safety
-Always all power off, always USB removed
-Reset is not always the best way to pick up a configuration change, consider just powering down and back up

Troubleshooting
TODO


## Authors

If you contribute to this video in any way, please add your name to this list : 

* Samer Najia

