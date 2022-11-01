# RAGEMP_AntiBreakWindows
Stops the client from breaking car windows while trying to enter a car that gets unlocked mid-animation.

GTAV has a default behaviour where any player trying to enter a locked vehicle will smash its windows.
In RAGEMP it can be a problem when using custom door lock scripts, as with those scripts when a player tries to enter a locked vehicle and the vehicle gets unlocked mid-animation the player will smash its windows and will stand still outside the now unlocked vehicle.

This code detects that situation and stops the task of smashing the car window instantly. We keep the car window intact while the player wont be able to see any extrange movement or animation when that happens.