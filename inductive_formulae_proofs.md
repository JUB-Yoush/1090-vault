- applying [[simple_induction]]/[[strong_induction]] to [[string]]s of [[well_formed_formula]]e

Basis step
- Prove P holds for [[atomic_formula]] X 

Indcuntion step:
- Assume P holds for all formula with complexity k<n, where n is of complexity X 
- Assume it holds for a string of n complexity
	- if X is of form $(\neg A)$ then by the inductive hypothesis it still holds
	- if X is of form $(A\circ B)$ then P holds for A and B