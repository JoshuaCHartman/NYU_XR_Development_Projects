# NYU XR & 3D Graphics Development Projects
 Projects completed as part of the NYU Tandon School of Engineering XR Development and 3D Graphics course.
 
 ## Week 8 - Raycasting & Quaternions
 - Interactive Environment - extending the project from Week 7.
 - - Implemented an object / NPC highlighting system using raycasting and layermasks. When filtered objects are struck by the ray, logic is implemented that activates an outline component in the contacted object. The outline is deactivated when the ray is no longer in contact with the object.
 - - Outline colors vary by object type : green for keys, yellow for coins, and light blue for friendly NPCs.
 - - Added a key system. Keys are collected, talled in a visible UI element, and removed when unlocking chests. 
 - - Tally system for collected coins added. Coin and key systms use static instances to pass and retrieve information.
 - - Quaternions were implemented in Week 7. See below.
 
 ## Week 7 - UI & Animation
 - Interactive Environment : 
 - - (to run, download Wk7_02, unzip, and double click .exe file)
 - - Switch between 1st and 3rd person view by pressing 1 on the keyboard. Movement w/ WASD & arrow keys and mouse.
 - - Interactions with multiple objects : NPCs turn towards player (using quaternions) and change animation state and then returning to starting rotation and state when player leaves, chests that open and move, doors that open (or not, depending on circumstances), UI elements appear on scene in response to player location (instructions, warnings, info).
 - - Numerous particle effects.
 - - Game lit with point and ambient light (night scene).
 - - Looping background sounds.
 - - Individual animation loops for NPCs.
 - - Assets from KayKit / Kay Lousberg (@KayLousberg).
 
 - Isometric Adventure :
 - - Four fireflies blink and move independently using keyframes.
 - - Chest animates open/close when player enters trigger zone, and triggers event in log.
 - - Animations are both premade and keyframe generated.
 
- UI / Game Menu :
- - Start Menu (scene index 0) with buttons to launch 3 scenes each encompassing a different game.
- - Each game contans a Pause menu, with options to return to the present game, or go back to the Main Menu.
 
## Week 6 - Scripting for Interaction
- Roll-A-Ball :
- - Physics-based control of player. 
- - Scripted interaction includes collectibles/pick-ups, application of physics forces, updating respawn checkpoints, moving obstacles, and simple particle effects.
- - Camera rotates around ball with right mouse button, at fixed offset follow position. Camera follows at offset when not held down.
- - Assets from KayKit / Kay Lousberg (@KayLousberg).

- First Person Explorer :
- - Mouse & keyboard controls using Unity's new Input System, with mouse sensitivty adjustmeny.
- - Physics-based player movement.
- - Scripted interaction with environment - opening doors, jump pads.
- - Scripted logic for gates to close after player exits trigger space, regardless of starting configuration (open/closed).

## Week 5 - C# Scripting 
- 3D Platformer :
- - Standalone installer for executable.
- - Scripts to control platform movement (editable in the Inspector), and collectibles rotation. 
- - Creation of custom materials with automatic opacity shifting defined by script, and editable in the Inspector. 
- - Instantiation of prefabs after collectibles gathered. 
- - Creation of additional playable area using a variety of rigidbody physics and joints, a scripted teleport system, scripted TextMeshPro controls, etc. 

## Week 4 - Unity Basics
- Rube Goldberg Machine :
- - Use the 3d physics engine to creaete a complicated machine. 
- Features : 
- - Starts without user input using only physics. 
- - Custom physics materials, and application of joints. 
- - Simple script creates a field to alter gameplay time. 
- - Six freely moving platforms/stations. 

- Primitives Gallery - working with 3D primitives and tags.
