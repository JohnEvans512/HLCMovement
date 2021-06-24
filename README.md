# HLCMovement
First person movement controller for Unity game engine.
Features:
Smooth and acurate movement. All calculations are done in frame update, only interactions with rigid bodies are in fixed update.
Every aspect of movement is framerate independent.
Jumping with a propper inertia simulation.
Height dependent landing amortization.
Fall damage output.
Smooth crouch/uncrouch.
Mouse look smoothing.
Bunny hopping, Crouch jumping and Air strafing.
Full rigid body interaction, pushing and weight simulation.
Sliding on high slopes.
Pick up and carry objects.
Sfx playback for footsteps, jump and landing.

Usage: Add an empty GameObject to the scene, add Character Controller component and this script to GameObject,
set the camera in the script field (do not parent Camera to anything). It should be ready to go.
Different features can be turned on and off by commenting/uncommenting define directives at the top of the file.
"Crouch" "Activate" and "Sprint" buttons will need to be set up in the input settings depending on enabled features.
This code was made and only tested on Unity 5.6.7, so it most likely won't work right away on newer versions.
