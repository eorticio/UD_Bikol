---
layout: relation
title: 'nmod'
shortdef: 'nominal modifier'
udver: '2'
---

The `nmod` relation is used for nominal modifiers of a noun or noun phrase.
It functionally corresponds to an attribute or genetive complement.

~~~ sdparse
An grupo kan mga species \n A group of species
nmod(grupo, species)
case(species, kan)
~~~

~~~ sdparse
Sa presidente kan Albay Writers Club \n The president of Albay Writers Club
nmod(presidente, Albay)
flat(Albay, Writers)
flat(Albay, Club)
~~~

~~~ sdparse
Nagbisita sa eskuelahan mi si Evan \n Evan visited our school
nmod(eskuelahan, mi)
~~~
