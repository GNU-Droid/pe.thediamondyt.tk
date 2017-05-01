---
name: PocketMine-MP TODO List
permalink: /wiki/software/server/pocketmine/todo/
---
## PocketMine-MP TODO List
A compiled list of all things that arent currently implemented in PocketMine, but should be.
---

#### Commands
 * /clear [player: target] [itemName: string] [data: int] [maxCount: int]
 * /clone \<begin: x y z> \<end: x y z> \<destination: x y z> [maskMode: string] [cloneMode: string] [tileName: string] [tileData: int]
 * /execute 
   * \<origin: target> \<position: x y z> \<command: string>
   * \<origin: target> \<position: x y z> \<detect: string> \<detectPos: x y z> \<detectBlock: string> \<detectData: int> \<command: string>
 * /fill \<from: x y z> \<to: x y z> \<tileName: string> [tileData: int] [oldBlockHandling: string] [replaceTileName: string] [replaceDataValue: int]
 * /gamerule 
   * \<rule: string> \<value: bool>
   * \<rule: string> \<value: int>
   * \<rule: string>
 * /locate \<feature: string>
 * /playsound \<sound: string> \<player: target> [position: x y z] [volume: float] [pitch: float] [minimumVolume: float]
 * /stopsound 
 * /setblock
 * /spreadplayers
 * /testfor \<victim: target>
 * /testforblock \<position: x y z> \<tileName: string> [dataValue: int]
 * /testforblocks
 * /replaceitem 
   * \<block: string> \<position: x y z> \<slotType: string> \<slotId: int> \<itemName: string> [amount: int] [data: int]
   * /<entity: string> \<target: target> \<slotType: string> \<slotId: int> \<itemName: string> [amount: int] [data: int]
 * /xp
 
#### Bugs
 * Players in spectater mode cannot shoot bows ([#852](https://github.com/pmmp/PocketMine-MP/issues/852))
 * Poorly coded NBT library is really slow ([#466](https://github.com/pmmp/PocketMine-MP/issues/466))
 * Command usage output is incorrect on the client ([#236](https://github.com/pmmp/PocketMine-MP/issues/236))

###### TODO: finish
