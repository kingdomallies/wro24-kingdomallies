WRO Future Engineers Team Kingdom Allies Engineering Documentation
====

## Content
* `build` contains documentation about our chassis and material choice
* `schemes` contains schematic diagrams demonstrating the connections between different electromechanical components. It also includes the available datasheets for the aforementioned components, and it also has a markdown file explaining the reasoning for each component.
* `models` contains the files used by 3D printers to produce the vehicle elements.
* `photos` contains two folders where one contains the team photos and the other contains the robot photos
* `src` contains the code of control software for all components that were programmed to participate in the competition
* `strategy` contains documentation and diagrams explaining our approach to the problem
* `video` contains the video.md file with the link to a video where the driving demonstration exists

## Rubric Requirements
* `Mobility Management` is found in `build`, `schemes`, and `models`
* `Power and Sense Management` is found in `schemes`
* `Obstacle Management` is found in `strategy` and `src`
* `Pictures - Team and Vehicle` is found in `photos`
* `Performance Videos` is found in `video`
* `Engineering Factor` is found in `build` and `README`


### Who We Are
Kingdom Allies is a driven group of high school students with the ambition to become future leaders in the field of autonomous vehicles. By actively participating in the WRO Future Engineers challenge, we are seizing the opportunity to develop our skills in engineering and problem-solving, preparing ourselves for the innovations of tomorrow.
- Deepen our understanding of autonomous vehicle technology.
- Gain hands-on experience with software organization tools, such as GitHub.
- Develop proficiency in working with electronic components.
- Learn to collaborate effectively as a team, solving problems with innovation and creativity.


### Electrical Components
Our chassis is controlled by the Arduino Nano microcontroller, which gets information from various sensors and uses said information to control the motors using an L298N motor controller board. The sensors that we are using for our vehicle are the following:
- LEGO Mindstorm EV3 Brick
- LEGO Rechargeable DC Battery
- EV3 Medium Servo Motor
- LEGO Ultrasonic Sensors
- LEGO Gyro Sensor
- PIXY 2.1 Camera
- Lego Cables
- Russian Wheels
- Steering Wheels

##### LEGO Mindstorm EV3 Brick:
The EV3 Brick is the central control unit of our robot. It features a programmable interface with a display screen and buttons for manual control. It is programmed using LEGO's Mindstorm software. It has 4 ports for Input and output, currently, our bot uses 2 output ports for both medium motors and 3 input ports for 2 ultrasonic sensors and gyro sensors.
##### LEGO Rechargeable DC Battery:
This 2000 mAh battery provides power to the EV3 Brick and other components. It is rechargeable and designed to fit into the EV3 Brick.
##### EV3 Medium Servo Motor
The medium servo motor is used for precise movements and rotations. It is smaller in size compared to the large motor and is capable of rotating 360 degrees with precise angle control, useful for the steering mechanism.
##### LEGO Ultrasonic Sensors:
These sensors are placed on both sides of the robot and measure the distance between the wall and the robot by emitting ultrasonic waves and measuring the time it takes for the waves to return. It's useful for obstacle detection and open-round challenge.
##### LEGO Gyro Sensor:
The gyro sensor mounted on top measures the rate of rotation around the sensor’s axis. It helps in precise robot movement, detecting orientation changes, and stabilizing movements, which is crucial for our robot’s journey.
##### Pixy 2.1 Camera:
The PIXY 2.1 Camera is an advanced vision sensor that can detect and track objects based on color. It provides real-time image processing capabilities and is used for object detection in obstacle challenge.
#####LEGO Cables:
These cables help in building connections between motors, and sensors to the EV3 Brick. They are responsible for transmitting power and data between the components and EV3 Brick.
##### LEGO Russian Wheels (62.4 x 20)
These wheels are used as rear wheels in our robot. These wheels are 62.4 mm in diameter and 20 mm in width.
LEGO Tractor Wheels (56 x 26):
These wheels are used as front wheels in our robot. These wheels are 56 mm in diameter and 26 mm in width.
##### Rack & Gear:
We designed a **custom 7.2 cm rack** with a similar **groove pattern** and design as the standard **6.4 cm LEGO rack**. The original 6.4 cm LEGO rack had some problems wherein its shorter length made it **difficult to mesh smoothly** with the **20-tooth double bevel black LEGO gear**, which restricted the wheels from achieving **specific steering angles**.
However, even with our 7.2 cm rack, we encountered a minor issue: the grooves of the black LEGO gear and our custom rack weren’t perfectly meshing. While it functioned temporarily, the meshing wasn't ideal, and the **error compounded by 0.01 with each turn**. To overcome this, we also created a **custom 12 tooth gear** whose grooves are perfectly meshing with custom rack thus **eliminating meshing errors** and significantly **improved the accuracy of the steering**, allowing the wheels to turn at precise angles.




# wro24-kingdomallies" 
"# wro24-kingdomallies" 
