##Obstacle Management

This code demonstrates EVENTS and their use in creating complex behavior. Older student may appreciate a small introduction to the concept of threads and multi-threaded application development but it is not needed for this exercise.

###Behavior

When executed the robot will turn the onboard LED green and start to move forward. In the event of a collision the robot will turn red and alter it's heading before proceeding.

###Events

There are four events. These are,

*	On Collision
*	On Freefall
*	On Land
*	On Gyro Max

This application uses the On Collision event. On Collision will define the logic to follow when a collision is detected. In our application, that code sets the color to onboard LED to red and updates the heading. Once executed the On Start Program (which is a kind of special event) resumes.