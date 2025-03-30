# ConsistentMechTextures
Prevents Mechs in rimworld spawning with ages above 100. ie disableing the achient mech textures

[h1]Overview[/h1]
A simple mod that makes it so that mechanoids will always use the same set of textures no matter if their made by the player or spawned by Randy, they will always use the same base texture. 
Player made mechs retain their markings if there are textures for that (there’s a 99.99% chance that will be the case). 

I highly recommend setting “Show player mech names” to “always” so the mechs you make are easy to spot.

This mod is intended to be used with mech retexture mods primary “[url=https://steamcommunity.com/sharedfiles/filedetails/?id=3013205187]Fluff's Curvaceous Underarmored Mechanoids[/url]" due to how that mod is configured.

[h1]Compatibility: [/h1]
Any mechanoid mod using the default mech faction (This includes VFE Mechanoids)


[h1] Known issues: [/h1]

Mechs spawned via either mech capsules or mech drop beacons will spawn at age 100 (Mech will use ancient textures)



[h1] For modders: [/h1]

This mod checks if the default faction type of a PawnKindDef is set to Mechanoid which at that point forces Mechs to generate at ages between 0 to 99, since once I mech go’s past 100 it starts using the ancient mech textures

This mod is literally one XML file with 2 patches within it
