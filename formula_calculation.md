- An ordered sequence of [[well_formed_formula]] that show complex [[string]] being formed piece by piece, with each new string adding a new part to the formula.
-
	1. you can add any new [[boolean_variable]] or constant ( vars must be written in () but const don't)
	2. you can negate any existing boolean var or const $(\neg A)$
	3. you can add a [[boolean_alphabet#Boolean Connectives|connective]] between any[[boolean_variable]] or const $(A \lor B)$

Example:
$p,q,(\neg q),(p \land (\neg q))$