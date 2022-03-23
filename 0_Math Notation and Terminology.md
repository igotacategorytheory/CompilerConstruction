## complexity theory
There are several ways in which the complexity of a computational problem can be measured. This study has been used extensively in the field of crypography. How hard is the problem?
## computability theory
- Kurt Godel
- Alan Turing
- Alonzo Church
*No computer algorithm can determine whether a mathematical statement is true or false*
Which problems are solvable? 
## Automata Theory
Definitions and properties related to mathematical models of computation. 
- finite automaton
	- text processing
- context-free grammar
	- artifical intelligence and programming languages
# Mathematical Notions and Terminology
## Sets
Often represented in brackets. S = {1,3,6,5,8} 
*group of objects represented as a unit*
Objects in the set are referred to as the *elements* of the set
` 7 ∈ {7, 21, 57} and 8 6∈ {7, 21, 57}.`
*subset* every member of *A* is a member of *B* 
*proper subset* if a subset is not equal to the parent subset
*multiset* when you want the # of occurances to matter
`When we want to describe a set containing elements according to some rule, we write {n|rule about n}. Thus {n| n = m2 for some m ∈ N } means the set of perfect squares.`
*union* the set combination of *A* and *B* 
*intersection* set of elements in both *A* and *B*
*complement* not in *A*
## sequences and tuples
An ordered pair is literally just a tuple with two parameters. Sequences are like sets except the order matters. Represented as such:
(7, 14, 15)
*Power Set* The set of all subsets. 
`If A is the set {0, 1}, the power set of A is the set { ∅, {0}, {1}, {0, 1} }. The set of all ordered pairs whose elements are 0s and 1s is { (0, 0), (0, 1), (1, 0), (1, 1) }.`
## functions and relations
In computer science it is essential to understand that functions and mappings refer to the same thing. *Functions*  are objects that sets up an input output relationship.
`A binary relation R is an equivalence relation if R satisfies three conditions: 1. R is reflexive if for every x, xRx; 2. R is symmetric if for every x and y, xRy implies yRx; and 3. R is transitive if for every x, y, and z, xRy and yRz implies xRz.`
## graphs
*undirected graph* set of points connected
points are *vertices/nodes*
connections are called *edges*
- number of edges at a node is the *degree* of the node
*simple paths* do not repeat nodes
*cycles* start and end at the same node
A graph is a *tree* when a graph is connected with no simple cycles
*simple cycle* is when a graph contains at least 3 nodes and repeats only the first and last nodes
## strings and languages
*alphabet* any non-empty finite set
`Σ1 = {0,1} Σ2 = {a, b, c, d, e, f, g, h, i, j, k, l, m, n, o, p, q, r, s, t, u, v, w, x, y, z} Γ = {0, 1, x, y, z}` examples
*languages are defined as a set of strings*
## boolean logic
The foundation for computer electronics. 
*Negation* is NOT op. 
*XOR*, operation is designated by the ⊕ symbol
	- when either but not both give 1
Any boolean expression can be represented with NOT & AND ops.
`P ∨ Q	equals	¬(¬P ∧ ¬Q)`
`P → Q 	equals	¬P ∨ Q `
`P ↔ Q 	equals	(P → Q) ∧ (Q → P) `
`P ⊕ Q	equals	¬(P ↔ Q)`
# Definitions, Theorems, and Proofs
- definitons eliminate ambiguity
*proof* convincing logical argument that a statement is true
*Theorem* proven statements
	(does anyone care for lemmas or corollaries?)
## Finding Proofs
P iff Q - represents 2 statements
If P is true, then Q is true`P ⇒ Q`
If Q is true, then P is true `P ⇐ Q`
## Types of Proof
### Proof by Construction
If the obj. exists you need to prove by construction..
### Proof by Contradiction 
Assume the opposite of what you are trying to prove to find a contradiction.
### Proof by Induction
- induction hypothesis is critical to the beginning of the problem 
`Basis: Prove that P(1) is true. . . . `
`Induction step: For each i ≥ 1, assume that P(i) is true and use this assumption to show that P(i + 1) is true.`



