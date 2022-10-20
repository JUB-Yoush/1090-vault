- a state v is a function that assigns a [[truth_value]] to a [[boolean_variable]]
it always assigns f to $\bot$ and t to $\top$

- state v is an infinite table, as there are infinitely many possible subscripts or primes to a [[boolean_variable]], but we only write the values for the ones present within the formula

- we can also use state v to get the truth values of entire [[well_formed_formula|wff]] by treating them as [[boolean_functions|boolean functions]]

- calling a state v on a wff is like calling the boolean variable on it, and it works recusivley down to return multiple values
$v((\neg A)) = F\neg(v(A))$
