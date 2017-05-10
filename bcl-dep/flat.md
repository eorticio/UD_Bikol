---
layout: relation
title: 'flat'
shortdef: 'flat'
udver: '2'
---

The `flat` relation used for expressions that are semi-flexible and lack a clear head.
This usually applies to names of people, places, or organizations.
By convention, the first word in the MWE acts as the head, but this should not be interpreted as having any syntactic significance.

~~~ sdparse
Si Jose Maria Panganiban sarong propagandistang Pilipino. \n Jose Maria Panganiban is a Filipino propagandist.
flat(Jose, Maria)
flat(Jose, Panganiban)
~~~

~~~ sdparse
May turista na puti nagduman sa San Jose. \n There is a white tourist that visited San Jose.
flat(Jose, San)
~~~

If there is a clear syntactic structure to a name, this should be reflected in the relations, and `flat` may not be used.

~~~ sdparse
Estados Unidos \n United States
amod(Estados, Unidos)
~~~
