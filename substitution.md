
## $A[\textbf{p}:=B]$
- (the $\textbf{p}$ is bolded as it's a [[metavariable]])
- a [[schema]] in the [[metatheory]]
- this means to substitute/replace every [[boolean_variable]] $\textbf{p}$ occuring in the formula $A$ by formula $B$ (wherever you see $\textbf{p}$ in $A$, replace it with the entire formula $B$)
- has the higest [[operation_priority]] over all [[boolean_alphabet#Boolean Connectives|Boolean connectives]]

### Substitution in Predicate Logic
- consistent with the previous definition 
- we substitue terms into object variables in formulae
$s[\textbf{X}:=t]$ 
$s$   // if f is a constant or a variable other than x      
$t$   // if $s$ is $\textbf{X}$
$f(s_{1}[\textbf{X}:=t],...,s_{n}[\textbf{X}:=t])$     


Notation: $A[x:=t]$ demotes the wff obtained by replacing all original free occurrences of the object variable $x$ in the formula $A$ by the term $t$

- The variable $x$ is bound in $A$ ($A$ is of the form $((\forall x)B)$ where $B$ is some [[well_formed_formula]]), then no replacement occurs since $x$ is not free
- There are instances where substitution is undefined 

