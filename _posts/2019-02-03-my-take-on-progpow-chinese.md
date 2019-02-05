---
layout: post
author: Alexey Akhunov
title: My take on ProgPOW — looking for a reasonable answer to a reasonable question (Chinese Translation)
---

### 我对 ProgPOW 的看法——为一个合情合理的问题寻找一个合乎逻辑的答案


_EDITOR NOTE: This is a community translation of Alexey Akhunov's [original post on Medium](https://medium.com/@akhounov/my-take-on-progpow-looking-for-a-reasonable-answer-to-a-reasonable-question-9f13ffd4e9d7)._

### Claim 1: The only ways to stop the development of specialised mining devices for Ethereum are to make ETH really cheap, or to drastically reduce mining reward

### 主张1：阻止以太坊专用挖矿设备开发的唯一路径，是打压以太币价格，或大幅降低挖矿奖励。

Both of these action lead to the reduction of mining revenue. Nothing else will credibly stop people from trying to develop better devices.

Some people claim that the reason that the reason EtHash specialised mining devices appeared only recently (3+ years after the launch of Ethereum) is due to EtHash’s excellent “ASIC-resistance”, compared to other algorithms. I believe that instead this 3 years delay is mostly due to:

1. Ethereum not being worth much until the beginning of 2017
2. Credibility of Proof Of Stake replacing PoW “soon”. The key word here is “replacing”. Eth 2.0 pivot in June 2018 meant that PoS and PoW chains will coexist, at least for some time.

It appears to me that the growing consensus among blockchain developers is that it is counterproductive to fight the specialisation of mining hardware. The goal instead should be indirectly fostering (or at least not resisting) more competition in the mining hardware development, which can be achieved by keeping mining “rewarding”. This can be done either by increasing the rewards, or by decreasing the mining costs. Both EIP-1234 (reduction of reward) and ProgPOW (increase of mining cost) go into the opposite direction.

打压币价和大幅降低挖矿奖励，均导致挖矿收入骤降。除此之外，没有什么能阻止人们尝试开发更高性能的设备。

有些人声称以太坊专用挖矿设备最近（以太坊算法推出3年后）才面世的主要原因，是由于EtHash算法相比其他算法，更出色的“抗ASIC”特性所致。而我认为，这3年的延迟主要由于：

1）以太币的价格在2017年之前都不高。
2）PoS 短期内取代 PoW 的可信度。关键点在“取代”。Eth2.0 在2018年6月份切换算法，意味着在一段时间内两种算法将共存。

在我看来，区块链开发者之间越来越多的共识是，与挖矿硬件专用化作斗争是适得其反的。相反，开发目标应该是间接促进（或者至少不抵制）挖矿硬件之间的竞争，这可以通过保障挖矿收益来达成。而保障挖矿收益，则可以通过增加挖矿奖励，或降低挖矿成本实现。但EIP-1234(降低挖矿奖励)和ProgPOW（增加挖矿成本），都是朝着相反方向发展。


### Claim 2: GPU mining is a losing battle, and Ethereum is the last bastion

### 主张2：使用 GPU 设备挖必败无疑，而以太坊则是这场战役的最后堡垒。

If we look at a very helpful table of how much miners earn per day in USD, from messari.io, and recall that Bitcoin, Dash, Litecoin, ZCash, Bitcoin Cash are predominantly mined with specialised (not GPUs) hardware, it becomes clear that Ethereum is “the last bastion” of GPU mining.

<img src="https://cdn-images-1.medium.com/max/1600/1*QsBp6kY8VZWCzeaPQIWy_A.png" alt="Img from medium" />

