---
title: MCPE 1.0.5 LoginPacket
permalink: /wiki/protocol/1.0.5/packets/login/
---
## Login Packet
//TODO: description

{:.table}
{:.table-bordered}
|Sent from client|true|
|Sent from server|false|

### Fields

#### Client Extra Data
NOTE: The names of each field is the *exact* field name sent from the client.

{:.table}
{:.table-bordered}
|Name|Type|Description|Example|
|----|----|-----------|
|ADRole|int|**TODO**||
|ClientRandomId|float|**TODO**||
|DeviceModel|string|The model of the device||
|DeviceOS|int|**TODO**||
|GameVersion|string|The network game version|1.0.6.0|
|ServerAddress|string|The server address and port|192.168.1.2:19132|
|GuiScale|int|**TODO**||
|SkinId|string|The name of the players skin|Standard_Alex|

Packet Info from [PocketMine-MP](https://github.com/pmmp/PocketMine-MP).
