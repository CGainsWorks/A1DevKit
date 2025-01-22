# A1DevKit
Bionic Arm Development Kit

License:
CC BY-NC

BOM:
Thin Small Push Switch e.g. Momentary Tactile Push Button for PCB i.e. Omron Plunger Tactile Switch, SPST 50 mA @ 24 V dc 6.1mm Through Hole
RGB LED (Avoid Youmile)
5x AGFRC A20 CLS Servo
1/8 Inch Flat Elastic or Equivalent
Electrical Wire (Thin and Small Guage is OK), Solder
Superglue
Fishing Wire or equivalent
PCA9685
DFR0564
Walfront EMG Signal Sensor (For development can switch to Myoware Sensor or others like Thalmic Labs Myo Armband or OpenBCI EMG sensor or Shimmer3 EMG/EXG sensor)
MAX1044
Arduino Nano (For development can switch to ESP32)
LiPo Battery 7.4V
2x 10u Capacitor
Toggle Switch
M4 Nuts & Bolts

Tools:
Soldering Iron
Wire Cutters
3D Printer
Tweezers
Philips Head Screw Driver
Slotted (Minus) Head Screw Driver

Instructions:
Make PCB according to schematic
Solder components according to schematic except LED, push switch and servos
3D print parts
Solder wires to led, push swith and servo
Assemble button andput wires through top hand part
Tie the fishing wire to servo spline and attach to servo (Note. first set servo to 0 degrees through the 5ServoSet program or equivalent)
Put servos into hand and put servo wires and button (push switch and LED wires) through wrist and attach to PCB
Assemble fingers but do not yet connect the elasitc and fishing wire
Assemble hand, making sure to put wrist and fingers into slot first before assembling top hand part to the rest
Assemble 2 halves of the forearm and put wrist into slot of the bottom half, the bottom half is the one with the PCB platform, and the wrist should point downwards
Put PCB into the platform
Assemble the stand, use it to make it easier to test the opening and closing of the fingers
Assemble the 2 arm halves together, NOTE: Test electronics first with the 5ServoSetWLED code to test button functionality and 5ServoSpeed to test the servo functionality - the fingers should bend opening and closing the hand
Assemble the arm case parts using magnets to the arm

Special thank you to anyone who wants to add to this open source project.
