Electromechanical diagrams
====

This diagram illustrates the wiring and components configuration of our robot
Central Unit:
EV3 Brick
Input Ports (1-4)
- Port 1: Pixy Camera
- Port 2: Right LEGO Ultrasonic Sensor - Port 3: Left LEGO Ultrasonic Sensor - Port 4: Gyro Sensor Pixy Camera Output Ports (A-D)
- Port A: Rear Wheel Motor
- Port B: Steering Wheel Motor
Components:
Our bot consists of the following components: - LEGO Mindstorm EV3 Brick
- LEGO Rechargeable DC Battery
- EV3 Medium Servo Motor
- LEGO Ultrasonic Sensors
- LEGO Gyro Sensor
- PIXY 2.1 Camera
- Lego Cables
- Russian Wheels
- Steering Wheels
  
LEGO Mindstorm EV3 Brick:
The EV3 Brick is the central control unit of our robot. It features a programmable interface with a display screen and buttons for manual control. It is programmed using LEGO's Mindstorm software. It has 4 ports for Input and output, currently, our bot uses 2 output ports for both medium motors and 3 input ports for 2 ultrasonic sensors and gyro sensors.
LEGO Rechargeable DC Battery:
This 2000 mAh battery provides power to the EV3 Brick and other components. It is rechargeable and designed to fit into the EV3 Brick.
### EV3 Medium Servo Motor
The medium servo motor is used for precise movements and rotations. It is smaller in size compared to the large motor and is capable of rotating 360 degrees with precise angle control, useful for the steering mechanism.
LEGO Ultrasonic Sensors:
These sensors are placed on both sides of the robot and measure the distance between the wall and the robot by emitting ultrasonic waves and measuring the time it takes for the waves to return. It's useful for obstacle detection and open-round challenge.
LEGO Gyro Sensor:
The gyro sensor mounted on top measures the rate of rotation around the sensor’s axis. It helps in precise robot movement, detecting orientation changes, and stabilizing movements, which is crucial for our robot’s journey.
Pixy 2.1 Camera:
The PIXY 2.1 Camera is an advanced vision sensor that can detect and track objects based on color. It provides real-time image processing capabilities and is used for object detection in obstacle challenge.
LEGO Cables:
These cables help in building connections between motors, and sensors to the EV3 Brick. They are responsible for transmitting power and data between the components and EV3 Brick.
### LEGO Russian Wheels (62.4 x 20)
These wheels are used as rear wheels in our robot. These wheels are 62.4 mm in diameter and 20 mm in width.
LEGO Tractor Wheels (56 x 26):
These wheels are used as front wheels in our robot. These wheels are 56 mm in diameter and 26 mm in width.

Rack & Gear:
We designed a **custom 7.2 cm rack** with a similar **groove pattern** and design as the standard **6.4 cm LEGO rack**. The original 6.4 cm LEGO rack had some problems wherein its shorter length made it **difficult to mesh smoothly** with the **20-tooth double bevel black LEGO gear**, which restricted the wheels from achieving **specific steering angles**.
However, even with our 7.2 cm rack, we encountered a minor issue: the grooves of the black LEGO gear and our custom rack weren’t perfectly meshing. While it functioned temporarily, the meshing wasn't ideal, and the **error compounded by 0.01 with each turn**. To overcome this, we also created a **custom 12 tooth gear** whose grooves are perfectly meshing with custom rack thus **eliminating meshing errors** and significantly **improved the accuracy of the steering**, allowing the wheels to turn at precise angles.
