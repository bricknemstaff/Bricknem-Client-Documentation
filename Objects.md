# Bricknem-Client-Documentation
 A written documentation of everything in the Bricknem web based game client.



So you want to build a game on Bricknem but don't understand the code (which I probably shouldn't write this but I'm gonna try my best - nero) well here is a documentation of all the code that is in the base game template which you can edit alot of the code is already documented in because of <b>@Grizler#6999</b>.



* <b>game.core.demo1.js</b>. This file is where you'll be spending the most time in because its the main file which runs the game. In this file you'll see that there is a bunch of code and I'll be explaining it here!.


* <b>_cannon.createRigidBody({})</b>. This is what you use to call a object such as: Cubes , Spheres, ect. When using this function you have to use a few variables.<br>
![image](https://user-images.githubusercontent.com/97628321/181345693-45c6fb70-f3bd-4db7-94d4-348c9f1f75f6.png)<br> as you can see there are five different variables.<br> 
* <b>Shape</b>: The shape variable will decide the shape of the object using the <b> new CANNON.Box</b> function you can choose the different objects. The next part of that line is choosing the hitbox of the object and the dimensions of the object.
* <b>Mass</b>: The next variable is the mass variable. This variable will tell the code that it has weight and physics.
* <b>Possition</b>: The possition variable will tell the code where to put the object.
* <b>meshMaterial</b>: The meshMaterial variable is what gives the object its color.
* <b>physicsMaterial</b> The physicsMaterial will tell the code what kind of physics the object should have. <b>_cannon.solidMaterial</b> makes the object have a solid object.


