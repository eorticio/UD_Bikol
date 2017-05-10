---
layout: relation
title: 'acl'
shortdef: 'clausal modifier of noun'
udver: '2'
---

The `acl` relation is used for adjectival clauses that modify a nominal.
This contrasts with `advcl`, which is used for clauses that modify predicates.
In the `acl` relation, the head is the nominal and the dependent is the head of the clause that modifies the nominal.

~~~ sdparse
an derecho nin pagkamidbid bilang sarong persona sa atubang nin ley. \n the right to be recognized as a person before the law
acl(derecho, bilang) 
~~~
