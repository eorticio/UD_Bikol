---
layout: relation
title: 'aux:amod'
shortdef: 'adjectival modifier auxiliary'
udver: '2'
---

The `aux:amod` relation is one of the four language-specific relations for Bikol.
It is used for the linking word 'na' that connects an adjectival modifier to its head.
The head of the relation is the modifier to which the linking word is attached.

~~~ sdparse
May turista na puti nagduman sa San Jose. \n There is a white tourist that visited San Jose.
aux:amod(puti, na)
amod(turista, puti)
~~~

The linking word will always come between the modifier and the word that it modifies.
Since modifiers typically come after the word they modify, the linking word usually precedes the modifier.
However, in some instances, like with superlatives, the order can be switched 
and therefore the linking word will come after the modifier.

~~~ sdparse
An pinakamainit na bulan Hulyo asin Agosto. \ July and August are the most popular months.
aux:amod(pinakamainit, na)
amod(bulan, pinakamainit)
~~~
