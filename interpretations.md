- an interpretations **D** = (D,M) translates a formula from $A$ to $A^D$ 
- there are two components of a first-order language interpretation:
	- Domain D (non empty set like the natural numbers)
	- Translator M (A mapping that maps every)

- Given an interpretation **D** = (D,M), the translation of A, i.e. $A^D)$ is obtained by
	- replacing $(\forall x)$ with $(\forall x\in D)$ 
	- keep any bound object variables unchanged
	- Applying M to every other substrings of A 

- Examples:
	- if A is x=y, then $A^D$ is $x^D = y^D$ and for $D = {1,2,3}$ and $M$ defined:
		- XD is 2 and YD is 3 then AD is 2=3 which is false
	- If a is $(\forall x)x=y$ 
		- then A^D is $(\forall x\in D) x=3$ 
		- "for all x in the set, x is 3"
		- which is false again 