---
layout: relation
title: 'conj'
shortdef: 'conjunct'
udver: '2'
---

The `conj` relation is the relation between two conjuncts, with the first conjunct being the head. 
The coordination is treated asymmetrically, with the first conjunct acting as the head for all proceeding conjuncts.

~~~ sdparse
Asya an pinakadakula asin pinakamatawong kontinente sa kinaban. \n Asia is the biggest and most populated continent in the world.
cc(pinakamatawong, asin)
conj(pinakadakula, pinakamatawong)
~~~

~~~ sdparse
an bagas, gulay, niyog asin abaka
cc(abaka, asin)
conj(bagas, gulay)
conj(bagas, niyog)
conj(bagas, abaka)
~~~
