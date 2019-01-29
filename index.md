---
# we will misuse date to be the date the guide updated
date: 2019-01-28 10:40:09 +0000

# Update page modified by changing the date.
# In Vim use `:r! date -u +"%F %T %z"`
---

<a class="github-ribbon" href="{{ site.github.repository_url }}"><img style="position: absolute; top: 0; right: 0; border: 0;" src="https://s3.amazonaws.com/github/ribbons/forkme_right_green_007200.png" alt="Fork me on GitHub"></a>

![](/assets/qi-logo-256.png?raw=true)

### {{ site.description | default: site.github.project_tagline }}

Hello! Qi is the energy that flows through everything. It is the energy that flows from nature into electricity, from hardware to software, from cryptocurrency to people, and back to nature. It is the vital life force to be balanced through daily practice. Welcome to Qi Hardware!

Qi Hardware is bringing together:

- Cryptocurrency and Blockchain Software & Hardware Innovators
- Open Source Software and Hardware Developers
- Previous Qi Hardware Project and Community as Makes sense
- Ethusiasts of Cryptocurrency, China and Shenzhen

### TODO

- [x] clone proofofhardware.com distributed
- [x] create clear introduction text
- [x] update qi-hardware.com logo
- [ ] create social
  - [x] telegram
  - [x] Instagram
  - [ ] Twitter (in-progress)
- [ ] pick out a font for the site
- [ ] figure out what to port from qi-hardware.com
- [ ] complete document drafts one by one
- [ ] invite people from qihardware irc with an announcement
- [ ] invite world to qihardware.org, social push connected to something
- [ ] ideas needing more exploration
  - [ ] eip drafts and documents
  - [ ] journal for science papers
  - [ ] energy testing equipment and tools (testnet)
  - [ ] proof of hardware shenzhen summit (march?)
  - [ ] fellowship or grants?
  - [ ] howto generate resources to grow community

### Events

- Currently we are planning a Proof of Hardware summit in Shenzhen.
- _Stay tuned here for more details._

### Glossary

- [Fullnode](/glossary/fullnode)
- _Add your term here, we will keep improving this._

### Guides

- Bitcoin
  - [Hello World for Fullnode](/guide/fullnode-helloworld)
  - [Setup a Bitcoin Fullnode](/guide/setup-bitcoin-fullnode)
  - [Your first cryptocurrency transaction without real coins](/guide/testnet-guide.md)
- Ethereum
  - [Setup an Ethereum Miner](/guide/setup-ethereum-miner)
  - [Setup an Ethereum Fullnode](/guide/setup-ethereum-fullnode)
- IPFS
  - [Setup an IPFS Node](/guide/setup-ipfs-node)

### Surveys

- [Wallets](/survey/wallets)
- [Put It On the Blockchain](/survey/put-it-on-the-blockchain)
- [Cryptocurrency](/survey/cryptocurrency)
- [Books](/survey/books)


### Contact

- E-mail: <a href="mailto:{{ site.email }}">{{ site.email }}</a>
- Telegram: [https://t.me/{{ site.telegram }}](https://t.me/{{ site.telegram }})
- Twitter: [https://twitter.com/{{ site.twitter }}](https://twitter.com/{{ site.twitter }}) (news & for public announcements)
- Instagram: [https://instagram.com/{{ site.instagram }}](https://instagram.com/{{ site.instagram }}) (community building)

### Contributors

- [Christopher Adams](https://christopheradams.io) @christopheradams
- [Qin Fengling](http://qinfengling.io), @qinfengling
- [Jon Phillips](https://rejon.org), @rejon
- [Clément Renaud](http://clementrenaud.com) @clemsos
- [Wolfgang Spraul](https://qihardware.org) @qihardware
- Add yourself :)

### Supporters

- [Fabricatorz Foundation](https://fabricatorz.org)
- [Linzhi](https://linzhi.io)
- [POEX](https://poex.io)
- [Proof of Existence](https://proofofexistence.com)
- _Contact to be a supporter <a href="mailto:{{ site.email }}">{{ site.email }}</a>  :)_


{% include footer_meta.md mod_date=page.date %}
