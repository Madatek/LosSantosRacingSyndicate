# LosSantosRacingSyndicate
A series of scripts for GTA V that manage a world of racing.

These scripts must be able to simulate and manage not only the player's career, but the AI's too. So the world must feel in costant evolution.
Street races and motorsport are both gonna be a thing, in Street Racing police is gonna be a factor, while in motorsport the aggressiveness of opponents will be really tough to contend with.
The actual races are managed by the wonderful scripts by Eddlm, this will only keep the world running.

In the "planning" folder, you will find how I plan to develop the mod. Of course, the script itself will be programmed in C#, while the data I'm not sure if to store them in .json or to actually create a database.

PROJECT STATUS

1 - Pull the head out of my ass and start doing shit - DONE
2 - Decide what I actually want to do - DONE
3 - Plan data and program structure - IN PROGRESS
4 - Develop the data structure (.json or mysql? A NOSQL DB like Mongo is also being considered)
5 - Develop the script
	5.1 - InitializeWorld
	5.2 - CreateSaveLoad
	5.3 - UiMenu
	5.4 - Read and apply from database, CreatePilot
	5.5 - FreeEvent
	5.6 - TimeAdvancer
	5.7 - CarPurchaserPlayer, TeamCreatePlayer
		5.7.1 - Same for AI
	5.8 - CreatePilotAI
	5.9 - ContractAI
6 - TimeAdvancer
	6.1 - EventManager, ChampionshipManager, EventSimulator

	
	