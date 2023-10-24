[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=12538852&assignment_repo_type=AssignmentRepo)
# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

A completely connected graph is a graph where there is an edge between every pair of vertices.

Suppose $A = (V_1, E_1)$ and $B = (V_2, E_2)$ are two completely connected graphs with the same number of nodes. Let the nodes of $A$ and $B$ be denoted as $a_1, a_2, a_3, \ldots, a_n$ and $b_1, b_2, b_3, \ldots, b_n$ or as $a_i$ and $b_j$ for any $i$ and $j$. Let $f: V_1 \to V_2$ be a function (bijection) between their sets of vertices.

A graph is one-to-one if every value in $V_1$ is mapped to exactly one element in $V_2$, meaning that the number of vertices must be equal. The number of vertices of the graphs are equal in this case, meaning the graphs are one to one. Formally, $f(a_i) = b_j$ for all $i$ and $j$.

Let $a_1$ and $a_2$ be any two nodes in $A$ connected by an edge. By the definition of completely connected, $A$ has an edge between any pair of vertices. This means that $f(a_1)$ and $f(a_j)$ must be connected by some edge in $B$, this means it is onto.

Therefore, there is a one-to-one and onto function $f:V_1 \to V_2$ such that $(u,v)$ is in $E_1$ if and only if $(f(u), f(v))$ is in $E_2$ in two graphs with the same number of nodes and are completely connected.

