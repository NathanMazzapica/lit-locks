How to make cards for different factions
1. Copy & Paste the 'ix_cwucard.lua' file in the items folder.
2. Change the name to fit your faction, for example 'ix_cmucard.lua'. NOTE: All file names must be lowercase or they will not work.
3. Open the file and change the name and description as needed.

How to make locks for different factions

1. Copy & Paste the 'ix_cwulock.lua' file in the entities/entities folder.
2. Change the name to fit your faction, for example 'ix_cmulock.lua'. NOTE: All file names must be lowercase or they will not work.
3. Open the file and change <ENT.spawnClassName = "ix_cwulock"> to <ENT.spawnClassName = "ix_[your-faction]lock">
4. To change the faction's locked color, simply change the value of <ENT.lockedColor>
5. Change the 'key' value to the uniqueID of your factions key. This is the key's filename without the sh_ and .lua parts. For example
   for sh_cmucard.lua, the uniqueID would be cmucard