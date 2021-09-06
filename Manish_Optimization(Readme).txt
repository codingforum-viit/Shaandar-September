Shivam and Karan are giving a group contest. As Shivam knows Karan is not good at optimizing code so Shivam asked Karan to give his code to Manish and Manish will return optimized code to Karan. As Manish is busy in solving other problems he asked to do you the optimization. You are given 2 arrays A and B of same Length N. You have to optimize the given code.

int res = 0;
for int i = 1 to N do
---for int j = 1 to N do
-----for int k = 1 to N do
-------if (A[i] == A[j]) OR (A[j] == A[k]) OR (A[k] == A[i])
---------continue
-------else
---------set res = max(res, B[i] + B[j] + B[k])
return res

You have to print the res variable.

Input Format

The first line of the input contains an integer the number of test cases T.
The next 3.T lines contains
1st line N - number of elements
2nd line N integers of array A
3rd line N integers of array B

Constraints

1 ≤ T ≤ 10
1 ≤ N ≤ 105
1 ≤ A[i], B[i] ≤ 105

Output Format

For each test case, output an integer corresponding to the return value of the res variable.

Sample Input 0

2
3
1 3 1
3 1 2
5
1 2 1 3 3 
3 4 2 2 4
Sample Output 0

0
11
Explanation 0

Testcase 1: No i,j,k are possible in this input so answer is 0.
Testcase 2: The maximum is attained when i = 1, j = 2 and k = 5. So res becomes 3 + 4 + 4 = 11.