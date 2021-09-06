Leo is a very lazy guy and he loves to watch web series. His teacher gives him a some task. As he is busy in watching money heist season 5, so he needs your help to solve the given task.
Teacher gives a positive integer n, and an array arr of size n. And he gave the task to leo to count the number of pairs of (x,y) such that x is less than y and (arr[x] & arr[y]) >= (arr[x] ⊕ arr[y]) where & is bitwise AND operation, and ⊕ denotes bitwise XOR operation.
Can you solve this task?

Input Format

The first line of each test case contains one positive integer n (1<=n<=105) — length of the array. The second line contains n positive integers arr[x] (1<=arr[x]<=109) — elements of the array

Constraints

1<=n<=105
1<=arr[x]<=109

Output Format

Print the count of total no. of pairs

Sample Input 0

5
1 4 3 7 10
Sample Output 0

1
Explanation 0

In the first test case there is only one pair: (4,7): for it 4 & 7=4, and 4⊕7=3.

Sample Input 1

4
6 2 5 3
Sample Output 1

2
Explanation 1

In this test case there are two pairs: (6,5) and (2,3).