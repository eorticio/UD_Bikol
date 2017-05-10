---
layout: relation
title: 'nsubj'
shortdef: 'nominal subject'
---

The dependency type `nsubj` marks the nominal subject of a clause. 
Subjects depend on the main predicate of the clause, which is usually a verb but may be a noun or adjective.

~~~ sdparse
Halion mo an mga papers sa lamesa. \n You bring me the papers on the table.
nsubj(halion, mo)
~~~

~~~ sdparse
An Alabama sarong estado kan Estados Unidos. \n Alabama is a state of the United States.
nsubj(estado, Alabama)
~~~

~~~ sdparse
Magayon an bado ni Maria. \n Maria's dress is nice.
nsubj(magayon, bado)
~~~
