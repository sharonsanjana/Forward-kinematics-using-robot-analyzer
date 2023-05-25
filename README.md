# Forward-kinematics-using-robo-analyzer

## AIM: 
To analyze the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer and polt the graph for link cordinates and joint angles
### COMPONENTS REQUIRED:
1.Robo analyzer software  


### THEORY: 
  
Forward Kinematics

A manipulator is composed of serial links which are affixed to each other revolute or prismatic joints from the base frame through the endeffector. 
Calculating the position and orientation of the endeffector in terms of the joint variables is called as forward kinematics. 
In order to have forward kinematics for a robot mechanism in a systematic manner, one should use a suitable kinematics model. 
Denavit-Hartenberg method that uses four parameters is the most common method for describing the robot kinematics. 
These parameters ai1, α −,1idi and θ the link length, link twist, link offset and joint angle, respectively. 
A coordinate frame is attached to each joint to determine DH parameters. Zi axis of the coordinate frame is pointing along the rotary or sliding direction general manipulator.

Denavit Hartenberg Parameters
With DH Parameters, solving for the Forward Kinematics is easy.  only need to take four parameters for each joint 
i: θifor the joint angle, 
αi for the link twist, 
difor the link offset, and 
ai for the link length. Once I’ve obtained them, I can just plug them in to this transformation matrix:


![image](https://user-images.githubusercontent.com/36288975/170172719-ed7befc9-2894-4344-bfd5-be831bb05308.png)

 ![image](https://user-images.githubusercontent.com/36288975/170172766-b8aeb788-7fd7-4de7-b340-f04656707ebd.png)

 

### PROCEDURE:

1.open the robot analyzer software.
2.select the robot and its degrees of freedom.
3.change the values with the link length whenever necessary. 
4.simulate the model for forward kinematics.
5.pick the graph between the link and the joints.
6.update the Dh parameters of the link configuration and endeffector configuration.





### SIMULATION 
6DOF

![image](https://github.com/sharonsanjana/Forward-kinematics-using-robot-analyzer/assets/127593602/e5f83add-b24c-4c9d-8443-7a6943752f45)

6D0F
https://user-images.githubusercontent.com/95198708/238820898-8f6d7ca0-8c4a-47c3-b46c-76971c72328f.png

4DOF

https://user-images.githubusercontent.com/95198708/238821065-83de22bf-48ee-4b39-91d5-5caa5bb28208.png
4DOF
https://user-images.githubusercontent.com/95198708/238821096-844d7578-bba1-4795-99e0-c144bb263c2a.png

### RESULTS :  

Thus, the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer is analysed and the graph for link cordinates and joint angles is plotted.
