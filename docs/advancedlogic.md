## Advanced Logic - Line Follower
This session challenges the students to develop a simple line following behavior for their robot. The task is accomplished using the color sensor to detect the present of a line edge and update it's course based on its sensor's feedback. Students will use the programming skills they've required through the previous exercises. A full walk through of the code is below in the Behavior section.

### Code

<img src="https://github.com/DaveKT/ToT-Robotics-EV3/raw/master/docs/ev3/AdvancedLogic.png" alt="Image of Program Code" />

[Download the EV3 Code](ev3/AdvancedLogic.ev3)

[View the iPad Code pt 1](ev3ipad/iPadLineFollower.jpeg)

[View the iPad Code pt 2](ev3ipad/iPadLineFollower2.jpeg)


### Behavior
The robot follows a dark (continuous) line around using the color sensor to detect the edge if the line and a switch block to steer the robot. The program executes the following steps.

1. Color sensor measures reflectivity (switch block)
    1. If the reflectivity is low (false), the robot is directly over the line and should steer slightly forward and away from the line.
    2. If the reflectivity is high (true), the robot is off the line and should steer slightly forward and towards the line.
2. Repeat loop forever

*Note: The example program is written so that the robot will follow the inside edge of a line (if the line is a tracing a circle). If you'd prefer your robot to follow the outside edge swap the position of the motor blocks so that the robot goes left when reflectivity is high and right when reflectivity is low.*
