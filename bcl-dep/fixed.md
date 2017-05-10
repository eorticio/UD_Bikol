---
layout: relation
title: 'fixed'
shortdef: 'multi-word expression'
udver: '2'
---

The `fixed` relation is one of the three relations for multiword expressions (MWE).
It is used for fixed grammaticized expressions that behave like function words or short adverbials. 
The first word is the head to all other dependents in the MWE.

~~~ sdparse
depende sa species \n depending on the species
fixed(depende, sa)
~~~

~~~ sdparse
An lambang saro igwa nin derecho nin pagkamidbid bilang sarong persona sa atubang nin ley. \n Everyone has the right to recognition everywhere as a person before the law.
fixed(sa, atubang)
~~~
