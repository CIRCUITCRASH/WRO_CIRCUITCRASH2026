# WRO_CIRCUITCRASH2026

Documentation

We are the team CircuitCrash from Serbia. This is our first time participating in the WRO Future Engineers category. Previously, some members of our team had already taken part in other categories.
Programming:
Arduino IDE, C#

Robot Construction
Main control unit:
Arduino Uno
The robot has rear-wheel drive, powered by a 12V DC motor. The front wheels are responsible for turning, which is controlled by a servo motor.
Sensors
Ultrasonic sensor that measures the distance from the edge of the track and keeps the robot at that distance on both sides.
Color sensor on the bottom of the robot that detects the blue and orange markings on the track and turns the robot accordingly.
Color sensor at the front of the robot that detects red or green obstacles and sends a signal to the control unit, which then executes the appropriate program.

PARKING EXIT
The robot starts from the parking position. When it is turned on, it checks for a magenta-colored obstacle in front of it. After detecting it, the robot uses the ultrasonic sensor to determine from which direction the signal is coming. Based on this, it starts turning and exits the parking space. After leaving the parking area, the car straightens itself and continues its path.

Open Challenge
The ultrasonic sensor mounted on the robot continuously monitors the distance from the outer wall and keeps the robot at a constant distance from it.
In the first turn, the color sensor detects the blue stripe and sends a signal to the control unit to rotate the servo motor by a specified amount. After that, the orange stripe appears, which is also detected and triggers the same type of reaction.
Changes in the inner wall do not need to be considered, because the robot always keeps a distance that allows it to avoid it while following the other wall.
After every completed turn, a counter increases by one. When the counter reaches 12 (3 laps), the vehicle stops.
Obstacle Challenge
While moving forward, if the robot detects a green obstacle, the servo motor receives a signal and begins avoiding the obstacle in the direction determined by the color. After passing the obstacle, the robot returns to the previous distance from the outer wall.
When the robot detects the blue and orange stripes marking a turn, it performs the turn in the same way as in the Open Challenge.
After every completed turn, a counter increases by one. When the counter reaches 12 (3 laps), the vehicle stops.



