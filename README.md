# Azure Dev-Ops Link
Multiplayer Shooting Game is updated here (Repository): https://dev.azure.com/10538269/_git/Game

# Technical Specification
|Utilized Engines & Language|
|-------------|
	Unity
	Photon Pun 2 / Realtime
	C#  

# Unity
Unity is simply a cross stage game engine which was created by the Unity Technologies. Unity is utilised to prinicpally make games and reproductions for PC's, mobille device, and also consoles.

# Photon
Photon Engine is simply a game engine which spends significant time in multiplayer game expansion. It's a progression of items, software, innovation, and systems networking parts which leads to extraordinary speed, execution, and more to online play.

With a tremendous network frequently adding up around 20,000,000 internt based online clients, the Photon Engine is incredible for multiplayer game expansion. Photon Engine functions admirably with Unity, as well, manufacturing all the strategies in which to produce games to a much more extensive way.

Realtime is a networking administration engine which operates fundamentally for fixing issues with lower latency games. It's cross stage, implying that Realtime can work for games along these lines such as the likes of Fornite. The Low Latency influences web based games, and Photon Realrtime means to annihilate all the normal speedy internet based play isses. Utilizing the state of gaming innovation to end match issues. Realtime offers bits of source code right on its site ofr inquisitive clients and is a convincing piece of a programming software, utilizing a self facilitated server.

Pun basically relates to the (Photon Unity Networking). It is literally a path for game designers and players to handly incorporate the Solidarity structure with the Photon services. Doing this makes the components handle the for rapid server speed, lagging free game rooms and a firm stable network. In comparison to Realtime, Pun is a fabulous and fast method for enhancing your servers, game rooms, and other functionalities that permit the games to flawlessly run.

# C Sharp
C# is specifically a very powerful object oriented programming language interface engineered by Microsoft. This language is very easy to use with engines such as Unity, as it is simple and a flexible language to implement within a system.

# Abstract
The main aim of this work is to develop a distributed system, in this case a First Person Shooter 3D Game utilizing the Unity and Photon (Pun) Engines. The purpose is to glance at how a First Person Shooter game can be developed into a functionable distributed system. Carrying all this forward, I was able to develop the 3D game environment to control different types of components, C# was utilised for handling the scripting in my system.
  
# Introduction
The main aim of this work is to develop a distributed system, in this case a First Person Shooter 3D Game utilizing the Unity and Photon (Pun) Engines. The purpose is to glance at how a First Person Shooter game can be developed into a functionable distributed system. Users will be able to play against other people across the network in the game and be able to join game rooms if they want to play with friends. Carrying all this forward, I was able to develop the 3D game environment to control different types of components, C# was utilised for handling the scripting in my system.

# Background
Notwithstanding the economic uncertainty and calamity enormously influencing the world, analysts issued that the gaming industry has extended at a rate of seemingly 57%. Even though as I type these words, tons & millions of people around the world are probably playing a game in front of their PC’s. The main cause of this broadening can be expressed that the gaming industry can attract many users with unique preferences. Unity Technologies realized the opportunities in this type of field and created a game engine studio for every game developer.

The scheme of creating a game is obviously really not new to this world. However, it was an option that I wanted to carry forward during the course of making a distributed system as I have a huge interest in the gaming industry.

Game Development can be declared to be the main artwork of adding designs to develop a game in order to smooth the process of interactivity between every player for educational, entertainment and simulation motives. Game Development can certainly be the action of determining how a game should ought to be like. 

As you may be aware that First Person Shooter (FPS) games are usually one of the most favoured game category as of today, it can even be considered a best seller nowadays. FPS games are certainly becoming favoured day by day, this is due to the creation of new technology. In a First Person Shooter game, a user plays the game in the first perspective, this relates to the fact that the user of the game controls a virtual game character that is situated in a 3D environment and also participates the game from an eye view of the game character.

The development of my chosen system was a result of an issue of playing with other users residing from elsewhere. I wanted to think of a possible result which would be able to let many users simultaneously to play the FPS game with no system crash and cut down every mistake which has been confronted. Distributed Systems can let all the assets to attach and be utilised as a whole. Distributed Systems may scale evenly by adding lots of PC’s to the system, this will definitely allow the system to hold majorly enlarged workloads.

# Scope
* Functional Criteria: This option requires the post-design process to complete a set of requirements to characterize the functional requirements of the selected system. This step involves managing the backend environment to facilitate the alignment of the set of requirements with the main goal of the project, in this case to create an online gaming platform that can be used by many users from different parts of the same network. Once all of the requirements have been met, the next step will be  to examine all the criteria to create a collection of guidelines that can then be used to design the system.

* System Development: According to the user interface design, the project must be applied and then the final stage is to have it executed. All the code is implemented in the web-based GitHub service. As you may know, GitHub is a very important tool for adding projects. This is because it is centralized to store all the coding related to the project.

*	User Interface: Once all the set of instructions have been designed, the following step is to produce a user interface that should be suitable and meet all the established functional requirements.

*	System Test: The development of the proposed system has been completed. In the next step, we test that all of the functional criteria are met and that no errors have been detected in the system and the integration part.

*	Documentation: Finally, right after testing the system has been completed and validation has taken place to all the functional criteria, the following step involves recording the project, where it should be documented according to your needs. In this case, the document is added to GitHub as a readme file for the created repository and the created application is added to Azure Dev Ops as it was quite big.

