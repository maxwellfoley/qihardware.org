# Fullnode Hello World

Learn the full node through `hello world` for separate components.

## Full blockchain database

It will need a long time to synchronize the entire database, be patient please.

We will use a lightweight way to learn the database:

- [Insight: A bitcoin blockchain explorer and API](https://insight.is)

```bash
git clone git@github.com:bitpay/insight.git && cd insight
npm install
npm start
```

Then open a browser and go to: `http://localhost:8100`

## Wallet

You can use any type of wallet, online/offline, software/hardware.

A lot of users use SPV wallet today, so you don't need to wait a long time to synchronize the entire database.

- [Bitpay payment test](https://bitpay.com/docs/testing)

## Miner

You should know [Block hashing algorithm](https://en.bitcoin.it/wiki/Block_hashing_algorithm) in the beginning,

There are 2 ways to do crypto currency mining, [solo or mining pool](https://en.bitcoin.it/wiki/Pool_vs._solo_mining)

Actually it seems nobody uses "solo mining" today, although it is more useful to understand how the miner works.

People eager to use a "mining pool," you will get more stable rewards, but it makes understanding how mining works more difficult.

Today, it's better to buy a ASIC miner or GPU miner today, as it will waste a lot of time for you to build a useless miner that is not competitive today.

If you still want to know more about miner, you can read the article [Bitcoin mining the hard way: the algorithms, protocols, and bytes](http://www.righto.com/2014/02/bitcoin-mining-hard-way-algorithms.html)

## Network routing

Routing is not as popular as the other components. You can also learn it from the following

- [Blockstream Satellite](https://github.com/Blockstream/satellite)
- [BTC Relay](https://github.com/consensys/btcrelay-fetchd)
- [Fast Internet Bitcoin Relay Engine](https://github.com/bitcoinfibre/bitcoinfibre)

{% include footer_meta.md mod_date="Fri Jul  6 06:44:19 UTC 2018" %}

