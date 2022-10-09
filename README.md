# Project Escher
A Unity (2020.3.4f1) based puzzle 3d game, designed to try out C# capabilities with Unity.
The main idea of this project was to create character controller, capable of changing gravity in 6 different directions (6 faces of a cube, 6 walls of a room).
Two different approaches were tested:
1. standart character controller, which is easily controlled, but have problems with colliding walls, especially when the gravity is changed;
2. rigidbody character controller moving and colliding as a physical object, but also being controlled as a physical object, which leads to unpredictable behavior in some cases (for example while navigating stairs);
In the uploaded version character controller is implemented as a rigidbody (option 2).
Gravity rotation is implemented via quaternions. 

To run the app execute Build\Project Escher.exe
