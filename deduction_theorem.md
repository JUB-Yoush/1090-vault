- a [[metatheorem]]
	- if $A$ is within [[formula_sets|formula set]] $\Gamma$,
	- and $\Gamma$ is a [[tautological_implication#Hypothesis|Hypothesis]] of $B$,
	- then we can say that $\Gamma$ by itself proves the implication, so $\Gamma \vdash A \rightarrow B$

-- Example--
- $\vdash (A\equiv B) \rightarrow (B\equiv C) \rightarrow (A \rightarrow C)$
- by deduction theorem we can turn it into
- $(A\equiv B) \vdash  (B\equiv C) \rightarrow (A \rightarrow C)$

- also useful for proofs by [[contradiction]], as you can just take a [[tautological_implication#Conclusion|conclusion]], make it false, and put it on the hypothesis side to make a proof 

-- Example --
$A \equiv B$, $B \equiv C$,$A$ $\vdash C$
By Proof by  [[contradiction]] we can prove
$A \equiv B$, $B \equiv C$,$A$,$\neg C$ $\vdash \bot$ 