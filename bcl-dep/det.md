---
layout: relation
title: 'det'
shortdef: 'determiner'
udver: '2'
---

The determiner relation indicates the relation between a determiner and its
nominal head.

~~~ sdparse
an kanda \n A duck
det(kanda, an)
~~~

The `det` relation is also used for the particle _mga_, which is used to
pluralize nouns. This will often result in two determiner relations
attached to a single nominal.

~~~ sdparse
Nagiriwal si mga buratsero. \n The drunks are fighting.
det(buratsero, si)
det(buratsero, mga)
~~~
