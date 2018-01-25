# FitnessMonitor
Fitness Monitor Device Code
The fitness monitor device is a device that consists of two Teensy microcontrollers, an IMU, a Wifi module, a heart sensor,
an SD card reader, and a GPS module. The device uses the heart sensor to measure the heart rate of the person wearing it, the
GPS module to measure distance traveled and mile pace, the wifi module to transmit this information to a webpage for the user
to access, as well as to obtain the time of day for the user, the SD card reader to store information for the user as well as
several other accounts on the same device, and the IMU to measure the total steps traveled. The first Teensy does all the
computations for the previously mentioned functions in LifeMonitor1.ino. The second Teensy is what communicates with the user
all this information verbally in LifeMonitor2.ino. Several voice recordings were made and stored in the SD card. The second Teensy
retrieves information from the first Teensy, uses the voice recordings in the SD card, and constructs sentences that the user can
hear via earphones. This was a final project for college.
