## Distance Test - Math Block Introduction
This program demonstrates the use of math to drive precise robot behavior. In this exercise, the students are required to drive their robot a predetermined distance without using trial and error. In order to make this calculation the students will need to know the circumference of their robots drive wheels and the distance their robot is required to travel. By dividing the distance to travel by the wheel circumference we can get the number of rotations each wheel has to make.

We can represent this formula as,

<p align="center"><img src="https://github.com/DaveKT/ToT-Robotics-EV3/raw/master/docs/wheelrotationsformula.png" alt="Image of Rotations Formula" style="width: 380"/></p>

For our example code below, the distance to travel {a} is 36 inches and the wheel circumference {b} is 6.875. This results in the following,

<p align="center"><img src="https://github.com/DaveKT/ToT-Robotics-EV3/raw/master/docs/rotationscalculation.png" alt="Image of Rotations Calculation" style="width: 380"/></p>

After performing the calculation, the red math block passes its result to the rotations parameter of the motor block. To change the distance to travel, simply update the value in the {a} parameter of the red block. *Note: the values here are in inches but you can use any units of length as long as the units are the same in both {a} and {b}.*

Riley Rover Wheel Circumference: 6.93"
Sirius Wheel Circumference: 11.65"

You can perform the calculations manually using the [EV3Lessons Wheel Converter](http://ev3lessons.com/resources/wheelconverter/).


### Code

<img src="https://github.com/DaveKT/ToT-Robotics-EV3/raw/master/docs/ev3/DistanceTest.png" alt="Image of Program Code" />

[Download the EV3 Code](docs/ev3/DistanceTest.ev3)

*Distance Test program not possible in iPad IDE*

### Behavior
The software drives the robot a specific distance {a} by calculating wheel rotations needed based on the wheel's diameter {b}.
