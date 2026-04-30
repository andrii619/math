# Proofs: Jay Cummings

## Chapter 8: Functions

### Exercises

- [ ] 8.10

#### Excercise 8.10 Page 363

Let $A$ and $B$ be finite sets with $|A|=|B|$, and suppose $f:A \to B$. Prove that $f$ is injective if and only if $f$ is surjective.

Proof:

First we will prove the forward direction. Assume that $f$ is injective. By definition of injectivity $f(a_1)=f(a_2)$ implies that $a_1=a_2$ for any $a_1,a_2 \in A$. Let $n=|A|$ and write $A=\{a_1,\dots,a_n\}$. Since $f$ is injective, the images $f(a_1),\dots,f(a_n)$ are $n$ distinct elements of $B$. But $|B|=n$, so $\{f(a_1),\dots,f(a_n)\}=B$. Hence every $b \in B$ has a preimage in $A$, so $f$ is surjective.
Next we will prove the opposite direction by proving the contrapositive of the statement. That is, we will show that if $f$ is not injective then it is also not surjective. 
Assume that $f$ is not injective. This means that there must exists some elements $a_1, a_2 \in A$ with $a_1 \neq a_2$ such that $f(a_1)=f(a_2)$. Let us apply the pigeonhole principle. Let elements $y \in B$ be boxes and elements $x \in A$ be items. Since $f$ is not injective then it means that there is at least one box that has two items in it. Since $|A|=|B|$ then by the pigeonhole principle there exists at least one box with no items in it. This means that there exists at least one element $y \in B$ that $f$ does not associate any element from $A$ with it. But this means that $f$ is not surjective by definition of surjectivity. Thus, we have shown that if $f$ is not injective then $f$ is also not surjective. By contrapositive this also means that if $f$ is injective then it is also surjective. 
We have proven both direction of our statement therefore we have proven that $f$ is injective if and only if $f$ is surjective.
