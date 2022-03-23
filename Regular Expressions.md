# Reading Regular Expressions
`(0 ∪ 1)0 ∗`
is also equal to `(0∪1) ◦ 0 ∗` where concatenation (attaching strings) is assumed 
## Order of Operations
1) `*` star
2) `◦` concatenation
3) `∪` union
### Formal Definition
![[Pasted image 20220322221142.png]]
- ε is empty string
- ∅ empty language
*inductive definition* not a circular definition but the definition consists of smaller parts of another definition
`R+ ∪ ε = R∗` 
`R+` shorthand for `RR∗ .`
>When we want to distinguish between a regular expression R and the language that it describes, we write L(R) to be the language of R
## Identities
`R ∪ ∅ = R` adding empty language to **any** language will not change it
`R ◦ ε = R` Joining (concatenating) an empty string to **any** string will not change it
#### remember
`R ∪ ε` may not equal *R*
`R ◦ ∅` may not equal *R*
*any regular expression can be converted into a finite automaton that recognizes the language it describes, and vice versa*
## Generalized nondeterministic finite automation
![[Pasted image 20220323004457.png]]
If a qrip exists such that:
- qi →R1 qrip, 
- qrip →R2 qrip, qrip →R3 qj
-  qi →R4 qj
