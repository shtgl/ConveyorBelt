## Problem Statement 
Develop a system to depict either 2D graphics or 3D graphics using Blender or other C/C++ graphics libraries.

## Software Requirements: 
Desktop: Windows 10 or Windows 11
Processor: Intel core i5 - 11300H clocked at 3.10 GHz
Ram: 16 GB 

## Methodology:
1.	We are using Blender for creating animation of a factory conveyor belt.
2.	Add a plane mesh for creating a conveyor belt.
3.	Edit the plane and add a round curve on both the ends of shape. 
4.	Merge the center points of the curve of the plane and convert it to a curve.
5.	To add conveyor belt blocks, add one more plane.
6.	Add an array modifier to the plane and set a gap distance between the two elements of the belt. Increase the count of elements on the belt.
7.	Now add a curve modifier to make the conveyor belt align with the curve.
8.	To increase the thickness of conveyor belt elements, add a solidify modifier.
9.	Add an animation keyframe to the conveyor belt. We are using 120 frames to simulate the activity. 
10.	Initialize the conveyor frame to 0 distance with respect to the x axis. Calculate the total length of the conveyor belt and use this length at the last keyframe of the animation.
11.	Add a plane and align it with the conveyor belt. This is just to add an effect to the conveyor object.
12.	Now add a mirror modifier to the plane and remove the extra face between the conveyor belt.
13.	Add a plane just behind the conveyor to create a machine object. Select the top two edges of the object and give a round curve.
14.	Select the front face (wrt conveyor) and add an inset element. And extrude the inset element within the machine object.
15.	Create a cube which will topple over the conveyor belt.
16.	Add a plane to create a platform for the factory look.
17.	Now add a cube element just after the conveyor end. And give a round curve to its edges. Create a hole within the plane and extrude the plane to increase the depth.
18.	Adjust the frame of the box toppling into the hole and conveyor belt to get a feel that the box is on the belt and about to fall down.
19.	Put the box in the hole at a particular key frame and insert a keyframe of rotation to rotate the box by a certain angle.
20.	 Remove the x and y rotation parameters, as they are causing the box to overlap with the conveyor belt. And let the z axis rotate the box and pull the axis of the key frame so that the box rotates at right angles and time.
21.	Now add multiple cubes by adding a cube object to favorites and just add it and align it in the timeline.
22.	To add a smoothing effect to the conveyor belt, we can add a bevel modifier. 
23.	Now add different objects to the factory to give a nice look.
24.	Add a lighting element to the system. We are using disk lights. Get more shadows to the factory using light sources incident on the factory at different viewing angles.
25.	Use different color combinations to give a nice effect to the system.
26.	Now add emission to the objects to let it emit light.
