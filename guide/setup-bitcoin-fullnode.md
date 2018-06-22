# Setup a Bitcoin Full Node 
### The definitive Guide

While many people are concerned with mining Bitcoin, few are running Bitcoin fullnodes. A Bitcoin fullnode is an instance of `bitcoind` running with the
entire bitcoin blockchain. For the health and speed of the network, it is
ideal for Bitcoin Fullnodes to be geographically dispersed. If you are running
a mining farm, it is also good to have a local Bitcoin Fullnode to decrease
latency of transactions.

The final reason it is great to run a bitcoin fullnode is because you
BELIEVE IN BITCOIN, BLOCKCHAIN and CRYPTOCURRENCY. It is the RIGHT thing to do.

The Bitcoin Fullnode is the BIBLE of BITCOIN that is continuously written :)

This guide is meant to be best CURRENT practice in a few scenarios

## Implement
- [Bitcoin Core](https://github.com/bitcoin/bitcoin)
- [Bitcore Node](https://github.com/bitpay/bitcore-node)
- [Bcoin](https://github.com/bcoin-org/bcoin)

## Hardware can be used as fullnode
- Raspberry Pi
- Bitnodes
- PC
- AWS

## From beginner to expert
- EASY: Buy Bitnodes, if you can't buy it you can also install the Bitnodes in Linux like this:

```bash
curl https://bitnodes.earn.com/install-full-node.sh | sh
```

- MIDDLE: Setup fullnode docker image in Amazon ECS
	- [Setup Bitcorn Core fullnode with Docker](https://github.com/ruimarinho/docker-bitcoin-core)

- HARD: Setup fullnode in Raspberry Pi / PC
	- [Setup Bitcoin Core fullnode](https://bitcoin.org/en/full-node)
	- [Setup Bitcore Node fullnode](https://bitcore.io/guides/full-node)
	- [Setup Bcoin fullnode](http://bcoin.io/guides/vps-setup.html)

[//]: <> (@rejon I don't know better way show page modified, so in vim:)
[//]: <> (:r! date -u)
{% include footer_meta.md mod_date="Fri Jun 22 06:02:47 UTC 2018" %}
