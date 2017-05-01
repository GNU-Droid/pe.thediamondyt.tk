---
title: Minecraft Pocket Edition
permalink: /wiki/versions/
---
# Minecraft Pocket Edition
Click the version of your choice to view changelog, protocol info and method dumps from libminecraftpe.so

{:.table}
{:.table-bordered}
|Version|Protocol Version|
|--------|----------------|
|[v1.1.0.8](1.1.0.8/)|111|
|[v1.1.0.0](1.1.0.0/)|110|
|[v0.8.0 alpha](0.8.0/)|14|
|[v0.7.4 alpha](0.7.4/)|12|
|[v0.2.0 alpha](0.2.0/)||
|[v0.1.3 alpha](0.1.3/)||
|[v0.1.1 alpha](0.1.1/)||
  
### Demos
{:.table}
{:.table-bordered}
|Version|
|--------|
|[v0.2.1 alpha build 2](demo/0.2.1.2)|


### How to create a dump
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
