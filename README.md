## Taste of Technology Sphero Robotics Class Outline

ToT Sphero Robotics is a four session course taught to students between the ages of 9 and 12. The primary goal of the course is to introduce technical concepts to students who show an interest and who may not have had prior exposure.

### Course Materials for ToT Robotics

*	[Sphero or Ollie Robots](http://store.sphero.com)
* [SPRK Lightening Lab Software](http://www.sphero.com/education)
*	[Compatible iPad, iPhone, or iPod Touch](https://sphero.zendesk.com/hc/en-us/articles/204211154)
*	Sphero SPRK Lightening Lab Code Included in this Repository

## Course Outline

### Week One
**Goals**: Introduce the SPRK Software, Introduce Loops, Introduce Motor Control, Introduce IF THEN ELSE

**Programs**

All example program files are in the [ToT_Robotics_Sphero](https://github.com/DaveKT/ToT-Robotics-Sphero/tree/master/docs/Examples) repository on GitHub.

1.	[ColorMe](docs/Examples/ColorMe.md)
2.	[LightShow](docs/Examples/LightShow.md)
3.	[GoingTheDistance](docs/Examples/GoingTheDistance.md)
4.	[Degrees](docs/Examples/Degrees.md)

**Session Guide**

1.	Show the students the Ollie and Sphero Robots. If the class is calm demonstrate how the Ollie and Sphero and move when on the floor using the simple remote software for each.
2.	Show the students the SPRK Lightning Lab Software. Be sure to highlight how to start a new program, the tabs with the different kind of command blocks, how to add a block to a program, how to edit a block's parameters, and how to delete a block from a program.
3.	Have the students copy the [Color Me](docs/Examples/ColorMe.md) program. Tell them to set the color to red. After they run that program tell them to set the color to whatever color they'd like.
4.	Discuss the concept of loops. There is more information about loops in the [Light Show exercise](docs/Examples/LightShow.md).
5.	Have the students copy the LightShow program and review the lesson listed in the LightShow markdown files once the assignment is completed.
6.	Review the concepts listed in the [Going The Distance exercise](docs/Examples/GoingTheDistance.md).
7.	Ask the students to play the Going the Distance game outline in the GoingTheDistance markdown file.

**Stretch**

1.	Review the basic geometry of a circle including 360° reference. Discuss the concept of heading 0° is facing straight ahead, 90° is right, 180° is facing back, -90° or 180° is facing left. *Note in Spheroland they use the negative values.*
2.	Discuss the concept of pitch, roll, and yaw. There is a very good explanation if you need to review on the [Smithsonian's How Things Fly](http://howthingsfly.si.edu/flight-dynamics/roll-pitch-and-yaw) site. Suggestion, when reviewing this concept with students hold up the robot and rotate it around the various axes. Do not share the web page since we're not discussing flight, just the axis of rotation.
3.	Discuss IF, THEN, ELSE statements. There is more information about this statement in the [Degrees](docs/Examples/Degrees.md) markdown file.
4.	Have the students code the [Degrees](docs/Examples/Degrees.PNG) program in the SPRK Lightning Lab.

### Week Two
**Goals**: Introduce additional sensors and readings, control the Sphero or Ollie using motors.

**Programs**

All example program files are in the [ToT_Robotics_Sphero](https://github.com/DaveKT/ToT-Robotics-Sphero/tree/master/docs/Examples) repository on GitHub.

1.	[SquareDance](docs/Examples/SquareDance.md)
2.	[ObstacleManagement](docs/Examples/ObstacleManagement.md)

**Session Guide**

1. Review the degrees in a circle and how they relate to the Sphero. For reference you may wish to display or hand out the [Ollie Degrees diagram](https://github.com/DaveKT/ToT-Robotics-Sphero/raw/master/docs/Resources/Ollie%20Degrees.png). Important note about the reference. Spheros operated in a fixed coordinate system. This means that, once aligned, each degree in the circle represents a fixed direction from the point of view of the operator or programmer, not Ollie. 0˚ is always directly away from the operator. 90˚ is always to the operator's right, etc.
2. Ask the students what steps are required to make a robot navigate in the shape of a square. The response should include something along the lines of move forward (0˚) for some period of time, turn left (270˚)…
3. Once the students have required the steps required to trace out a square, have them duplicate the code in the [Square Dance Exercise](docs/Examples/SquareDance.md).
4. Explain that sometime our robotics can run into the unexpected. As a result, programmers need a way to "handle" any "exceptions" to normal operating. Have the students copy the code in the [Obstacle Management exercise](docs/Examples/ObstacleManagement.md). Point out that the "On Collision" part of the program will only run if the robot runs into something.

**Stretch**

1. Have the students describe the steps needed to trace out a triangle. Have them modify the Square Dance program to trace a triangle and run the program. If it didn't work the first time, review the code and try again.
2. Draw a more complex shape. Try a hexagon or a circle. Which is easier to program? Why?

### Week Three
**Goals**: Solve navigational problems that require the student to apply what they have learned about absolute position within a 360˚ reference.

**Programs**

All example program files are in the [ToT_Robotics_Sphero](https://github.com/DaveKT/ToT-Robotics-Sphero/tree/master/docs/Examples) repository on GitHub.

1.	[Figure Eight](docs/Examples/FigureEight.md)
2.	[Cones](docs/Examples/Cones.md)

**Session Guide**

1.	Conduct a very brief review of the geometry of a circle,
    * 0˚ is straight ahead
    * 90˚ is right
    * 180˚ is back
    * 270˚ is left
2.	Introduce the concept of the arc.
3. Have the students copy and run the Figure Eight program. Note that the spin blocks in this program are set to 360˚, full circles.
4. Have a brief discussion about the number of degrees in a half circle and full circle. (Review ahead of time, but do not share with the students, the Cone program.)
5.	Set out four or five "Cones" and challenge the students to write a program similar to the Figure Eight program that will navigate the cones.

**Stretch**

1.	Assuming the students were able to navigate through the cones, challenge the students to extend the program to turn the robot around and come back.

### Week Four
**Goals**: Using the information presented during this session, program an Ollie to navigate a maze.

**Programs & Materials**

1.	Course Construction Materials - Can be anything that will lay out the outline of a "race course" (e.g. pool noodles, painter's tape, wooden blocks, etc).

**Session Guide**

1.  Prior to class set up a course sized for the Ollie or Sphero robot. The course should have at least four total turns that required changes in direction. For simpler mazes keep the number of turns low and make sure all turns are 90˚ or 270˚. For more complex mazes you can set up turns that are any number of degrees (not just simple left or right turns). The course does not need to start and end in the same spot.
2.  Once class begins, have the students break out into small teams (2 or 3 is ideal) and write a program that will steer their robot through the course. For teams that finish first, have them try to turn around at the end and come back.

**Stretch**

1. Talk to the students about any trouble they had running the course. Do they think that their programs could handle unexpected events?
2. Select the two best performing robots and have them run the course at the same time (both start on the start line and begin navigating the maze simultaneously). What happened? What things could be changed to make the robots run more smoothly?


### Alternate Material

#### Ollie Sled
The Ollie sled can be attached directly to Ollie to enable the robot to pull light loads. The instructor may choose to use this attachment to run experiments (e.g. how much weight can Ollie pull with different power settings, how is traction affected by a trailing load, etc) or it can be used as an incentive to complete other coursework (e.g. the instructor could hold "chariot" races.)

The sled attaches to Ollie via large rubber band. The sled is built with LEGO technic parts using these [instructions](docs/Resources/OllieSled.pdf). A list of parts for the sled is [here](docs/Resources/OllieSled.xlsx).
