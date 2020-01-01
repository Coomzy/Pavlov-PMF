# Pavlov-PMF - Modding Framework for Pavlov VR

PMF is a Custom Game Mode modding framework for Pavlov VR, this includes game mode structure to work along side Pavlov, helper functions for things that should be basic but are more complicated than usualy (grabbing and IDing certain actors etc.), general useful actors like:
- PMF_GameLogic (Handles core game mode from PlayerSettings (Health, Speed, Gravity, Loadout) to Team Types (FFA, TeamVsTeam, MultiTeam))
- PMF_PlayerReplicationInfo (Basically a hybrid Controller + PlayerState class making sharing data and sending RPCs easy)
- PMF_Singleton (Access to a Singleton like actor so you only need to cache useful actors once)
- PMF_DebugHandler (Server/Client logging that can be viewed in world or attached to the scoreboard, also constant logging)
- And many more

[PMF Documentation](https://github.com/Coomzy/Pavlov-PMF/blob/master/Documentation/PMF-Docs.md)

# Pavlov-INF - Infection Modding Framework for Pavlov VR

INF is a Custom Game Mode modding framework with Infection based game modes in mind for Pavlov VR, it is built upon PMF so any PMF related folders are required.

It is based upon Halo style of Infection with Humans vs Zombies, when Humans die they become 'Infected' and join the Zombie team when all Humans have been infected the round is over.

Example Features:
- Energry Swords (By default Infected have Energy Swords)
- Alpha/Minion Zombie Settings (Zombies have seperate player settings from Humans allowing for quick iteration of health, speed, gravity, loadout etc.)
- Zombie Selection Choice (Intial Zombies are chosen based on a setting from Random to Winner etc.)
- Zombie Respawn Settings (By default all zombies respawn but can be restricted to Alphas only etc.)

[INF Documentation](https://github.com/Coomzy/Pavlov-PMF/blob/master/Documentation/INF-Docs.md)

Credits:\
Vankrupt Games own any Pavlov assets\
Epic own any Unreal Engine assets\
Microsoft own any Halo assets
