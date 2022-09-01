# Turtlesim-GoTo-Controller-ROS-Project
## Description
It's a Package containing more than one project to control a turtle in turtlesim simulator 

**draw_circle.py**
> It controls the turtle in a way that it is able to move angular wise and draw complete circles
It's a Goto controller for Turtlesim Simulator where you can give it certain coordinates and it shall go alone to this goal and stops at it.

**turtle_controller**
> It controls the turtle in a way that it is able to move anywhere inside the squares but never hits the walls, and makes the line color of the turtle steps in the rightside different from the left side of the screen.

**Turtle_Goto_Controller_Task**
> It's a Goto controller for Turtlesim where you can give it certain coordinates and it shall go alone to this goal and stops at it.


## How to install and work with project 
- You should be familiar with Ubuntu and ROS.
- You can download the full package and put it in your workspace.
- You should then open the terminal and go to the directory scripts inside the package where you will find the python files of the project and run whatever you like.
- **Hint** For Turtle_Goto_Controller_Task you could run it with roslaunch command since I've made a launch file that runs turtlesim the code file and the parameter file.

