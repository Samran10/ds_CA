#I will be working on a 3D Multiplayer Game, this will be created in Unity using the Photon Pun 2 Services.
#Users will be able to play against other people across the network in the game and be able to join game rooms if they want to play with friends.

# Introduction
The main aim of this work is to develop a distributed system, in this case a First Person Shooter 3D Game utilizing the Unity and Photon (Pun) Engines. The purpose is to glance at how a First Person Shooter game can be developed into a functionable distributed system. Carrying all this forward, I was able to develop the 3D game environment to control different types of components, C# was utilised for handling the scripting in my system.

# Requirements
* The game should allow it’s users to issue an interface through which the users of the game can enter the home screen when starting the game.
* The game should allow it’s users to add their player name.
* The game should allow it’s users to build a game room to which the game will be played in.
* The game should allow it’s users to find a room which has been created.
* The game should allow it’s users to exit the room once the game has been created.
*	The game should allow it’s users to enter the room once the game has been created.
*	The game should allow it’s users to be the next host of the game once the main host leaves the game.
*	The game should allow it’s users  to see their names when starting the game.
*	The game should allow it’s users to switch guns once the game has been started. Game consists of 2 guns. Shotgun gives 50 damage and the Handgun gives 25 damage. Each   player will spawn with 100 health when they enter the game.
*	The game should allow it’s users to be able to shoot other users, this leads to a reduction in their heath and if the damage is high, the user whose health is low       should die and respawn for the game to be continued.
*	The game should allow it’s users to shoot everything in the game – there will be a fixed timer of 15 seconds for the bullets to disappear.
*	The game should allow its users to look at the status of their health bar when being shot.
*	The game should allow it’s users to look at the their kills and deaths on the leader board once the game has been started.
*	The game should allow it’s users to fall off the game map and then respawn. Falling of the map will account in a death stat on the leader board.
