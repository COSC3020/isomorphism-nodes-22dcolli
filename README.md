# Isomorphism

Prove that if two graphs $A$ and $B$ do not have the same number of nodes, they
cannot be isomorphic. I have started with the formal definition of isomorphism
below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

## Plagarism Statement

All exercises must contain the following statement:
“I certify that I have listed all sources used to complete this exercise, including the use
of any Large Language Models. All of the work is my own, except where stated
otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is
suspected, charges may be filed against me without prior notice.”

## Note
I did not complete this excersise last semester, so I am attempting this completely from scratch.

## Answer

By definition, the two graphs we compare have to have the same number of nodes, otherwise they simply can't be isomorphic. In the slides it is stated that in order to be isomorphic, there needs to be a one-to-one and onto function between the two graphs, and with the same number of nodes that just can't happen. For example, if Graph A has 5 nodes and Graph B has 4 nodes, and then we try to map the two graphs on to each other, we would see that Graph A then had a node that didn't map to anything in B, which means that it isn't one to one and going further if that single node had any connections, then the edges of both graphs wouldn't line up either. Having the same number of nodes in both graphs is the simplest and one of the most important first indicators of isomorhism that we can check for.
