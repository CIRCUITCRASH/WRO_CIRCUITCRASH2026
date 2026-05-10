# WRO_CIRCUITCRASH2026

Documentation

We are the CircuitCrash team from Serbia. This is our first time participating in the WRO Future Engineers category. Previously, some members of our team had already competed in other categories.

Programming:
We use EV3 Classroom for programming. The main control unit of the robot is an EV3 brick. The robot has rear-wheel drive powered by a large servo motor. The front wheels are responsible for steering, which is controlled by a servo motor.

About the robot:
The robot uses several sensors. The ultrasonic sensor measures the distance from the edge of the track and keeps the robot at a constant distance from it on both sides. The color sensor located on the bottom of the robot detects the blue and orange markings on the track and turns the robot accordingly. Another color sensor located at the front of the robot detects red or green obstacles and sends a signal to the control unit, which then executes the appropriate program.

The robot starts from the parking position. When it is turned on, it checks whether there is a magenta-colored obstacle in front of it. After detecting it, the robot uses the ultrasonic sensor to determine from which direction the signal is coming. Based on this information, it starts turning and exits the parking space. After leaving the parking area, the car straightens itself and continues its path.

Open Challenge
During the Open Challenge, the ultrasonic sensor mounted on the robot continuously monitors the distance from the outer wall and keeps the robot at a constant distance from it. In the first turn, the color sensor detects the blue stripe and sends a signal to the control unit to rotate the servo motor by a specified amount. After that, the orange stripe appears, which is also detected by the system and triggers the same type of reaction. Changes in the inner wall do not need to be considered because the robot always keeps a distance that allows it to avoid it while following the other wall. After every completed turn, a counter increases by one. When the counter reaches 12, meaning 3 laps, the vehicle stops.

Obstacle Challenge
During the Obstacle Challenge, if the robot detects a green obstacle while moving forward, the servo motor receives a signal and begins avoiding the obstacle in the direction determined by the color. After passing the obstacle, the robot returns to the previous distance from the outer wall. When the robot detects the blue and orange stripes marking a turn, it performs the turn in the same way as in the Open Challenge. After every completed turn, a counter increases by one. When the counter reaches 12, meaning 3 laps, the vehicle stops.



