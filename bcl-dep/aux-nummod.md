---
layout: relation
title: 'aux:nummod'
shortdef: 'numeric modifier auxiliary'
udver: '2'
---

The `aux:advmod` relation is one of the four language-specific relations for Bikol.
It is used for the linking word 'na' that connects a numeric modifier to its head.
The head of the relation is the modifier to which the linking word is attached.

~~~ sdparse
Ini may apat na eskalon \n This has four floors.
aux:nummod(apat, na)
nummod(eskalon, apat)
~~~