*	Data Consistency: System must ensure that all the distributed data provide consistent data access and update operations, even though the system should maintain data consistency despite concurrent entry and failure.

*	Performance: System should offer rapid response times and efficient resource usage, while minimizing communication overhead and network latency, even though the system should minimize network latency and communication overhead.

*	Concurrency: System must definitely be capable of managing the simultaneous access and modification of data by multiple users or processes in an environment that is distributed.

# Requirements
In sequence to be able to acknowledge all the purposes of my system, these series of requirements will certainly be considered to be the functional criteria of my system.

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

# Design
As you may be aware that this is a 3D Multiplayer Shooting Game (FPS). Users can play this game with their friends through the Photon server. Users will be able to entertain themselves and have fun with their friends when playing this online game.

Home Screen of my built 3D Multiplayer Shooting Game (FPS). Consists of the following Find Room, Build Room, Exit Game & Playername (this is where the user will insert their name and this will be displayed to the other user when starting the game).

![4](https://user-images.githubusercontent.com/78740991/228991945-af3d9b06-ecb4-4299-ae74-c4a010749312.png)

When the user clicks the Build Room button from the Home Screen, it will bring them to a separate form where the user will need to enter the name of the room they wish to create and then click the Build Room to build that room.

![5](https://user-images.githubusercontent.com/78740991/228991962-e3d60e6d-4718-4682-956f-2fe8fe737d45.png)

This form pops up when the user clicks the Find Room button from the Home Screen, if any user created a room it will display in the Find Room section and the player names will be displayed too – whoever joined that specific room. The user will then have the option to start the game room or leave the room.

![6](https://user-images.githubusercontent.com/78740991/228991972-088fb7f8-5feb-4cd0-b5d2-bfa7f37ed6c3.png)

This map will open when the user starts the game. The users will spawn at a randomised place on the map.

![7](https://user-images.githubusercontent.com/78740991/228991996-a5b6a530-df70-4ae7-8054-2b81b090458c.png)

As you can see from the picture below, the player name is displayed above the capsule.

![8](https://user-images.githubusercontent.com/78740991/228992007-4c12c097-36be-488f-975e-47b9fb46fa7e.png)

This is the shotgun in the game. Users will be able to choose which gun they want to select.

![9](https://user-images.githubusercontent.com/78740991/228992017-1fea268e-bdec-469f-a275-a6a858f47ab5.png)

This is the handgun in the game. Users will be able to choose which gun they want to select.

![10](https://user-images.githubusercontent.com/78740991/228992024-e029a0d4-8776-4b1d-9558-5f9b0913bb23.png)

Health bar will reduce every time the same player gets struck by a bullet.

![11](https://user-images.githubusercontent.com/78740991/228992034-f982f6f9-c52a-4e97-9ada-259a7346b12e.png)

These are the bullets which will be shot from the gun. The bullet will have a timer of 15 seconds before they disappear.

![12](https://user-images.githubusercontent.com/78740991/228992042-65d0d306-7f85-47f0-83cd-fbb35d8e4a91.png)

Users will be able to see their stats on the leader board with both kills and deaths updated during the  gameplay.

![13](https://user-images.githubusercontent.com/78740991/228992048-67a6555a-0349-423e-9161-29515329f6ee.jpg)

# Analysis
Making a 3D Multiplayer Shooting Game (FPS) that works through a network for the users of the game can seriously be crucial.

*	Security: When handling the game through a network, it can be surely be secured by all the security precautions of that specific network, due to this it can be less protected to the outer cyber-attacks.

*	Cost: Running the game using the Photon Unity Networking (PUN) through a network can be very reasonable in terms of pricing. You are able to use its services free of charge for up to 100 concurrent connections. This definitely removes the demand for more costly connections.

*	Speed: By simply running the game though the Photon Network, it ensures faster connections through the users, simply due to the fact that data does not really need to proceed between the internet.

*	Privacy: Running the game through the Photon (Pun) engine, every user of the game can be sure that no one from outside can access their game server, this ensures that the users privacy is kept. When developing the game, you are able to select which region you want the users to be from.

*	Control: When running the game through a network, users can possess more command over the game, this includes personalizing settings & features according to the users requirements. When developing the game, the Photon (Pun) engine allows the developer to select which region you want the users to be from.

# Evaluation
The design of system which is distributed has various types of advantages in comparison to different designs. Photon is straightforwardly a scalable, low-latency & high fault tolerant distributed system which has the function to connect to multiple streams of huge data flowing constantly.

*	Fault Tolerance: The distributed system that I have chosen is particularly created to control issues by dividing workloads over many servers.

*	Concurrency: My selected distributed system enables concurrent processing of requests, which can lead to a more improved performance of the system and decreased latency. It’s worth noticing that the Photon Cloud has a maximum of 16 users per room.

*	Scalability: The distributed system which I have picked considers horizontal scaling, implying that the system can be extended by literally by placing additional servers to deal with a large amount of workload. This is certainly a huge upper hand as compared to the conventional architectures which include limitations in any sort of scaling.

*	Performance:  My picked distributed system provides fast responding times and optimized  resource usage, resulting in reduced network latency.
