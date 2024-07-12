##  Question 1
Jayme has a list of consecutive numbers beginning with 7. Her arrangement of those numbers is called a beautiful arrangement if at least one of the following is true:  




• The number present at the ith position is divisible by i.  
• /is divisible by the number present at the ith position.  

Language C

Determine how many beautiful arrangements of her integers is possible. For example, she has n = 5 integers, [1,2,3,4,5]. Using 1-based indexing, there are the following arrangements satisfying the above:


``[1,2,3,4,5]``  
``[2,1,3,4,5]``
``[3,2,1,4,5]``
``[4,2,3,1,5]``
``[5,2,3,4,1]``
``[4,1,3,2,5]``
``[1,4,3,2,5]``
``[3,4,1,2,5]``
``[2,4,3,1,5]``
``[5,4,3,2,1]``

Autocomplete Ready
1 > #include <assert.h
*Complete the arr
*
*The function i *The function
19
20
1*
21
22
23
24
25
×1
26
27
int arranger
28
I
29
30
31> int ma

In the first row, both conditions hold for all elements: each i equals the value at index i, so each iis divisible by the element and each element is divisible by its index i. In the next row where the first two elements have been switched, where i = 1 and the value is 2, 2 is divisible by i. In the next position, index i=2 is divisible by its element value of 1. Similar logic is applied to form each of the subsequent rows.


# Function Description
Complete the function arrangements in the editor below. The function must return the number of beautiful arrangements possible.

arrangements has the following parameter(s):  

n: an integer  

1
# Constraints  

• 1 < n < 20  


# Input Format For Custom Testing
The first line contains an integer, n.

# Sample Case 0
Sample Input 0  

2  

Sample Output 0  

2  

Language
C
Autocomplete Ready
1> #include <assert.h>-
Environ
19
20 1*
21
* Complete the arrangeme
22
*
23
*The function is expe
24
*The function accep
25
*|
26
27
int arrangements
28
29
30
31 > int main()


Explanation 0
The beautiful arrangements for n=2 are [1,2] and [2,1]. Consider the arrangement [1, 2]
• The number present at the 1st position (i = 1) is 1, and 1 is divisible by i.
• The number present at the 2nd position (i = 2) is 2, and 2 is divisible by i.
Consider the arrangement [2, 1] then:
• The number present at the 1st position (i = 1) is 2, and 2 is divisible by i.
• The number present at the 2nd position (i = 2) is 1, and iis divisible by 1.
▼Sample Case 1
Sample Input 1
3
Sample Output 1
3
Explanation 1
[1,2,3]
[2,1,3]
[3,2,1]
▼Sample Case 2
Sample Input 2
Language C
Autocomplete Ready
1> #include <assert.h>
19
20
1*
21
22
*
23
24
Complete the arrange
*The function is ex
*The function acce
25
*1
26
27
int arrangement
28
29
}
30
31> int main()
