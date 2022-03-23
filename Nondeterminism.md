*nondeterministic computation* can be envisioned in a tree hierarchy, where nodes are independent forks (processes) 
### usecase
- NFA are easy to construct (smaller in comparison to DFA)
- any NFA can be converted to DFA
	 **every NFA has an equivalent DFA**
Main distinction between NFA and DFA lies with transition functions.
### formal definition
> In an NFA, the transition function takes a state and an input symbol or the empty string and produces the *set of possible next states*
> A nondeterministic finite automaton is a 5-tuple (Q, Σ, δ, q0, F), where 
> 1. Q is a finite set of states, 
> 2. Σ is a finite alphabet, 
> 3. δ : Q × Σε−→P(Q) is the transition function, 
> 4. q0 ∈ Q is the start state, and 
> 5. F ⊆ Q is the set of accept states.
### closure under regular operations
A set is closed under a operation if applying said operationto any members always yields a member of the set.
#### references
[closure and more](https://people.cs.clemson.edu/~goddard/texts/theoryOfComputation/4a.pdf)