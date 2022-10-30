#TODO 
- our boolean logic is truthful
- making sure that everything we can prove using the [[boolean_alphabet]] is actually true
- use can use soundess to disprove fallacies like $A  !\vdash B$


### Soundess Theorem
- if $\Gamma \vdash A$, then $\Gamma$$\vDash _{taut} A$ 
- If $\Gamma$ proves $A$ then $\Gamma$ tautologically implies A
- every [[absolute_theorem]] is a [[formula_states#Tautology]]
- $\Gamma \vdash A$ is a theorem schema, where $A$ stands for any formula 
- to show that $A$ is not provable, we can find a specific formula, and some [[state_v]] for which $v(A) = \textbf{f}$

### Soundess Counter-Examples
- we can use the contrapositve of the soundess theorem to also construct proofs
- if $\Gamma !\vDash _{taut} A$ then $\Gamma \neg\vdash A$