 ¬ ⇒ ∧ ∨ 

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

1.  Step | Claim | Justification
	-----|-------|--------------
	1 | (p ∧ q) ∧ r | premise
	2 | s ∧ t | premise
	3 | p ∧ q | *AndElim1*(1)
	4 | q | *AndElim2*(3)
	5 | s | *AndElim1*(2)
	6 | q ∧ s | *AndIntro*(4, 5)













