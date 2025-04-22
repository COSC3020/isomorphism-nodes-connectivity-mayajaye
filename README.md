# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

A and B are both completely connected graphs, so every pair of distinct vertices is connected by a unique edge.

$A = (V_{1}, E_{1})$ $B = (V_{1}, E_{1})$

$|V_1| = |V_2|$

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v) \in E_1$ iff $(f(u),f(v)) \in E_2$.

1. If $A = (V_{1}, E_{1})$ is isomorphic to $B = (V_{1}, E_{1})$, there must exist a bijection function f that maps $V_1$ to $V_2$ such that:
$[(u,v) \in E_{1} \iff (f(u),f(v)) \in E_{2}]$

If the bijective function f maps $V_1$ to $V_2$, that proves A is isomorphic to B

2. $\exists
f: V_1 \rightarrow V_2 [true \iff (f(u),f(v)) \in E_{2}]$ 

{definition of completeness}: Because A is complete, $(u,v)$ must be a distinct pair that belongs to $E_1$

3. $A = (V_{1}, E_{1})$ is isomorphic to $B = (V_{1}, E_{1}) \rightarrow \exists
f: V_1 \rightarrow V_2 [true \iff true]$

{definition of a bijection}: Because f is a bijection, it is an onto function, meaning since u and v are a distinct pair, f(u) cannot be equal to f(v). This means f(u) and f(v) will be a distinct pair that belongs to $E_2$ since B is also complete.

4. $\exists
f: V_1 \rightarrow V_2 [true]$ {iff truth table}

5. true  {condition holds}

Because it is true that there is a bijective function f that maps $V_1$ to $V_2$ such that u and v belong to $E_1$ and f(u) and f(v) belong to $E_2$, A must be isomorphic to B.

Formal definition of completeness from [this](https://www.geeksforgeeks.org/what-is-complete-graph/)

"I certify that I have listed all sources used to complete this exercise,
including the use of any Large Language Models. All of the work is my own, except
where stated otherwise. I am aware that plagiarism carries severe penalties and
that if plagiarism is suspected, charges may be filed against me without prior
notice."
