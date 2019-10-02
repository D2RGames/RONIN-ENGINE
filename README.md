# RONIN ENGINE
 Pixel platformer engine made using GDevelop

CURRENT Version: 0.0.2

This project is being tested using a controller and keybinding software (I use JoyToKey), to ensure proper "feel". the keybinds I use are as follows:

ACTION		KEY		DS4 BUTTON

Movement	Arrows		D-Pad
Jump		Space		Cross
Kick		B		Circle
Sprint		N		L1


-How It Works-

-Level "terrain blocks" are used to build the outline of the level. Terrain blocks are resizeable, but its important that they don't overlap. Keep terrain blocks on Z layer 1. Once you have a level laid out its just a matter of placing your graphics over the terrain blocks on a higher Z level. Graphics placed over the terrain blocks by nature do not need behaviors or collision with this system.
(As of ver 0.0.2 the only terrain blocks ready to use are Ledge, Wall, Floor, and JumpThruFloor.)

-Player1's Move Guide-

MOVE, JUMP, and CROUCH:
	Should be easy to figure out on your own!

CLIMBING:
	When you are in the air press towards the ledge to grab it. once attached you have three possibilites for movement: Press DOWN to let yourself down, press UP to jump upwards and onto the platform, or Press opposite to your facing direction to look back.
once you are looking back you can jump by pressing JUMP, if you release the back button you will return to looking forward, in which time you can press UP and DOWN once more.

WALLJUMP:
	Jump at a wall and you'll attach to it and begin sliding down the wall. In this state you must press away from the wall and press JUMP to succsessfully walljump. Wall sliding can be used to your advantage if you need to time the walljump.

KICKS:
	Press KICK while moving or stationary to do a basic kick, if you time your next kick well you can do a combo. Trying to mash kick as fast as you can won't work, it takes timing. If you kick while in the air you'll do a flying kick, flying kicks don't end until you touch ground. Also if you kick while sprinting you'll do a flying kick off the ground.

SPRINTING and SLIDING:
	Hold SPRINT to increase your running speed, you'll jump farther when you sprint but you'll also have extra momentum if you change directions. To do a slide along the ground be sprinting while moving and press DOWN. The length of the slide will be based on how fast you were going prior.

-Known Bugs-

-While crouched its possible to inch along the ground by pressing left or right, this is okay though as crawling will eventually be implemented and will solve this.

-Sometimes while walljumping at a ledge terrain block the camera "judders" a bit, not a huge issue gameplay-wise more of a aesthetic bug

-Now and then when you grab a ledge the player sprite will be offset from the ledge, making him look like he's slightly hanging in mid air. Haven't been able to find the source of this issue as it appears to occur at random, although it doesn't seem to break the programming at all.


	


 

