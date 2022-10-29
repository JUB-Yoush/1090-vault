
- By using [[deduction_theorem|decuction]] and [[contradiction|proof by contradiction]] to move everything to the [[tautological_implication#Hypothesis|Hypothesis]] side, and have $\bot$ on the [[tautological_implication#Conclusion|conclusion]] side.
1. try to get rid of as many $\rightarrow$ as you can
2. once you've done that you're left with a wff you're trying to prove
3. negate that wff and make it another hypothesis
4. then make the conclusion $\bot$ and solve

--Example--
Instead of proving
$\Gamma \vdash A \rightarrow B$
you could prove
$\Gamma , A, \neg B \vdash \bot$