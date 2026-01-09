# Proof
### Definition - Mathematical proof
A mathematical proof of a **proposition** is a chain of **logical deductions** leading to the **proposition** from a base set of **axioms**
## Propositions
### Definition - Proposition
A proposition is a statement that is either true or false
### Examples
1. 2 + 3 = 5
2. 2 + 3 = 4
3. $\forall \; n \in \mathbb{N} \; . \; n^2 + n + 41 \; \text{is prime}$
    "For all $n$ in natural numbers, $n^2 + n + 41$ is prime"
4. Euler's Conjecture
$$
\forall \; a, b, c, d \in  \mathbb{Z}^+ \; . \; a^4 + b^4 + c^4 \neq d^4 
$$
    "For all $a, b, c, d$  in positive integers, $a^4 + b^4 + c^4 = d^4$  has no solution"
    Proven to be false with $a=95800, b=217519, c=414560, d=422481$
5. Four Colour Theorem
    $\text{Every map can be coloured with 4 colours so that adjacent regions have different colours}$
6. Fermat's Last Theorem
$$
\forall \; n \in \mathbb{Z},\ n > 2 \rightarrow \nexists \; x, y, z \in \mathbb{Z}^+ : x^n + y^n = z^n
$$
    "There are no positive integers $x, y$ and $z$ such that $x^n + y^n = z^n$ for some integer $n>2$ "
7. Goldbach's Conjecture
    $\text{Every even integer greater than 2 is the sum of 2 primes}$
    Remains unproven till today
### Other Definitions
- Theorem - A theorem is an **important true** proposition
- Lemma - A lemma is a **preliminary** proposition useful for later propositions
- Corollary - A corollary is a proposition that follows in just a few logical steps from a **theorem**
## Predicates
### Definition - Predicate
A predicate is a **proposition** whose truth **depends** on the value of one or more variables
### Examples
1. $n^2 + n + 41 \; \text{is prime}$, which can also be written in a function-like notation as
$$P(n) ::= \text{``}n^2 + n + 41 \; \text{is prime"}$$
    We can assert from the predicate that $P(2) = 47$ , which fulfills the predicate with 2 as the value of $n$, creating a true proposition
    
    We can assert from the predicate that $P(40) = 1681 = 41^2$, which fulfills the predicate with 40 as the value of $n$, creating a false proposition
    
    We can assert from the predicate that $n$ belongs to a natural number, creating the proposition $\forall \; n \in \mathbb{N} \; . \; n^2 + n + 41 \; \text{is prime}$, which can be true or false
    
    Thus, if $P$ is a predicate, then $P(n)$ is either true or false, depending on the value of $n$
## The Axiomatic Method
### Definition - Axiom
An axiom is a **proposition** we **assume** is true
### Examples
1. 5 axioms from Euclidean geometry
	1. A straight line may be drawn between any two points
	2. Any terminated straight line may be extended indefinitely
	3. A circle may be drawn with any given point as center and any given radius
	4. All right angles are equal
	5. For any point $p$ and line $l$ with $p \notin l$, there $\exists$ a unique line $l^\prime$ 
	The fifth axiom is also known as Euclid's Parallel Postulate, as shown in the diagram below:
	![[euclid-parallel-postulate]]
	Multiple attempts have been made to deduce Euclid's Parallel Postulate from the first 4 axioms, until it was proven that it did not follow them, and is indeed an axiom itself.

