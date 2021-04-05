#### Name: Adam Shinomiya
#### Date: 29 March 2021
#### What this is: Calculations from the manual work out of the Needleman-Wunsch algorithm.

### Instructions: Local Alignment calculations
For each entry in the matrix in the lab assignment, there is a letter and you are to place your calculations for each letter below. The first calculation for entry (a) is done for you. Please follow this example in your calculations for the rest of the letters.

Scoring table:


|Score or penalty| value |
|----------------|-------|
|gap penalty      |-1     |
|Mismatch penalty | 0     |
|Match score     | 1     |


a)
- Match or Mismatch: A = A is a match
- Left entry calculation: -1 - 1 = -2
- Above entry calculation: -1 -1 = -2
- Diagonal entry calculation: 0 + 1 = 1
- Max score: 1 from the Diagonal is 1


b)
- Match or Mismatch: T != A
- Left entry calculation: 1 - 1 = 0
- Above entry calculation: -2 - 1 = -3
- Diagonal entry calculation: -1 - 1 = -2
- Max score: 1 from the Diagonal is 0


c)
- Match or Mismatch: A != T
- Left entry calculation: -2 - 1 = -3
- Above entry calculation: 1 - 1 = 0
- Diagonal entry calculation: -1 - 1 = -2
- Max score: 1 from the Diagonal 0


d)
- Match or Mismatch: T = T
- Left entry calculation: 0 - 1 = -1
- Above entry calculation: 0 - 1 = -1
- Diagonal entry calculation: 1 + 1 =2
- Max score: 1 from the Diagonal is 2


e)
- Match or Mismatch: A != G
- Left entry calculation: -3 - 1 = -4
- Above entry calculation: 0 - 1 = -1
- Diagonal entry calculation: -2 - 1 = -3
- Max score: 1 from the Diagonal is -1


f)
- Match or Mismatch: G != T
- Left entry calculation: -1 - 1 = -2
- Above entry calculation: 2 - 1 = 1
- Diagonal entry calculation: 0 - 1 = -1
- Max score: 1 from the Diagonal is 1



(Did you remember to add your name to this Markdown file?)
