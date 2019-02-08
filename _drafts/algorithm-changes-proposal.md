---
date: 2019-01-29 13:12:00 +0000
# Update page modified by changing the date.                                   
# In Vim use `:r! date -u +"%F %T %z"`                                         
---

## Proof of * Algorithm Changes Proposal

Original question was does Linzhi have a position on a proposed ETC algorithm change from Ethash, what Ethereum currently is using, and considering switching to ProgPoW, to SHA-3:

- https://github.com/ethereumclassic/ECIPs/issues/13

From LinzhiCorp telegram chat:

Sonia Chen, [07.02.19 00:23]
sure we do:

1. PoW change should not divide community
2. PoW change must have a reason/benefit that is clearly expressed and with large enough consensus
3. PoW change should be preset to a fixed date 1 yr or 2 yr in advance.
4. we propose for a PoW change to be designed in such a way that the resulting chips are reusable for other functions in the network, like node spinup
5. The two motivations given for 1049 are not convincing. The economics of 51% attacks are not well understood yet, it seems better to monitor them and learn. We are not sure whether a chain has to have a unique PoW algo or not, there are good arguments either way. The secondary benefit is like our #4, but it needs codesign with chip folks (any, not just us).
6. Overall we think it's very good that people work out strong proposals in all directions. Nobody has all answers. ECIP-1049 is great!


### Thoughts

- Overall, Ethereum has a $1.6 mio daily payout, so arbitrary human changes to code like block reward effect the entire Ethereum economy. It is not wise to make arbitrary changes without some process or procedure.

### TODO

- Think through proposal and alter into a better format.
- Get proposal added to the ECIP-1049 in ETC


{% include footer_meta.md mod_date=page.date %}
