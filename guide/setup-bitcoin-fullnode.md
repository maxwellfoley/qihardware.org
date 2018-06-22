# Setup a Bitcoin Full Node 
### The Definitive Guide

While many people are concerned with mining Bitcoin, few are running Bitcoin fullnodes. A Bitcoin fullnode is an instance of `bitcoind` running with the
entire bitcoin blockchain. For the health and speed of the network, it is
ideal for Bitcoin Fullnodes to be geographically dispersed. If you are running
a mining farm, it is also good to have a local Bitcoin Fullnode to decrease
latency of transactions.

The final reason it is great to run a bitcoin fullnode is because you
BELIEVE IN BITCOIN, BLOCKCHAIN and CRYPTOCURRENCY. It is the RIGHT thing to do.

The Bitcoin Fullnode is the BIBLE of BITCOIN that is continuously written :)

This guide is meant to be best CURRENT practice in a few scenarios

## Software Implementations
- [Bitcoin Core](https://github.com/bitcoin/bitcoin)
- [Bitcore Node](https://github.com/bitpay/bitcore-node)
- [Bcoin](https://github.com/bcoin-org/bcoin)

## Hardware that can be used as fullnode
- Raspberry Pi
- Mini-computers (like Bitnodes or Bitseed)
- Physical Computer / Standard PC
- Virtual Server (AWS, linode, etc)

## Biggest Issues

- Currently as of 2018-06-22, Bitcoin Fullnode requires at least 250G hard drive.
- Processor with enough power to handle both network throughput and transactions.
- Power draw from the computer. Smaller mini computer like bitseed only 10W.
- No really scaled manufacturer producing Bitcoin fullnodes.

## From Beginner to Expert

### EASY: Bitseed

Bitseed is an active project and company selling bitcoin nodes as a
hardware product.

#### Buy a Bitseed

- [Bitseed.org](https://bitseed.org)

#### Install a Bitseed on a computer

- [Open Source Code](https://github.com/bitseed-org/bitcoin-box)
- [HOWTO Install Bitseed 3](https://github.com/bitseed-org/bitcoin-box)

### EASY: Bitnodes
- As of 2018-06-22, the main core software project for [bitnode is 
DISCONTINUED](https://github.com/ayeowch/bitnodes-hardware)
- We do not recommend buying hardware or installing onto random hardware
as this project seems stalled.

#### Install your own Bitnode on Linux

```bash
curl https://bitnodes.earn.com/install-full-node.sh | sh
```

### MEDIUM: Setup Bitcoind on your computer

Make sure you have a dedicated 250G+ drive, preferably SSD, dedicated to bitcoin.

- [Bitcoin.org Running a Full Node](https://bitcoin.org/en/full-node)

#### Example: Mac Mini

- Current: Mac Mini i5 4G RAM + 512G Hardisk, RMB 2600 / $450 USD

### MEDIUM

- Buy cheap mini-computer
- Make sure has 250-500G hard drive
- Install [debian](https://debian.org)
- Install bitcoind
- Plug in ethernet network (make sure network uses DHCP)
- BOOM! WORKS!


### MEDIUM: Setup fullnode docker image in Amazon ECS
- [Setup Bitcore Core fullnode with Docker](https://github.com/ruimarinho/docker-bitcoin-core)

### HARD: Setup fullnode in Raspberry Pi / PC

- [Setup Bitcoin Core fullnode](https://bitcoin.org/en/full-node)
- [Setup Bitcore Node fullnode](https://bitcore.io/guides/full-node)
- [Setup Bcoin fullnode](http://bcoin.io/guides/vps-setup.html)


## Do you know more?

- Please do help us add the latest knowledge to this guide.





[//]: <> (@rejon I don't know better way show page modified, so in vim:)
[//]: <> (:r! date -u)
{% include footer_meta.md mod_date="Fri Jun 22 08:04:43 UTC 2018" %}
