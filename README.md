# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v) \in E_1$ iff $(f(u),f(v)) \in E_2$.

    A = {                   B = {
        X: [Y]               F: [G]
        Y: [X]               G: [F]
    }                       }

$V_{1} = \{X, Y\}$

$E_{1} = \{(X, Y), (Y, X)\}$

$V_{2} = \{F, G\}$

$E_{2} = \{(F, G), (G, F)\}$

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v) \in E_1$ iff $(f(u),f(v)) \in E_2$

$A = (V_{1}, E_{1})$ is isomorphic to $B = (V_{1}, E_{1}) \rightarrow \exists
f: V_1 \rightarrow V_2 [(u,v) \in E_{1} \iff (f(u),f(v)) \in E_{2}]$ {replace $G_1$ → A, replace $G_2$ → B}

$A = (V_{1}, E_{1})$ is isomorphic to $B = (V_{1}, E_{1}) \rightarrow \exists
f: V_1 \rightarrow V_2 [(X,Y) \in E_{1} \iff (f(X),f(Y)) \in E_{2}]$ {replace $u → X, v → Y$}

$A = (V_{1}, E_{1})$ is isomorphic to $B = (V_{1}, E_{1}) \rightarrow \exists
f: V_1 \rightarrow V_2 [(X,Y) \in E_{1} \iff (F,G) \in E_{2}]$ {replace $f(X) → F, f(Y) → G$}


$A = (V_{1}, E_{1})$ is isomorphic to $B = (V_{1}, E_{1}) \rightarrow \exists
f: V_1 \rightarrow V_2 [true \iff true]$ {definitions of $E_1$ and $E_2$}

$A = (V_{1}, E_{1})$ is isomorphic to $B = (V_{1}, E_{1}) \rightarrow \exists
f: V_1 \rightarrow V_2 [true]$ {iff truth table}

$A = (V_{1}, E_{1})$ is isomorphic to $B = (V_{1}, E_{1}) \rightarrow true$  {condition holds}

$true$ {implication truth table} Q.E.D.


"I certify that I have listed all sources used to complete this exercise,
including the use of any Large Language Models. All of the work is my own, except
where stated otherwise. I am aware that plagiarism carries severe penalties and
that if plagiarism is suspected, charges may be filed against me without prior
notice."
