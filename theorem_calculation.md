let $\Gamma$ be a given set of [[well_formed_formula|formulae]](or assumptions)
A theorem calculation/proof from $\Gamma$ is any finite (ordered) sequence of formulase that can be written following these rules:

### Theorem Calculation Rules
1: we my write a formula from $\Lambda$ or $\Gamma$ at any step (an [[logical_axiom]] or [[rules_of_inference|assumpton]])
2: we may write the denominator of an instance of an [[rules_of_inference|inference rule]], provided all formulae in the nuerator of the same instance have been written in a previous step. So we could write $C[\textbf{p}:=A] \equiv C[\textbf{p}:=B]$ (bottom half of [[rules_of_inference#Leibniz|Libniz rule]]) only if $A \equiv B$ was written in a previous step. (the top half)