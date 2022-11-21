#PREDICATE_LOGIC 
#TODO 

- a variable in [[predicate_logic]] can be bound to a quantifier or free from it, depending on if it's in it's scope or not.
- Example: $B \rightarrow (\forall x) A$ 
- Any $x$ occurring in $A$ is in the scope of ($\forall x$) 
- Any $x$ occuring in $B$ is not in the scope of ($\forall x$)
- if $B$ is $x=y$ and A is $x<y$ then
	- $x=y \rightarrow (\forall x)x<y$ 
	
variable $x$ is bound if
	- it occurs in a substring $(\forall x)$, or
	- it occurs in the scope of some $(\forall x)$ 

variable $x$ is free if it is not bound

$x=y \rightarrow (\forall x)x<y$ 
first $x$: not in $(\forall x)$ nor the scope of  $(\forall x)$, therefore the first occurance of x is free  
second $x$: is in $(\forall x)$ therefore it's bound
third $x$: is in the scope of $(\forall x)$ therefore it's bound
