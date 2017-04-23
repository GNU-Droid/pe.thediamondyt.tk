---
title: MCPE 0.2.0 Info
permalink: /wiki/versions/0.2.0/
---
# MCPE 0.2.0
// TODO

### How I got this data
I simply went in my Android Linux terminal and typed the following.

##### Full Dump
```bash
nm -DC libminecraftpe.so > dump.txt
```

##### Packets
```bash
nm -DC libminecraftpe.so | grep "Packet::" > packetdump.txt
```
