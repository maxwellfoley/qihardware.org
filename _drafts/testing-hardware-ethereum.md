---
date: 2019-02-03 13:12:00 +0000
# Update page modified by changing the date.                                   
# In Vim use `:r! date -u +"%F %T %z"`                                         
---

## Testing Hardware for Ethereum on Global Scale


Cobbling together notes on how to test ProgPROW and other software that will roll out on global blockchain projects.

Here are some bits n pieces:

- Sonia Chen, [03.02.19 21:33]
I think first priority is to test over a selection of the most commonly used GPU (and memory) chips, see here http://ethosdistro.com/versions/
- Sonia Chen, [03.02.19 21:33]
that doesn't talk about memory though
- Philip Salter, [03.02.19 21:37]
Nah Jon I disagree. Geography is irrelevant as long as we test in similar temperature. Testing ASICs is also reasonable with just two miners (but there aren't any ASICs for PPOW anyway). And Sonia yes agreed, the most common GPU types of course are first on the list! AMD570, AMD580, NV1070, NV1080.. maybe some TIs and Titans and Vega and 20xx series but not sure if their price (capex) is at all competitive right now.

- Philip Salter, [03.02.19 21:37]
I'll start working on this and share results here when I get some. If anyone else pitches in then it might be faster


{% include footer_meta.md mod_date=page.date %}