I do not anticipate any new cryptocurrencies launching with the aspiration of being “ASIC-resistant”. Notable example is Grin, which will increase the reward share of their ASIC-friendly algorithm from 10% to 100% within the first 2 years after launch. Decision of Grin to actually make one of the algorithms ASIC-friendly is due to their hope that making ASIC design simpler will encourage competition. Here is the relevant [video link](https://youtu.be/XckwEw8FyEA?t=1100).

下图来自 messari.io, 是旷工每日收益表。再回想一下比特币，达世币，莱特币，Zcash, BCH均主要使用专用挖矿设备（而非 GPU 设备），就会更清楚以太坊就是 GPU 设备的“最后堡垒”。

我预计任何新发布的加密数字货币都不再有“抗ASIC”的愿景。值得关注的 Grin算法，计划在发布后2年内，将其ASIC友好算法的奖励份额，从10%提升至100%. Grin的这一决定，是基于他们期望ASIC 友好算法可以鼓励竞争。详情请见链接 [video link](https://youtu.be/XckwEw8FyEA?t=1100).


### Claim 3: Hardware design shops are getting better at what they do

### 主张3：硬件设备制造商会不断进步。

One of the most interesting takeways from David Vorick’s talk ([video link](https://youtu.be/sQOfnsW6PTY?t=7841)) for me was that the process of designing digital chips is separate from “taping out”, which is in turn separate from the actual fabrication. Another interesting fact about people like David is that it does not take a very long time (1–2 years) for a very good software developer to learn enough about hardware design to set up a design shop. The required information to do such a transition is not well shared and accessible, so one has to learn directly from people, but such transition is not at all impossible. Hardware design is not a black magic and I expect, given the demand, the number of independent hardware design shops will only grow.

David Vorick 的演讲中([video link](https://youtu.be/sQOfnsW6PTY?t=7841))，最吸引我的一点是，芯片设计和“流片”是分开的，也就是说，芯片设计与芯片制造是分开的。另一个有趣的事实是，像 David 这样的优秀软件工程师，花费相当的时间（1-2年）去学习硬件设计知识，即可建立硬件设计工作室。这种（从软件开发到硬件设计的）转变所需的知识，并不容易获取和共享，所以必须直接请教有经验的人，但这种转变也并非全无可能。硬件设计不是什么黑科技，我预计，基于现有需求，独立硬件设计工作室的数量将会不断增长。


### Claim 4: Pursuit of “ASIC resistance” is a strategy of denial that can hurt more than help

### 主张4：追求“抗 ASIC”是一种逃避策略，对以太坊的发展有害无益。

There were some calls to the Ethereum protocol developers to come up with the “Guidelines for the developers of the specialised mining hardware for ProgPOW on Ethereum”. At first, I did not really understand what these guidelines would be. But recently someone has explained to me that it would be basically answer to the question: “Hey, Ethereum protocol developers, we heard you are switching PoW to ProgPoW. We want to start designing a specialised hardware for it (yes, we know that you think we shouldn’t, but it is neither illegal nor unethical to do it, so we will give it a shot). Please tell us what we should do to make sure we are not labeled as bad actors after the fact”.

This is a very reasonable question. But if you subscribe to the ASIC-resistance strategy, the only answer you can give is this: “There is nothing you can do to prevent being labeled as a bad actor. We don’t want you to develop your hardware, and if we see that you have succeeded, we will try to do another PoW change so you cannot sell your hardware and go out of business”. Which is not a very reasonable answer, and can hurt more than help.

This combination of reasonable question and unreasonable answer is what actually motivated me the most to write this article in the first place. So what the reasonable answer should be?

最近，有人呼吁以太坊开发者出台“ProgPOW 算法下专用硬件设备制造者的开发指南”。起初，我并不真正理解该开发指南是指什么。不过最近有人向我解释，该指南大体可以回答这个问题——“嘿，以太坊开发者们，我们听说你们将要从PoW切换至ProgPOW, 我们想要为此算法做一款专用挖矿设备（当然啦，我们知道你们认为我么你不应该这样做，可这既不违法，也不违反道德，所以我们打算试试看）。请告诉我们应当怎么做，以确保我们不会在既成事实后被认定为坏蛋。”

这是一个很合理的问题。但是，如果你认同抗ASIC策略，那么你能给出的唯一答案，就是“你无论做什么都会被认定为坏蛋。我们不想让你开发这款设备，如果我们发现你已经成功了，那我们就会改变算法，这样你的设备就卖不出去了。”这不是一个很合理的答案，且有害无益。

这样一个合理的问题，和不合理的答案，就是我最初写这篇文章的动机。那么，这个问题真正合理的答案，又是什么呢？
