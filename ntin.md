# (a) Question: Using truth table, show that : p → q ≡ ~p ∨ q

Ans: 
| p | q | p → q | ~p | ~p ∨ q |
|---|---|-------|----|---------| 
| T | T | T     | F  | T       |
| T | F | F     | F  | F       |
| F | T | T     | T  | T       |
| F | F | T     | T  | T       |

The truth values for p → q and ~p ∨ q are identical, proving their logical equivalence.

## (b) Question: Prove that √2 is irrational

Ans: Proof by contradiction:
1. Assume √2 = a/b (rational number)
2. a/b in lowest terms (no common factors)
3. Square both sides: 2 = a²/b²
4. Multiply by b²: 2b² = a²
5. a² is even, so a must be even
6. a = 2k
7. 2b² = 4k²
8. b² = 2k²
9. b² is even, so b is even

Contradiction! Hence, √2 is irrational.

## (e) Question: Find the domain for which the functions are equal
f(x) = 3x² - 1 and g(x) = x + 5

Ans: 
Solve: 3x² - 1 = x + 5
3x² - x - 6 = 0
(3x + 2)(x - 3) = 0
x = -2/3 or x = 3

## (f) Question: In how many ways can a student choose 8 questions out of 10 questions?

Ans: 
Combination: ¹⁰C₈ = 10! / (8! * 2!) = 45 ways

## (g) Question: Prove the following logical statement
∀x: (x ∨ ~x)

Ans: 
This is a tautology - always true for any x
Demonstrates the law of excluded middle in logic

## (h) Question: Find f(g(x)) and (fg)(x)
f(x) = 1/x, g(x) = 3/x²

Ans:
f(g(x)) = 1/(3/x²) = x²/3
(fg)(x) = (1/x) * (3/x²) = 3/x³

## (i) Question: Use mathematical induction to prove
1² + 2² + 3² + ... + n² = n(n+1)(2n+1)/6

Ans: 
Base case (n=1): 1² = 1(1+1)(2*1+1)/6 = 1 ✓
Inductive step involves proving for k+1 given the assumption for k

## (j) Question: How many distinct three-letter words can be formed from "MUST"?

Ans: 
Total permutations: 4! = 24 ways


# Question 4

### (a) Question: Let A = {a,b,c,d}, B = {1,2,3}, and R = {(a,2), (b,1), (c,1), (d,2)}. Is R a function?

Ans:
To be a function, each element in the domain (first set) must map to exactly one element in the codomain.

Checking domain elements:
- a maps to 2
- b maps to 1
- c maps to 1
- d maps to 2

Each element in A maps to exactly one element in B, so R IS a function.

### (b) Question: Show that in any group of 30 people, we can always find 5 people who were born on the same day of the week.

Ans:
Using Pigeonhole Principle:
- Total days in a week = 7
- Total people = 30
- 30 ÷ 7 = 4 remainder 2
- This means at least one day must have 5 or more people born on it
- Therefore, 5 people must share the same day of birth in a week

### (c) Question: Write short notes on Modus-Ponens and Disjunctive Syllogism

Ans:
**Modus-Ponens (Affirming the Antecedent):**
- Logical argument form
- Structure: 
  1. If P, then Q
  2. P is true
  3. Therefore, Q is true
- Example: 
  1. If it rains, the ground is wet
  2. It is raining
  3. Therefore, the ground is wet

**Disjunctive Syllogism:**
- Logical argument form
- Structure:
  1. Either P or Q
  2. Not P
  3. Therefore, Q
- Example:
  1. Either it's raining or sunny
  2. It's not raining
  3. Therefore, it's sunny

## Question 5

### (a) Question: Show that for integers greater than zero: 2^(n+1) - 1 ÷ n

Ans:
Proof by induction:
1. Base case (n=1):
   2^(1+1) - 1 = 3 
   3 is divisible by 1 ✓

2. Inductive step:
   Assume true for k
   Prove for k+1:
   2^(k+2) - 1 should be divisible by (k+1)

### (b) Question: Let A and B be mutually exclusive events with P(A) = 0.6 and P(B) = 0.3

(i) Probability that A does not occur
Ans: 1 - P(A) = 1 - 0.6 = 0.4

(ii) Probability that A and B occur simultaneously
Ans: Since A and B are mutually exclusive, 
P(A and B) = 0 (cannot occur together)

### (c) Question: Reduce the expression F(a,b,c) = (a∨b∨c)(a∨b∨c)(a∨b∨c)

Ans:
Simplify by removing redundant terms:
= a∨b∨c

### (d) Question: Prove 1/nCr + 1/(n-r)Cr = 1/n+1Cr

Ans:
Algebraic manipulation of combination formulas
Involves expanding and simplifying combination terms
Uses properties of binomial coefficients

