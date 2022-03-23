>Just because the language appears to require unbounded memory doesn’t mean that it is necessarily so

As a result there are methods of proving this.
consider two languages over the alphabet `Σ = {0,1}:`
`C = {w| w has an equal number of 0s and 1s}`, and 
`D = {w| w has an equal number of occurrences of 01 and 10 as substrings}.`
## Pumping Lemma
All strings in lang. are pumpable if they are as long as the *pumping length*
- pigeonhole principle
![[Pasted image 20220323012847.png]]
*A* is regular lang.
*s*any string in *A* of at least length *P*
*s* = *xyz*
- `y =/=  ε`
- `xy` is at most length *p*
- *n* is at least *p*
	- *n+1* > *p*
### To prove that a given language L is not regular: 
1. Assume that L is regular. 
2. Use the pumping lemma to guarantee the existence of a pumping length p such that all strings of length p or greater in L can be pumped. 
3. Find a string s in L that has length p or greater but that cannot be pumped. 
4. Demonstrate that s cannot be pumped by considering all ways of dividing s into x, y, and z, and for each division, finding a value I where xyi z∉L Ö 
	The existence of s contradicts the pumping lemma if L were regular. Hence L cannot be regular.