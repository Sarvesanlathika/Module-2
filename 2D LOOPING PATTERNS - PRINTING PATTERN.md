# Exp.No:2(d) LOOPING PATTERNS- PRINTING PATTERN

# AIM
To write a program to print inverted pyramid pattern with the same digit.

# ALGORITHM
1.Start

2.Read integer a from the user

3.Loop from i = a down to 1 (inclusive):

4.for i in range(a, 0, -1)

5.Inside the outer loop, loop from j = 0 to i - 1:

6.for j in range(0, i)

7.Print the value of a followed by a space (keep on same line)

8.Print a newline after the inner loop to move to the next row

9.End

# PROGRAM
```
# REGNO:-212222060229
# Name:-sarvesan lathika
a=int(input())
for i in range(a,0,-1):
    for j in range (0,i):
        print(a,end=" ")
    print()
```
# OUTPUT
<img width="451" height="529" alt="image" src="https://github.com/user-attachments/assets/e85a2a27-37ae-439f-8dde-b91de54c27e6" />


# RESULT
Thus the python program to program to print inverted pyramid pattern with the same digit has been implemented and executed successfully.
