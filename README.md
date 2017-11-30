# 04_TankBattles
Open-world deathmatch game between two tanks in Unreal 4.

GDD
Concept: 
The game’s concept is quite simple: tanks fight on a Deathmatch for survival on a hostile environment. In this first version, there will be 2 tanks, one controlled by the player and the other one by the AI. For the moment, we will skip adding terrain structures like trees, buildings, fences, roads or other tanks. But these things may be included in an upcoming version to make the game more fun.

Rules:
1) The first tank to kill the enemy tank/tanks is the winner
2) If your tank gets destroyed, you lose the game.
3) Aiming can only be done in certain angles: Y-axis: 70º; X-axis: 360º. This means that the tank won’t be able to aim down, unless the entire vehicle is facing downhill.
4) Colliding with another tank will cause a small amount of HP loss to both tanks.
5) The tank will be controlled with the mouse for the turret and with the WASD keys for the movement.

Requirements:
1) A tank model
2) Terrain materials
3) Tank movement and aim components
4) Physics engine for the tank projectiles
5) Menu screen
6) SFX for: projectiles, hits, misses, reloading, movement and damage.
7) Background music for the menu and the game (for the game it can be just weather effects)
