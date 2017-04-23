---
title: MCPE 0.8.0 Info
permalink: /wiki/versions/0.8.0/
---
# MCPE 0.8.0
// TODO

### Dumps
All functions in the libminecraftpe.so Android binary.

[Full Dump](dumps/dump.txt)
[Blocks Dump](dumps/blockdump.txt)
[Items Dump](dumps/itemdump.txt)
[Packet Dump](dumps/packetdump.txt)

### How I got the data
I simply went in my Android Linux terminal and typed the following.

##### Full Dump

```bash
nm -DC libminecraftpe.so > dump.txt
```

##### Packet Dump
To dump blocks and items i just changed 'Packet' to 'Tile' or 'Item'.

```bash
nm -DC libminecraftpe.so | grep "Packet::" > packetdump.txt
```
