This model is ideal for embedded systems or devices with little memory or resources available. There is quite a lot that's possible with 1bit of memory.
- pattern recognition
**automatic door** 4 possible inputs

![[Pasted image 20220321035055.png]]
**elevator** states may represent the floor
![[Pasted image 20220321035811.png]]
*accept state* This is where finite state machine wants to end. This would represent valid input.
*transitions* function that defines movement from state to state
denoted with `δ`
More shorthand `t δ(x, 1) = y`
- same representation as using arrows
- current state and input treated as ordered pair
	**_T_**(current state, current input symbol)! ->next state_
- if the start state is an accept state, ε is accepted
### Formal Definitions
*finite automation* is a 5-tuple (*Q, Σ, δ, q0, F*)
- *Q* is a finite set (states
- *Σ* is finite set (alphabet)
- *δ* transition func.
*computation* *w = w1,w2 · · · wn* be a string where each *wi* is a member of the alphabet *Σ*
finite automata will accept if seq. of states in Q exists
1) machine starts in start state
2) state to state according to transition function
3) input accepted if it ends up in accept state
[[regular language]] is lang. recognized by finite auto.
### Designing Finite Automata
The goal is to create language that will be recognized by machine. Recv. input string and determine validity. 
#### references
Paul E. Black, "accepting state", in [_Dictionary of Algorithms and Data Structures_](https://www.nist.gov/dads/) [online], Paul E. Black, ed. 17 December 2004. (accessed TODAY) Available from: [https://www.nist.gov/dads/HTML/acceptingstt.html](https://www.nist.gov/dads/HTML/acceptingstt.html)
[More on Finite Automata](https://www.csm.ornl.gov/~sheldon/ds/sec4.2.html)