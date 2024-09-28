## Strategy for Autonomous RC Car  

WRO Future Engineers Open Challenge
Project Overview

This project aims to develop an autonomous RC car for the WRO Future Engineers Open Challenge. The car will navigate a course with turns, using ultrasonic sensors for wall detection and a gyro sensor for angle measurement. The goal is to complete three laps around the course, with precise 90-degree turns at each corner, controlled by a PID system.
Components
Ultrasonic Sensors: Two ultrasonic sensors will be mounted on the left and right sides of the car to detect walls and determine when to take a turn.
Gyro Sensor: A gyro sensor will measure the car’s angular orientation, helping determine the angle of each turn (90 degrees) and ensuring the car moves straight using PID control.
PID Controller: The PID (Proportional, Integral, Derivative) control will be used to maintain a straight trajectory after each turn.
Strategy for Course Navigation

## 1. Initial Movement and Setup
Forward Movement with Gyro PID: At the start, the car will move forward using the gyro sensor and a PID controller to ensure it moves in a straight line.
ultrasonic Value Monitoring: The car will monitor the average of the ultrasonic sensor values during this forward movement. The car will continue moving forward until the average ultrasonic value exceeds 80 degrees.
## 2. Detecting Turns Using Ultrasonic Sensors
Turn Detection Logic: The ultrasonic sensors will be used to detect the absence of a wall, indicating it's time to make a turn.
If one of the sensors detects no wall (high value), it means the car is approaching a corner.
By subtracting the values of the left and right ultrasonic sensors, the car will determine which direction to turn:
If the result is positive, it indicates that the right side detected the absence of a wall, meaning the car needs to turn right.
If the result is negative, it means the left side detected no wall, and the car will turn left.
## 3. Pre-determined Turn Direction
Initial Direction Check: At the start of the run, the car will perform a quick check of the direction to turn (left or right) based on the initial readings from the ultrasonic sensors.
This initial check will allow the car to store the general direction of turns for the rest of the laps.
By storing this direction, the car won’t have to recheck which side to turn each time it reaches a corner, reducing the chance of incorrect turn values during the run.
## 4. Executing Turns
90-degree Turns with Gyro: When it’s time to turn, the car will use the gyro sensor to execute a precise 90-degree turn. The angle will be controlled through a feedback loop using the gyro sensor to ensure the turn is accurate.
Straight Movement After Turn: After each turn, the car will again use the gyro sensor and PID control to ensure it moves in a straight line until it reaches the next corner.
## 5. Looping Through Laps
Loop for 3 Laps: The car will follow this strategy to complete 12 turns or 3 laps around the course, repeating the turn detection and execution process at each corner with updating the counter to know how many turns are completed and end when 12th turn is done. The pre-determined turn direction will guide the car without needing to recheck the sensors each time.
Conclusion
This strategy focuses on using sensor-based decision-making to navigate the course efficiently. The initial direction check simplifies the process by storing the turn direction, while the combination of ultrasonic sensors and the gyro sensor ensures that the car can handle both turns and straight movement with accuracy. By utilizing PID control, the car will maintain its straight trajectory and complete the course in the most efficient manner.
