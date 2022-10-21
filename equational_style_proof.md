#TODO 
### $A_{1}\equiv A_{2}, A_{2}\equiv A_{3}, A_{n}\equiv A_{n+1}$
- Proofs written through making equivalent statements
- less rigid than [[hilbert_style_proofs|Hilbert style]]
- using the transitivity of the $\equiv$, we're able to replace $A_{n}$ with $A_{n+1}$
- we can use a $\Leftrightarrow$ to simplify the syntax 

### Corrollary:
- 1: $\Gamma \vdash A_{1} \equiv A_{n+1}$ ([[formula_sets|Gamma]] is a series of equivalnces that proves $\vdash A_{1}$ to $\equiv A_{n+1}$)
- 2:  $\Gamma \vdash A_{1}$ iff  $\Gamma \vdash A_{n+1}$ (we don't always use equational style proves to establsih a equvalence, but to prove any wff, we pick one thing we know is true [[logical_axiom]] or [[rules_of_inference]], and show that it's equivalent to the [[well_formed_formula]]) we're trying to prove