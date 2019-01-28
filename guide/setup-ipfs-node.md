---
date: 2019-01-28 09:43:58 +0000
---

# Setup an IPFS Node
### The Definitive Guide

IPFS is a [distributed file system](https://en.wikipedia.org/wiki/Clustered_file_system#Distributed_file_systems), not the blockchain.

If you want to know more about instances of distributed file system, there are lots of information available through [Wikipedia](https://en.wikipedia.org/wiki/List_of_file_systems#Distributed_file_systems).

EDITOR NOTE: We could not take it any longer. When we heard that in China people have been
buying hard drives with ipfs enabled, thinking it will generate money, we had
to get closer to the reality of setting up an IPFS node RIGHT NOW.

This guide is meant to be best CURRENT practice in a few scenarios.

## Software Implementations
- [IPFS](https://ipfs.io)

## Hardware that can be used as fullnode
- Raspberry Pi
- Mini-computers (like Bitnodes or Bitseed)
- Physical Computer / Standard PC
- Virtual Server (AWS, linode, etc)
- NAS

## Biggest Issues

- There is no human friendly interface to setup IPFS on a drive.
- There is no system for generating revenue from running or, renting the extra space on your HD.
- Low adoption
- Lots of competition from Google, Amazon, Apple, MS on cloud storage.



## From Beginner to Expert

### EASY: [Run IPFS in a Docker container](https://ipfs.io/blog/1-run-ipfs-on-docker/)

### EASY: Run ipfs on your computer

- [Install IPFS](https://ipfs.io/docs/install)

### MEDIUM: Setup NPM module to do ipfs solution

- [A solution](https://github.com/leanthebean/mtg/blob/master/server/server.js)

### HARD: Setup ipfs on Raspberry Pi / PC

- INCOMPLETE, needs to be written.

## Innovation to do

- Make IPFS Apache module
- Make IPFS Nginx modules
- Make simple front-end to some simple NAS
- Make some simple front-end to openwrt



{% include footer_meta.md mod_date=page.date %}
