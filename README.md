# Rock-Paper-Scissors-Haptic-Glove

This repository has 3 codes written in Python3 and deployed on a Raspberry Pi 3.  These codes interface with a MPU6050 accelerometer/gyro and the ADS-1115 analog to digital converter.  

Accelerometer Testing: This code gathered data from all 6 axes of the IMU (3 from accelerometer, 3 from gyroscope).  It then stores those values constantly for a fixed amount of time.  After all the data has been gathered, we use matplotlib to plot and format the data, such that we can view all the axes on a single plot.  

Sensor Plotting:  This code gathers data from 2 separate sensors that are both communicating via a I2C line.  One I2C line for gathering motion data and the other I2C ine for gathering gesture data.  We plot both of these sensor data on a single plot versus time in order to visualize the timing requirements for my detection algorithm.  

RPS Final Working Code:  This code allows a player to play Rock, Paper, Scissors against a 3D printed robotic hand.  This code combines motion detection and gesture detection algorithms to successfuly track a players movements and score while playing Rock, Paper, Scissors.  
