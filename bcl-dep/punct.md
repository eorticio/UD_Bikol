---
layout: relation
title: 'punct'
shortdef: 'punctuation'
udver: '2'
---

This is used for any piece of punctuation in a clause, regardless of its function. 
The punctuation mark is attached to the head of the phrase or clause to which it belongs.
A punctuation mark separating coordinated units is attached to the following conjunct.
Paired punctuation marks (e.g. quotes and brackets, sometimes also dashes, commas and other) should be attached to the same word,
usually the head of the phrased inclosed in the pair punctuation.

~~~ sdparse
Namundag siya sa sarong prominenteng pamilya sa Nueva Caceres, Camarines Sur, Filipinas. \n He was born to a prominent family from Nueva Caceres, Camarines Sur, Philippines.
punct(namundag, .)
punct(Camarines, ,)
punct(Filipinas, ,)
~~~

~~~ sdparse
Inaapod man ini sa Espanyol na “cera de abeja”. \n This is also called “cera de abeja” in Spanish.
punct(Inaapod, .)
punct(cera, “)
punct(cera, ”)
~~~
