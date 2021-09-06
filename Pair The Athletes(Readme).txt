There are N athlete having Ai heights.
You have to form groups among the athlete.
Then make a pair of the tallest and shortest athlete from all contiguous subgroups formed.
Finally display the number of pairs formed.

Input Format

First line contains an integer, N .
Second line contains N space separated integers, Ai denoting the height of the athlete.

Constraints

1<= N <=103
1<=Ai<=105

Output Format

Print the no of pairs of athletes formed.

Sample Input 0

5
1 2 6 4 5
Sample Output 0

5
Explanation 0

The pairs are formed by taking the maximum and minimum numbers from the contiguous grouping of the array.
groups of 2 atheletes
1 2 min - 1 max - 2
2 6 min - 2 max - 6
6 4 min - 4 max - 6
4 5 min - 4 max - 5
groups of 3 atheletes
1 2 6 min - 1 max - 6
2 6 4 min - 2 max - 6
6 4 5 min - 4 max - 6
groups of 4 atheletes
1 2 6 4 min - 1 max - 6
2 6 4 5 min - 2 max - 6
groups of 5 atheletes
1 2 6 4 5 min - 1 max - 6
The 5 unique pairs are:(1, 2) (2, 6) (4, 5) (4, 6) (1, 6)

Sample Input 1

5
1 4 5 3 2 
Sample Output 1

6
Explanation 1

The unique pairs are:(1, 4) (2, 3) (3, 5) (4, 5) (1, 5) (5, 2)