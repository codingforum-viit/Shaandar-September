Priyanka is playing with a string S containing only '0' and '1'. Now she wants to divide this string into minimum number of subsequences in such a way that the subsequence should not contain two adjacent zeros or ones (i.e. like 101010... or 010101...). She is asking you to divide this string in minimum number of subsequences and return which character belongs to which subsequence and she also wants this array to be lexicographically smallest. See test case for more clarifications.
Note - Subsequence is a sequence that can be derived from the given sequence by deleting zero or more elements without changing the order of the remaining elements. for ex. for 10111 subsequences are 1, 0, 11, 111, 10, 01, 0111,etc but not 110 ,1110.

Input Format

contains 2 lines
1st n
2nd string s

Constraints

n - length of string s. 1<=n<=105
string only contains '0' and '1'

Output Format

1st line k number of subsequences 2nd line n integers a1,a2,…,an , where ai is the number of subsequence the i-th character of s belongs to.

Sample Input 0

4
0011
Sample Output 0

2
1 2 1 2
Explanation 0

we only need 2 subsequences. answers can be 1 2 2 1 and 1 2 1 2 but 2nd is lexicographically smaller than the 1st. 1 2 1 2 means s[0] belongs to 1st subsequence, s[1] belongs to 2nd subsequence, s[2] belongs to 1st subsequence and s[3] belongs to 2nd subsequence.