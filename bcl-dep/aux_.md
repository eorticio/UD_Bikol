---
layout: relation
title: 'aux'
shortdef: 'auxiliary'
# The filename "aux" is not allowed on Windows, so we redirect instead
# (see https://github.com/UniversalDependencies/docs/issues/20)
redirect_from: "sv/dep/aux.html"
udver: '2'
---

An `aux` (auxiliary) of a clause is a function word associated with a verbal predicate 
that expresses categories such as tense, mood, aspect, voice or evidentiality.

~~~ sdparse
An kabotan kan banwaan iyo an dapat na pinaghahalean kan autoridad kan gobierno \n The will of the people shall be the basis of the authority of government
aux(pinaghahalean, dapat)
~~~

The Bikol UD Treebank introduces four new, language-specific relations, `aux:amod`, `aux:nmod`, `aux:nummod`, and `aux:advmod`, 
which are used for the linking word 'na' found in modification structures in Bikol. 
It is important to note that these relations are associated with modifiers, 
and not with predicates as the traditional `aux` relation is used. 
For more documentation about these four language-specific relations, see their corresponding documentations.
