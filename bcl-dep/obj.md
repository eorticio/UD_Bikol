---
layout: relation
title: 'obj'
shortdef: 'object'
udver: '2'
---

The `obj` relation indicates the (direct) object of a verbal predicate, 
typically the noun phrase that denotes the entity acted upon or which undergoes a change of state or motion.

~~~ sdparse
Halion mo an mga papers sa lamesa. \n You bring me the papers on the table.
obj(Halion, papers)
nsubj(Halion, mo)
det(papers, an)
det(papers, mga)
~~~

~~~ sdparse
Ipapabisto ko saimo si Mario. \n You introduce him (/her) to Mario.
obj(Ipapabisto, saimo)
iobj(Ipapabisto, Mario)
nsubj(Ipapabisto, ko)
~~~
