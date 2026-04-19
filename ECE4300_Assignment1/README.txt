This is a simple 3D labyrinth game demo built with Unity on Windows.
Players can move using WASD, control the camera with the mouse, interact with UI elements, and perform jumps. The game also features background music.

Features

Press to Start

At the beginning of the game, the player can see the maze but cannot move, and objects in the scene are frozen.

A "Press Any Key to Start" message is displayed on the screen.

When the player presses any key:

Player movement is unlocked (WASD + mouse look)

Scene objects become dynamic

The start UI message disappears

Player Controls

Movement: W / A / S / D

Mouse Look: Control the camera with the mouse

Jumping: Press Space

Death and Respawn

The player dies upon touching hazardous balls.

Victory Condition

The player triggers victory by reaching the exit.

Displays Victory UI.

Player control is disabled, and the mouse is unlocked.

Camera

Main Camera is a child of the Player object

cameraTransform is assignable in the Inspector

UI System

Clickable buttons trigger events (e.g., Quit Game)

Press Alt to unlock the mouse cursor and interact with UI

Audio

Background music playback

Physics and Collisions

Player interacts with ground and objects via collisions

Cubes and other objects can have Box Colliders for collision detection

Additional Function :

Press to Start

Death upon Touching Hazardous Ball

Press Space to jump

Hold Alt to unlock the cursor and interact with UI

Victory Condition
