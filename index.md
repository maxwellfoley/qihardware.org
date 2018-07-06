---
date: 2018-06-24 03:00:55 +0000
# Update page modified by changing the date.
# In Vim use `:r! date -u +"%F %T %z"`
---

<a class="github-ribbon" href="{{ site.github.repository_url }}"><img style="position: absolute; top: 0; right: 0; border: 0;" src="https://s3.amazonaws.com/github/ribbons/forkme_right_green_007200.png" alt="Fork me on GitHub"></a>

# Proof of Hardware

![](/assets/poh-logo-256.png?raw=true)

### {{ site.description | default: site.github.project_tagline }}

Bitcoin mining is currently too expensive for an individual to join. However, the field of blockchain software is still in its infancy. Without a question, hardware will be used to accelerate computation around blockchain developments and cryptocurrencies.

We (that meaning and could include YOU) made this website to be a group editable resource to break thru the noise of the web, and paid reviews, or guides, to be an open community process for jumpstarting the world of Blockchain Hardware from the individual up. We are contributors made up from the team that invented Bitcoin mining, living and working Beijing, Shenzhen, Hong Kong, Taiwan and San Francisco, coming together to bring software developers closer to hardware realities.

Please add your knowledge to these guides, and see you at a future event in Shenzhen :)


## Guides

### Full Node

Full node defination from [Mastering Bitcoin](https://github.com/bitcoinbook/bitcoinbook)

[A bitcoin network node with all four functions: wallet, miner, full blockchain database, and network routing](https://github.com/bitcoinbook/bitcoinbook/blob/develop/ch08.asciidoc#full_node_reference)

Actually, any health crypto currency should contains all of these functions.

It is the fundamental component of blockchain.

You can use them separately, part of them or combine serval of them in your product.

e.g.

1. Mining pool only use part of full blockchain database, network routing, wallet and miner

2. Cryptocurrency trading platform can use wallet only

3. Block Explorer use full blockchain database

4. Hardware wallet only use part of wallet

More components it used, more complexity it will be.

If you can't wait to try, the following will be the best practise.

- [Setup a Bitcoin Fullnode](/guide/setup-bitcoin-fullnode)
- [Setup an Ethereum Fullnode](/guide/setup-ethereum-fullnode)
- [Setup an Ethereum Miner](/guide/setup-ethereum-miner)
- [Hello World for Fullnode](/guide/fullnode-helloworld)

### IPFS

It is a [distributed file system](https://en.wikipedia.org/wiki/Clustered_file_system#Distributed_file_systems), not blockchain.

If you want to know more about instances of distributed file system,

you can find a lot of informations through [Wikepedia](https://en.wikipedia.org/wiki/List_of_file_systems#Distributed_file_systems)

If you can't wait to try, the following will be the best practise.

- [Setup an IPFS Node](/guide/setup-ipfs-node)

## Surveys

- [Wallets](/survey/wallets)
- [Put It On the Blockchain](/survey/put-it-on-the-blockchain)
- [Cryptocurrency](/survey/cryptocurrency)

## Events

- Currently we are planning a summertime Proof of Hardware summit in Shenzhen.
- Stay tuned here for more details.

## Contact

- <a href="mailto:{{ site.email }}">{{ site.email }}</a>
- Telegram: [https://t.me/proofofhardware](https://t.me/proofofhardware)
- Twitter: [https://twitter.com/proofofhardware](https://twitter.com/proofofhardware) (news & for public announcements)
- WeChat: Ask in Telegram or via e-mai for invite.

## Contributors

- [Jon Phillips](http://rejon.org), @rejon
- [Qin Fengling](http://qinfengling.io), @qinfengling
- [Clément Renaud](http://clementrenaud.com) @clemsos
- [Christopher Adams](https://christopheradams.io) @christopheradams
- Add yourself :)

## Sponsors

- [POEX](https://poex.io)
- [Proof of Existence](https://proofofexistence.com)
- Contact to be a sponsor <a href="mailto:{{ site.email }}">{{ site.email }}</a>  :)

{% include footer_meta.md mod_date=page.date %}
