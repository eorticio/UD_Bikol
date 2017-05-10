---
layout: relation
title:  'advcl'
shortdef : 'adverbial clause modifier'
udver: '2'
---

An adverbial clause modifier is a clause which modifies a verb or other predicate as a modifier and not a core complement.
This includes things like temporal, conditional and purpose clauses.
The dependent of the `advcl` relation is the main predicate of the modifying clause, 
and the head is the predicate that the clause modifies.

~~~ sdparse
An kanda, depende sa species, nagbuburak na nadarang kolor na puti, pula, o lila. 
\n A desert rose, depending on the species, blossoms to white, red, or lilac color.
advcl(nagbuburak, depende)
~~~

~~~ sdparse
Maski pobre kami, tiripon man an pamilya. \n Although we are poor, we are still a family.
advcl(tiripon, pobre)
~~~
