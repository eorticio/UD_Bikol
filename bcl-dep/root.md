---
layout: relation
title: 'root'
shortdef: 'root'
udver: '2'
---

The `root` grammatical relation points to the root of the sentence. A fake node "ROOT" is used as the governor. 
The ROOT node is indexed with "0", since the indices of real words in the sentence start at 1.

~~~ sdparse
ROOT Nagiriwal si mga buratsero. \n ROOT The drunks are fighting.
root(ROOT, nagiriwal)
~~~

Bikol lacks a word for "to be", so the root can be some modifier to the subject of the phrase.

~~~ sdparse
ROOT An Alabama sarong estado kan Estados Unidos. \n ROOT Alabama is a state of the United States.
root(ROOT, estado)
~~~
