# competetive-coding
# interesting and important
#Number of Anagramic Groups
You are given N strings of length M, count the number of anagramic groups. An anagramic group is a list of strings which are anagrams of each other.

Input Format

First line of input contains T - number of test cases. In each test case, the first line contains N - the number of strings and M - the length of each string, separated by a space. The N subsequent lines each contain a string of length M.

Constraints

1 <= T <= 100
1 <= N <= 100
1 <= M <= 1000
'a' <= str[i] <= 'z'

Output Format

For each test case, print the count of the number of anagramic groups in the given N strings, separated by newline.

Sample Input 0

2
5 4
arts
rank
star
rant
rats
9 5
tesla
start
slate
salte
tarts
aster
arson
astle
norse
Sample Output 0

3
5

Explanation 0

Test-Case 1
The strings "arts", "star" and "rats" can be grouped together because they are anagrams of each other. 
The total number of such groups is 3 and the groups are {"arts", "rats", "star"}, {"rant"} and {"rank"}.

****code****
from collections import Counter
for _ in range(int(input())):
    n,s = map(int,input().split())
    l = []
    res = []
    for i in range(n):
        s = input()
        l = [*s]
        l.sort()
        res.append("".join(l))
    d = Counter(res)
    print(len(d))
    
        
