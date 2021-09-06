In VIIT ,Second Year batches have started. So the students from SY sit with their friends and they form a "Friends Group".
Each student has an id from 1-9.
There can be multiple students with same id.
Now we are given N groups of friends. Our task is to find the maximum number of groups in which each group contains atleast one friend id in common in all the other groups.
Suppose Friends Group= [12,110,3].
Here First group contains two friends with id= 1 and id =2 and Second group contains three friends with id= 1 and id =1 and id=0 and Third group contains 1 friend with id=3.
Hence the maximum number of groups in which each group contains atleast one friend id in common is 2.

Input Format

First line of input contains N, denoting number of friends group.
Second line of input contains N space separated groups, each group denoting students in it.

Constraints

1≤ N ≤105
1≤ Ai ≤109

Output Format

Single integer representing maximum nos of groups containing one id common.

Sample Input 0

5
12 11 3 4 5
Sample Output 0

2
Explanation 0

Friend with id 1 is present in 2 groups i.e. 12 and 11. So the answer would be 2.

Sample Input 1

10
121 2 0 99 1112 22 2 11111 1 2
Sample Output 1

6
Explanation 1

In first group students are of id = 1, 2
In second group students are of id= 2
In third group students are of id = 0
In fourth group students are of id= 9
In fifth group students are of id = 1, 2
In sixth group students are of id= 2
In seventh group students are of id = 2
In eigth group students are of id= 1
In nineth group students are of id = 1
In tenth group students are of id= 2
So students of id= 2 are present in 6 groups . Hence maximum friends group is 6