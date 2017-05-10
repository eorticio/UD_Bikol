---
layout: relation
title: 'aux:advmod'
shortdef: 'adverbial modifier auxiliary'
udver: '2'
---

The `aux:advmod` relation is one of the four language-specific relations for Bikol.
It is used for the linking word 'na' that connects an adverbial modifier to its head.
The head of the relation is the modifier to which the linking word is attached.

~~~ sdparse
Matuga na naman siguro an bulkan Mayon \n The Mayon volcano will surely erupt again.
aux:advmod(naman, na)
advmod(Matuga, naman)
~~~

~~~ sdparse
Halion mo an mga papers ta pigkorehiran na iyan \n Bring me the papers because they were already corrected.
aux:advmod(iyan, na)
nmod(pigkorehiran, iyan)
~~~
