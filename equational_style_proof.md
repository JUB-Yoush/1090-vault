#TODO 
### $A_{1}\equiv A_{2}, A_{2}\equiv A_{3}, A_{n}\equiv A_{n+1}$
- Proofs written through making equivalent statements
- less rigid than [[hilbert_style_proofs|Hilbert style]]
- using the [[transitivity]] of the $\equiv$, we're able to replace $A_{n}$ with $A_{n+1}$
- we can use a $\Leftrightarrow$ to simplify the syntax 

### Corrollary:
- 1: $\Gamma \vdash A_{1} \equiv A_{n+1}$ ([[formula_sets|Gamma]] is a series of equivalnces that proves $\vdash A_{1}$ to $\equiv A_{n+1}$)
- 2:  $\Gamma \vdash A_{1}$ iff  $\Gamma \vdash A_{n+1}$ (we don't always use equational style proves to establsih a equvalence, but to prove any wff, we pick one thing we know is true [[logical_axiom]] or [[rules_of_inference]], and show that it's equivalent to the [[well_formed_formula]]) we're trying to prove


### predicate logic
- we need to use many relative theorems that we cannot use in the tradtional equational proof (as they're not true on thier own)
- equational proofs don't establish equivlance like [[hilbert_style_proofs]],
- we can add onto our equational proofs by allowing implications
- instead of
	- $A_{1}$
	- <=>
	- $A_{2}$
	- <=>
	- ...
	- $A_{n}$
- we can do 
	- $A_{1}$
	- $\rightarrow$ // $A_{1}$ implies $A_{2}$
	- $A_{2}$
	- <=> // $A_{2}$ is equivalent to $A_{3}$
	- $A_{3}$ 
- by the [[deduction_theorem]], a relative theorem $A_1 \vdash A_2$ becomes an absolute theorem $\vdash A_1 \rightarrow A_2$  