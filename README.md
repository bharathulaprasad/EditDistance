# EditDistance

S1=ABRGQSE
S2=YBRGEQUS

in python evaluating this is very simple.
import editdistance
editdistance.eval('ABRGQSE', 'YBRGEQUS')

How shoud we calculate it by Dynamic programming is of interest.

Solution:
Minimum Edit Distance									
	#	Y	B	R	F	E	Q	U	S
#	0	1	2	3	4	5	6	7	8
A	1	1	2	3	4	5	6	7	8
B	2	2	1	2	3	4	5	6	7
R	3	3	2	1	2	3	4	5	6
G	4	4	3	2	2	3	4	5	6
Q	5	5	5	3	3	3	3	4	5
S	6	6	6	4	4	4	4	4	4
E	7	7	7	5	5	4	5	5	5
![image](https://user-images.githubusercontent.com/76819369/156381352-39feadf6-b1c6-4f6c-a37d-eb33e5747ff5.png)
