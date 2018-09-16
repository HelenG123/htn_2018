# Hack the North 2018
_Introducing Mouseless_
A mouse-free browser experience
Our website can be found [here](TODO)

## Contents
TO DO:

## Setup
**1. Hardware**
   - [Leap Motion Controller](https://www.leapmotion.com/)
      - Minimum requirements includes
        - Windows® 7+, Mac OS X 10.7 Lion (legacy support)
        - AMD Phenom™ II or Intel® Core™ i3/i5/i7 processor
        - 2 GB RAM
        - USB 2.0 port
        - Internet connection


**2. Computer & Software**
   - [Leap Motion SDK v2.3.1](https://developer.leapmotion.com/sdk/v2)
   - [Gesture learning and recognition framework](https://github.com/roboleary/LeapTrainer.js)
   - [Library for backend](https://github.com/roboleary/LeapCursor.js)
   - Tested on Windows 10
   - Frontend runs on [Google Chrome](https://www.google.com/chrome/)

## Procedure

**1. Backend procedure**
  - Gestures are recorded through the Leap Motion Controller via the Leap Motion SDK v2.3.1.
  <img src="https://github.com/HelenG123/htn_2018/blob/master/media/lead_hardware.jpg" width="500">
  - Gesture are acquired and learned through the [Gesture learning and recognition framework's online user interface](https://rawgit.com/roboleary/LeapTrainer.js/master/trainer-ui.html)
    ![Alt Text](/media/leaps_trainer_gif.gif)
  - The UI provides a `.json` with the

**2. Frontend procedure**
  - TODO  : pic of our website

## Future work
We would like to implement browser extensions for the major browsers such as Google Chrome and Mozilla Firefox.
