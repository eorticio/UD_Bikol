---
layout: relation
title: 'cc'
shortdef: 'coordinating conjunction'
udver: '2'
---

A `cc` is the relation between a conjunct and a preceding coordinating conjunction. 

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
