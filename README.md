## Taste of Technology LEGO Robotics Class Outline

ToT LEGO EV3 Robotics is a three session course taught over the period of 3 weeks to students between the ages of 9 and 12. The primary goal of the course is to introduce basic programming and robotics concepts to students who show an interest and who may not have had prior exposure. This outline provides a list of materials and curriculum needed to lead the course.

### Course Materials for ToT Robotics

*	[Riley Rover](http://www.damienkee.com/home/2013/8/2/rileyrover-ev3-classroom-robot-design.html) (built from the [LEGO Mindstorms Education Kit](https://shop.education.lego.com/legoed/en-US/search/navSearchResults.jsp?categoryId=EDU_PRD_LINE_107&ProductLine=MINDSTORMS+Education+EV3))
*	Low Power Laptop or Desktop Computers
*	EV3 Code Included in this Repository - *note, code is provided for both computer and iPad platforms. Switching platforms mid-session is not recommended.*
* [Troubleshooting Guide](docs/troubleshooting.md)

Optionally teachers may wish to use the [Sirius (FLL Robot)](http://builderdude35.com/downloads-2/) model to teach this course since this model is a little better known than the Riley Rover thanks to FIRST LEGO League and Kyle Markland a.k.a. [BuilderDude35](http://builderdude35.com). To use this model, small modifications to the base programs will be required. Most importantly, the large motors will need to have their power levels multiplied by -1 as the Sirius motors are "upside-down". Less experienced users are probably best served by the Riley Rover model.

### Course Outline

#### Session One
**Goals**: Introduce the LEGO Software, Introduce Motors and Speakers (output), Introduce Loops

**Programs**

1.	[Hello World](docs/hello.md)
2.	[Sound](docs/sound.md)
3. 	[Motors](docs/motors.md)

**Session Guide**

1.	Start by demonstrating the IDE. Specifically, walk through
	*	Launching the LEGO programming environment
	*	Starting a new program
	*	The Start Block and block types
	*	Editing a block
*Note*: New users should watch the [Getting Started on Your PC/MAC](https://www.lego.com/en-us/mindstorms/learn-to-program) video.

2.	Show [Hello World](docs/hello.md) and [Sound](docs/sound.md) programs using a projector or printout and have the students copy and run the program. Make sure that the students are able to upload and execute the program on their own. They may either upload the program, disconnect the robot, and use the robot's menu to run the program OR they may leave the robot connected to the computer and run the program from the IDE using the "play" button.
3.	Review [Motors](docs/motors.md) and have the students replicate and run the *Right Angle* program.
4.	Thought Experiment: How could a programmer use the *Right Angle* code to make a robot trace out a square? (Answer: run the right angle program four times).
5.	Demonstrate loops and have the students replicate the *Square Program*.

**Stretch**

1.	Modify the square code to draw a triangle. (Think about the number of sides and the degrees in each angle of and equilateral triangle).
2.	Write a new program that will have the robot go in a circle with one block.
3.	Do any of the earlier programs so that the robot runs backwards.

#### Session Two
**Goals**: Introduce Color and Ultrasonic Sensors (Input), Introduce Switch Blocks (Conditional Statements)

**Programs**

1.	[Input and Output](docs/inandout.md)
2.	[Avoid Walls](docs/avoidwalls.md)

**Session Guide**

1. 	Warm up with quick walkthrough and copy of Output program in InAndOut
2.	Discuss the difference in input and output with examples. Ask students to give additional examples.
3.	Review the logic (switch block) and have students replicate the Input and Output program in InAndOut.
4.	Discuss the behavior of wall avoidance.
5.	Have the students troubleshoot the broken avoid walls program.

**Stretch**

1.	Review the logic and have students replicate the Distance program in InAndOut.
2.	Discuss what input and outputs were used in this sessions programming.

#### Session Three
**Goals**: Demonstrate learning by independently coding a solution for line following problem.

**Programs**

1.	[Line Follower](docs/advancedlogic.md)
2.	[Distance Test](docs/distancetest.md)

**Session Guide**

1.	Review inputs and outputs. Focus on motors (output) and color sensor (input).
2.	Review how the switch and loop logic blocks work.
2.	Show LEGO Test Mat paying special attention to the black oval line.
3.	Demonstrate line following behavior by pretending to be a robot; talk about what is being processed. If you're not familiar with line following behavior read the [Line Follower guide](docs/advancedlogic.md) before leading this lesson.
4.	Assign the students the task of creating a line following robot. List the blocks that will be needed.
	1. Start Block
	2. Loop  Block
	3. Switch Block
	4. Motor Block
5.	During the coding process talk about build and test iterations.
6.	If the students run out of time you can share the preprogrammed solution and talk through the code so that everyone understands the process.

 **Stretch**

 1.	Discuss math blocks and how they can be used to make a robots actions more precise. Discuss and run the exercise in the [Distance Test guide](docs/distancetest.md).
