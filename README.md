# Legacy Talking Level
 A talking angle level based on the 328-based Arduino, the MPU6050 and the Talkie speech library.

This is a legacy project. The current iteration is in development and switches to sample-based text to speech. The Talkie library is great, but it has some limitations running on comparatively limited microcontrollers; namely its tendency to hog timers and halt code execution while it speaks. It is also time-consuming to generate LPC speech data that is intelligible, which makes adding new words, and thus new functions a challenge.

It does however have the advantage of requiring very little hardware, so I am publishing this code here for those who wish to build the talking level using software speech and to serve as an example that such a project can certainly be achieved. I still welcome contributions and will fix reported bugs.

This project was created out of my own need for a talking spirit level. The talking level is an angle level using the MPU6050 3-axis accelerometer. It can speak X, Y and Z angles, and makes a highly accurate spirit level. The software can measure angles relative to a preset angle, which turns your level into a useful angle gauge. You can toggle the speaking of angles independently, and adjust other values via a single-button settings menu. All values and settings are spoken aloud.

You can view more information along with build instructions and a detailed software change-log at [My Website](https://ashleycox.co.uk/projects/talking-spirit-level/)

