## Taste of Technology Lego Robotics Class Outline

ToT Lego EV3 Robotics is a three session course taught over the period of 3 weeks to students between the ages of 9 and 12. The primary goal of the course is to introduce basic programming and robotics concepts to students who show an interest and who may not have had prior exposure. This outline provides a list of materials and curriculum needed to lead the course.

### Course Materials for ToT Robotics

*	[Riley Rover](http://www.damienkee.com/home/2013/8/2/rileyrover-ev3-classroom-robot-design.html) (built from the [LEGO Mindstorms Education Kit](https://shop.education.lego.com/legoed/en-US/search/navSearchResults.jsp?categoryId=EDU_PRD_LINE_107&ProductLine=MINDSTORMS+Education+EV3))
*	Low Power Laptop or Desktop Computers
*	EV3 Code Included in this Repository - *note, code is provided for both computer and iPad platforms. Switching platforms mid-session is not recommended.*

Optionally teachers may wish to use the [Sirius (FLL Robot)](http://builderdude35.com/downloads-2/) model to teach this course since this model is a little better known than the Riley Rover thanks to FIRST LEGO League. To use this model, small modifications to the base programs will be required. Most importantly, the large motors will need to have their power levels multiplied by -1 as the Sirius motors are "upside-down". Less experienced users are probably best served by the Riley Rover model.

### Course Outline

#### Session One
**Goals**: Introduce the LEGO Software, Introduce Motors and Speakers (output), Introduce Loops

**Programs**

1.	[Hello World](docs/hello.md)
2.	Sound
3. 	Motors

**Session Guide**

1.	Start by demonstrating the IDE. Specifically, walk through
	*	Launching the LEGO programming environment
	*	Starting a new program
	*	The Start Block and block types
	*	Editing a block
2.	Show hello and sound programs and have the students replicate and test. Make sure that the students are able to upload and execute the program on their own. They may either upload the program, disconnect the robot, and use the robot's menu to run the program OR they may leave the robot connected to the computer and run the program from the IDE using the "play" button.
3.	Demonstrate motors and have the students replicate and test the right angle program.
4.	Thought Experiment: Code a Square (Right angle program four times)
5.	Demonstrate loops and have the students replicate the square program.

**Stretch**

1.	Modify the square code to draw a triangle.
2.	Write a new program that will have the robot go in a circle with one block.
3.	Do any of the earlier programs so that the robot runs backwards.

#### Session Two
**Goals**: Introduce Color and Ultrasonic Sensors (input), Introduce Switch Blocks (Conditional Statements)

**Programs**

1.	InAndOut.ev3
2.	AvoidWalls.ev3

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
**Goals**: Demonstrate learning by independantly coding a solution for line following problem.

**Programs**

1.	AdvancedLogic.ev3

**Session Guide**

1.	Review inputs and outputs. Focus on motors (output) and color sensor (input).
2.	Review the switch and loop logic blocks.
2.	Show LEGO Test Mat
3.	Demonstrate line following behavior (by pretending to be a robot; talk about what is being processed)
4.	Assign the students the task of creating a line following robot. List the blocks that will be needed.
	1. Start Block
	2. Loop  Block
	3. Switch Block
	4. Motor Block
5.	During the coding process talk about build and test iterations.
