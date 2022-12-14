- #PREDICATE_LOGIC 
- you can replace any $\forall$ with $\exists$, and vice versa.

How to introduce $\exists$ to a theorem
- (Dual of [[logical_axiom#First-Order Logic ($ Lambda_{1}$|Ax2)]])$\vdash A[x:=t] \rightarrow (\exists x)A$   //if we have an instance of $A$, there exist some $x$ where $A$ holds
- Corollary (Dual of specialization Rule) $A[x:=t]\vdash (\exists x)A$ // 
- Corollary simplifes to $A \vdash (\exists x)A$ // wherever you see A you can write $(\exists x)A$
- metatheorem: : if x dnof in $\Gamma$ or in $B$, then $\Gamma \vdash A \rightarrow B$ iff $\Gamma \vdash (\exists x)A \rightarrow B$ 

How to introduce $\forall$ to a theorem
- metatheorem: if x dnof in $\Gamma$ or in $A$, then $\Gamma \vdash A \rightarrow B$ iff $\Gamma \vdash A \rightarrow (\forall x)B$ 
	- what it means: you can a $\forall x$ to the conclusion of a formula iff $x$ doesn't appear free in $\Gamma$ and $A$ 

Introduce $\exists$ 
- if x dnof either in $\Gamma$ or in $B$, then $\Gamma \vdash A \rightarrow$ iff $\Gamma \vdash (\exists) $
