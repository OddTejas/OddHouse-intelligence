# General strucutre of taking account of two or more selections

## AND - Multiplication
when two cases are joined with thier combinations or permutations, their results are multiplied.

## OR - Addition
When two cases and their results, are joined with or, both cases are independent, then their permutation and combinations are added.

## Example
__Problem:__
A bag contains 4 red balls and 3 blue balls. You randomly select 3 balls all at once. How many different ways can you choose a group of balls that contains at least 2 red balls?

For this the problem can be divided into two cases.

*Case1:* out of 3 balls 2 are red and 1 is blue
*Case2:* out of 3 balls 3 are red and 0 is blue

### Case 1
Total combinations:
 For red :$\binom{4}{2}$ __AND__ for blue $\binom{3}{1}$

 *since both possiblities are joined with and and both are possible at the same time, we multiply, to complete this __stage__*

$$\binom{4}{2} * \binom{3}{1} = 18$$

### Case 2
Total combinations:
For red :$\binom{4}{3}$ __AND__ for blue $\binom{3}{0}$

$$\binom{4}{3} * \binom{3}{0} = 4$$

*Again, since both possiblities are joined with and and both are possible at the same time, We multiply
to complete this __stage__.*
### Final assembly
the stages and cases are added to get the total condititons.
Now either case 1 __OR__ case 2 can happen to fulfill the condition, thus we __ADD__.

$\text{Total Combinations} = 18 + 4 = 22$
