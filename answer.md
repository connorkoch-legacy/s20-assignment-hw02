### Task 1 ###

1.  - p = John was jealous of Jane
	- q = John was in a good mood

	`p ∨ ¬q`

2.  - p = Smith has installed central heating
    - q = Smith has sold his car
    - r = Smith has paid his mortgage

	`p ⇒ (q ∨ ¬r)`

3.  - p = The barometer falls
    - q = It will rain
    - r = It will snow

	`p ⇒ (q ∨ r)`


### Task 2 ###

1. ((p ⇒ q) ∧ (¬((r ∨ p) ⇒ q)))
2. (p ∨ ((¬q) ⇒ (p ∧ r)))
3. ((p ∨ p) ⇒ (¬q))


### Task 3 ###

1.  `(p ∧ q) ∧ r, s ∧ t ⊢ q ∧ s`

	Step | Claim | Justification
	-----|-------|--------------
	1 | (p ∧ q) ∧ r | premise
	2 | s ∧ t | premise
	3 | p ∧ q | *AndElim1*(1)
	4 | q | *AndElim2*(3)
	5 | s | *AndElim1*(2)
	6 | q ∧ s | *AndIntro*(4, 5)

2.  `p ∧ q ⊢ q ∧ p`

    Step | Claim | Justification
    -----|-------|--------------
    1 | p ∧ q | premise
	2 | q | *AndElim2*(1)
	3 | p | *AndElim1*(1)
	4 | q ∧ p | *AndIntro*(2, 3)

2.  `p ⇒ (p ⇒ q), p ⊢ q`

    Step | Claim | Justification
    -----|-------|--------------
    1 | p ⇒ (p ⇒ q) | premise
	2 | p | premise
	3 | p ⇒ q | *ImpElim*(1, 2)
	4 | p | assumption
	5 | q | *ImpElim*(3, 4)

4.  `p ⇒ q ⊢ ¬q ⇒ ¬p`

    Step | Claim | Justification
    -----|-------|--------------
    1 | p ⇒ q | premise
	2 | 

	TODO: How to do? 1. How are the natural deduction rules derived if they are separate from truth values? 2. What does it mean to make an assumption, and how can this assumption be made (Ex. 1.16)

5.  `r, p ⇒ (r ⇒ q) ⊢ p ⇒ (q ∧ r)`

    Step | Claim | Justification
    -----|-------|--------------
    1 | r | premise
    2 | p ⇒ (r ⇒ q) | premise
	3 | 


### Task 4 ###

1. `p ⇒ (¬q ∨ (q ⇒ p))`

	![graph 1](parse-tree-1.png)

2. `¬p ∨ (p ⇒ q)`

	![graph 2](parse-tree-2.png)

3. `(p ∧ q) ⇒ (¬r ∨ (q ⇒ r))`

	![graph 3](parse-tree-3.png)







