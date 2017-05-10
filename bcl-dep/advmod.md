---
layout: relation
title: 'advmod'
shortdef: 'adverbial modifier'
udver: '2'
---

An adverbial modifier of a word is a (non-clausal) adverb or adverbial
phrase that serves to modify the meaning of a predicate or another modifier.

~~~ sdparse
An mga residente digdi inaapod na Nagueños \n Some residents were summoned here from Nagueños.
advmod(inaapod, digdi)
~~~

The _advmod_ relation is also used for interrogatives when they modify a predicate.

~~~ sdparse
Ano pigagibo mo?  \n What are you doing?
advmod(pigagibo, ano)
~~~
