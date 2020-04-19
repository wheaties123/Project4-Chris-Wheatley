Chris Wheatley
University of Maryland (College Park)
ENPM661 Spring 2020
Dr. Monfaredi
Project #4

Project Description:
Project showcases the Baxter robot's ability to pick and place objects from one location to another.  Specifically, I used VREP to pick a cylinder from table #1 to table #2 and to pick a difefrent cylinder from table #2 to table #1. 

Project 4 contains the following files:
	- baxter_scene.ttt
	- baxter_simulation_vrep.mp4
	- Baxter_leftArm_joint1.txt
	- README.txt
			
NOTES (please read and consider):
	- I placed cuboid primitive objects along the edges of the tables to prevent the cylinders from sliding off after placing them on the table.
	- In this .zip file, I included a .txt file copy of the "Baxter_leftArm_joint1" child script, which was coded in LUA, which defines the motion of Baxter's left arm necessary to perform the desired actions.

If you want to run the simulations in VREP yourself, please follow the steps below:

User Instructions To Run Simulations in VREP:
1)  Ensure that CoppeliaSim/VREP is installed on your machine.
2)  Download and unzip all Project 4 contents.
3)  To run the simulation directly in VREP:
		a) Navigate to "Scenario1" folder.
		b) Open the "baxter_scene.ttt" and run the simulation dirtrectly.
		3) Note that the "Baxter_leftArm_joint1" schild script can be found in the left-hand menu, which is where all of Baxter's left arm actiosn were configured.