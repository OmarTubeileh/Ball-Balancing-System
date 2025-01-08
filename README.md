# Ball-Balancing-System
- This project is a part of Embedded Systems Lab, it is an implementation of model-based PID ball balancing system.
- The system uses an Arduino board, a servo motor, an ultrasonic sensor, and a joystick module. The ultrasonic sensor continuously measures the position of a solid ball on a track and returns the ball to its predetermined position. The ultrasonic sensor feeds back the ball’s immediate position.
- The sensor is placed at the end of the track and directed to the ball’s movement path. The servo motor is placed on a base under the track and is connected to it by a stick and flex joints to get the ability to move the track up and down until the ball returns to its position on the track.
- The ball’s distance is fed into a proportional-integral-derivative (PID) controller, which has been programmed into the Arduino. The system shall compare this distance (ball’s position) with a predetermined position to find the error. Thus, the PID compensates for this error immediately.
- The Kp, Ki, and Kd are gains were tuned manually to operate the controller correctly. The tunning is done using the Joystick module
