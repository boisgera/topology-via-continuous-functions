---
title: Continuous functions
author: Sébastien Boisgérault, MINES ParisTech
---

Let $S=\{0, 1\}$ with $\leq$ the usual order.
A *topological space* is a set $X$ endowed with a set of *continuous* functions 
from $X$ to $S$ such that:

  - if $f, g: X\to S$ are continuous, $f \wedge g$ is continuous,

  - if $\{f_i: X \to S\}$ are continuous,
    $\vee_i f_i$ is continuous.

As a special case, the *Sierpiński space* is the set $S$ together whose set of
continuous functions $S \to S$ is:
$$
\left\{(x\mapsto 0), (x\mapsto 1), (x \mapsto x) \right\}.
$$
(In other words $f: S\to S$ is continuous
if and only if $f(1)=0 \Rightarrow f(0)=0$.)

Now, more generally, let $X$ and $Y$ be topological spaces. 
A function $f : X \to Y$ is 
*continuous* if and only if for every continuous
function $g: Y \to S$, the function $g \circ f: X \to S$ is continuous.


TODO:

  - explain the gist (if we are interested in cont fun, not topo spaces ;
    also very convienent way to deal with topo on posets)

  - explain the didactics option

  - explain/prove why it works (wrt the "classic" definition)

  - open sets (via charac functions), rebuild other topological concepts


  - reference (synthetic topo, Scott, Abramsky)

  - connection with comp sci and partial functions, computability and 
    partial information, etc.

