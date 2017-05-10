---
layout: relation
title: 'obl'
shortdef: 'oblique modifier'
udver: '2'
---

The `obl` relation is used for a nominal functioning as a non-core (oblique) argument or adjunct 
to a verb, adjective, or other adverb, thus serving as an adverbial attachment.
The `obl` relation is always accompanied by a `case` relation.

~~~ sdparse
Pasiring kami sa baraylehan. \n We are going to the dance.
obl(Pasiring, baraylehan)
case(baraylehan, sa)
~~~

The `obl` relation can 

~~~ sdparse
Dakolon an basura sa dagat. \n The trash is accumulating in the river.
obl(Dakolon, dagat)
case(dagat, sa)
~~~
