
# Proofs: Jay Cummings

## Chapter 3: Sets

### Exercises

- [ ] 3.3 (b), (c), (k), (j)
- [ ] 3.5 (a), (b), (c), (d)
- [ ] 3.8
- [ ] 3.10
- [ ] 3.15
- [ ] 3.23
- [ ] 3.26
- [ ] 3.27
- [ ] 3.31 (a)
- [ ] 3.40 (a)



#### Excercise 3.8

Determine whether each of the following is true or false.

a) $1 \in \{1,\{1\}\}$
true
b) $1 \subseteq \{1,\{1\}\}$
false. Element 1 is not a set so it cannot be a subset.
c) $1 \in \mathcal P(\{1,\{1\}\})$
False. Elements of P are ∅, {1}, {{1}}, {1,{1}} which are all sets and 1 is not a set, its an object.
d) $\{1\} \in \{1,\{1\}\}$
true
e) $\{1\} \subseteq \{1,\{1\}\}$
true
f) $\{1\} \subseteq \mathcal P(\{1,\{1\}\})$
true
g) $\{\{1\}\} \in \{1,\{1\}\}$
false
h) $\{\{1\}\} \subseteq \{1,\{1\}\}$
True.
{{1}} is the set whose only element is {1}
To check subset: is {1}∈{1,{1}}?Yes.


i) $\{\{1\}\} \in \mathcal P(\{1,\{1\}\})$
True.

For any set (S),
$
A \in \mathcal P(S)\quad \Longleftrightarrow\quad A \subseteq S.
$

So here:
$
\{\{1\}\} \in \mathcal P(\{1,\{1\}\}) \iff \{\{1\}\} \subseteq \{1,\{1\}\}.
$

Now verify the subset statement:

* The only element of $\{\{1\}\}$ is $\{1\}$.
* And $\{1\} \in \{1,\{1\}\}$ is **true** (it’s listed).

Therefore $\{\{1\}\} \subseteq \{1,\{1\}\}$, hence:
$\{\{1\}\} \in \mathcal P(\{1,\{1\}\})$ is **True** ✅.

j) $\varnothing \in \mathbb N$
false
k) $\varnothing \subseteq \mathbb N$
true
l) $\varnothing \in \mathcal P(\mathbb N)$
true
m) $\mathbb Q \times \mathbb Q \subseteq \mathbb R \times \mathbb R$
true
n) $\mathbb R^2 \subseteq \mathbb R^3$
False.
o) $\varnothing \subseteq {1,2,3} \times {a,b}$
true
