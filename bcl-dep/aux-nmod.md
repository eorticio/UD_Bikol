---
layout: relation
title: 'aux:nmod'
shortdef: 'nominal modifier auxiliary'
udver: '2'
---

The `aux:nmod` relation is one of the four language-specific relations for Bikol.
It is used for the linking word 'na' that connects a nominal modifier to its head.
The head of the relation is the modifier to which the linking word is attached.

~~~ sdparse
kapitolyo na ekonomiya nin Albay \n economic capital of Albay
aux:nmod(ekonomiya, na)
nmod(kapitolyo, ekonomiya)
~~~

~~~ sdparse
helang na tuberculosis \n tuberculosis disease
aux:nmod(tuberculosis, na)
nmod(helang, tuberculosis)
~~~
