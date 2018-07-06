---

date: 2018-07-06 09:43:58 +0000

---

# Survey of Putting It On the Blockchain
## Current State of Putting Things onto the Blockchain

__As of 2018-06-26__

## Ways of Putting Onto the Blockchain

### Certifications

99% of the time when someone says let's "Put That On the Blockchain" what that
is transalted into is a timestamp and sha-256 hash placed onto the main Bitcoin or
Ethereum blockchains. 

#### Proof of Existence

The original proof of existence is [https://proofofexistence.com](https://proofofexistence.com)

### Messages

Since the first blockchain was the Bitcoin Blockchain, there is a limited
amount of information that can be put onto each block. Ethereum does not have
the same limit on blocksize, but a concept of "gas" used to keep down the
insanity of putting increasingly larger sets of data onto "the blockchain". Even
the forked Bitcoin, BCH, has an increased block size to 32mb, but only 220 bytes
in the OP_RETURN for placing a document.

- [List of Hacky Ways to Put Message on Bitcoin Blockchain](https://www.quora.com/Bitcoin-How-can-I-leave-a-message-in-the-block-chain/answer/Adam-Tache)

### Documents

Let's consider messages as small documents, so when we are talking about 
Documents we are really talking about documents like PDF, Songs, Videos, 
Presentations, etc. So let's consider documents 1 mb and larger.

- More than likely, best way to do this is SHA-256 hash to external storage

## Blockchain File Storage

### Needs Research

- Factom
- Siacoin
- Filecoin (status)

{% include footer_meta.md mod_date=page.date %}
