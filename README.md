# TECHNICAL SPECIFICATION
|Utilized Engines & Language|
|-------------|
Unity
Photon Pun 2 / Realtime
C#

# Unity

# Photon
Photon Engine is simply a game engine which spends significant time in multiplayer game expansion. It's a progression of items, software, innovation, and systems networking parts which leads to extraordinary speed, execution, and more to online play.

With a tremendous network frequently adding up around 20,000,000 internt based online clients, the Photon Engine is incredible for multiplayer game expansion. Photon Engine functions admirably with Unity, as well, manufacturing all the strategies in which to produce games to a much more extensive way.

Realtime is a networking administration engine which operates fundamentally for fixing issues with lower latency games. It's cross stage, implying that Realtime can work for games along these lines such as the likes of Fornite. The Low Latency influences web based games, and Photon Realrtime means to annihilate all the normal speedy internet based play isses. Utilizing the state of gaming innovation to end match issues. Realtime offers bits of source code right on its site ofr inquisitive clients and is a convincing piece of a programming software, utilizing a self facilitated server.

Pun basically relates to the (Photon Unity Networking). It is literally a path for game designers and players to handly incorporate the Solidarity structure with the Photon services. Doing this makes the components handle the for rapid server speed, lagging free game rooms and a firm stable network. In comparison to Realtime, Pun is a fabulous and fast method for enhancing your servers, game rooms, and other functionalities that permit the games to flawlessly run.

# Abstract
The main aim of this work is to develop a distributed system, in this case a First Person Shooter 3D Game utilizing the Unity and Photon (Pun) Engines. The purpose is to glance at how a First Person Shooter game can be developed into a functionable distributed system. Carrying all this forward, I was able to develop the 3D game environment to control different types of components, C# was utilised for handling the scripting in my system.
  
# Introduction
The main aim of this work is to develop a distributed system, in this case a First Person Shooter 3D Game utilizing the Unity and Photon (Pun) Engines. The purpose is to glance at how a First Person Shooter game can be developed into a functionable distributed system. Users will be able to play against other people across the network in the game and be able to join game rooms if they want to play with friends. Carrying all this forward, I was able to develop the 3D game environment to control different types of components, C# was utilised for handling the scripting in my system.

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
