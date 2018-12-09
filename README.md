# Why ToxicTagger

This addon enables you to easily make macros that are good for tagging mobs with the toxictagger command without the need for SuperMacro.

This addon/macro is good for getting the tag on the right mobs with very little cognitive effort on your part. 

I tried to make it as faceroll as possible which means that the best way to use this macro is to bind it on the scroll wheel while jumping around in the area.

You don't have to worry about accidentally wasting your cooldowns on mobs you dont want to attack e.g.: 
Mobs that are tagged by other players, wrong mobs or getting stuck targetting dead mobs. 

# Example use 1: 
The best use case is when you are waiting for spawn of a rare mob and you have to compete for the tag against others. 
Let's say you need to kill **Yowler** for the quest *Howling in the Hills* and you want to tag with a rank 1 spell.

/run toxictagger("Fire Blast(Rank 1)", {"Yowler"});

# Example use 2: 
Let's say you are a lvl 15 Mage in Moonbrook, Westfall and need Defias Pillagers and Defias Looters for your quest. Maybe you need Goretusks too.

/run toxictagger("Fire Blast", {"Pillager", "Looter", "Goretusk"});

Notice that you don't need to write the full name of the mob you want. You only need to write some of it. In this example I didnt write "Defias" but you *could* also make it work with {"Pill", "Loot"}

# Example use 3:
Maybe you want to get the tag on earth elementals: 

/run toxictagger("Lightning Breath", {"Rock Elemental"});

This will tag both *Lesser Rock Elementals* and *Rock Elementals* which both drop Elemental Earth. 

Notice that Lightning Breath is a pet ability.

# Video of Succesful Tag Attempt: 

https://youtu.be/PAUHHrd2pCg

# Video of not accidentally wasting cooldown on wrong mobs: 
