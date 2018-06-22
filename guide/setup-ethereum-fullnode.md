# Setup an Ethereum Full Node
### The Definitive Guide

## Software Implementions
- [go-ethereum](https://github.com/ethereum/go-ethereum)
- [Parity](https://github.com/paritytech/parity)
- [cpp-ethereum](https://github.com/ethereum/cpp-ethereum)
- [EthereumJ](https://github.com/ethereum/ethereumj)

## Hardware that maye be used as fullnode

- Raspberry Pi
- BEAGLEBONE BLACK
- ODROID XU3/XU4
- WANDBOARD
- PC
- Virtual Server (AWS, linode)

## Biggest Issues

## From Beginner to Expert

### EASY: Ubuntu Linux

- You may also install the go-ethereum in Ubuntu like this:

```bash
sudo add-apt-repository -y ppa:ethereum/ethereum
sudo apt-get update
sudo apt-get install ethereum
```

### MIDDLE: Docker

- [Setup fullnode docker image with Docker](https://github.com/ethereum/go-ethereum/wiki/Running-in-Docker#running-in-docker)

### MIDDLE: Mini-computer (Raspberry Pi, etc)

- [Setup fullnode in Raspberry Pi / BEAGLEBONE BLACK / ODROID XU3/XU4 / WANDBOARD](http://ethembedded.com)

### MIDDLE: AWS

- [Using the AWS Blockchain Template for Ethereum](https://docs.aws.amazon.com/blockchain-templates/latest/developerguide/blockchain-templates-ethereum.html)

### HARD: Build from Source Code

- [Build it from the scratch](https://github.com/ethereum/go-ethereum/wiki/Building-Ethereum)



[//]: <> (@rejon I don't know better way show page modified, so in vim:)
[//]: <> (:r! date -u)
{% include footer_meta.md mod_date="Fri Jun 22 08:30:54 UTC 2018" %}

