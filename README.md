# Exp. No: 2a ITERATIVE STATEMENTS – PRINTING N NATURAL NUMBERS
# AIM
To create a Python program for printing n natural numbers using a while loop.

# ALGORITHM
Start Input a number a Display: "Natural Numbers are :" Initialize i to 1 Repeat the following steps while i <= a: Print the value of i Increment i by 1 End

# PROGRAM
```
a=int(input())
print("Natural Numbers are :") 
i=1
while i<=a: 
 print(i) 
 i+=1
```
# OUTPUT
<img width="1209" height="623" alt="image" src="https://github.com/user-attachments/assets/42ece84a-fea2-4c38-aeb1-497e6f30531b" />

# RESULT
Thus the program to print n natural numbers using while loop has been implemented and executed successfully.

# Exp.No:2b FUNCTIONS - MODULO
# AIM
To write a Python program to define a function that accepts two values and returns their modulo value.

# ALGORITHM
Begin the program. Read two numbers a and b from the user using input(). Convert the inputs to integers using int(). Define a function result(a, b) with the following steps: Calculate the modulo using a % b and store it in a variable d. Print the result using a formatted string. Call the function result(a, b) with the user inputs. Terminate the program.

# PROGRAM
```
def result(a,b):
  d=a%b
print(f"modulo is {d}")
a = int(input())
b = int(input())
```
# OUTPUT
<img width="1193" height="306" alt="image" src="https://github.com/user-attachments/assets/657518f2-766b-47b7-8494-82a97886b9c1" />

# RESULT
Thus the program to define a function that accepts two values and returns their modulo value has been implemented and executed successfully.

# Exp.No:2c BUILT-IN FUNCTIONS AND LAMBDA FUNCTIONS - RELATING TWO NUMBERS
# AIM
To write a Python program to check the relation between two numbers — whether one number is greater than, equal to, or lesser than another — using a lambda function.

# ALGORITHM
Begin the program. Read two numbers input1 and input2 from the user using input(). Convert the inputs to integers using int(). Define a lambda function compare that takes two arguments a and b. The lambda function performs the following comparisons: If a > b, it returns the string: "a is greater than b". Else if a < b, it returns the string: "a is smaller than b". Else, it returns: "a is equal to b". Call the compare function with input1 and input2 as arguments. Print the result of the comparison. Terminate the program.

# PROGRAM
```
result = lambda x,y : f"{x} is smaller than {y}" if x < y else (f"{x} is greater than {y}" if x > y                else f"{x} is equal to {y}")
a=int(input()) 
b=int(input()
print(result(a, b))
```
# OUTPUT
<img width="1175" height="321" alt="image" src="https://github.com/user-attachments/assets/de6242b5-4067-4301-9081-4134c835dd70" />

# RESULT
Thus the program to check the relation between two number using lambda function has been implemented and executed successfully.

# Exp.No:2d LOOPING PATTERNS - PRINTING PATTERN
# AIM
To write a Python program to print a pyramid pattern of numbers based on the number of rows entered by the user.


# ALGORITHM
Begin the program. Read the number of rows a from the user using input() and convert it to an integer. Use a for loop that runs from i = 1 to a (inclusive) to handle the number of rows. Inside the loop, use a nested for loop that runs from j = 1 to i (inclusive) to print numbers in each row. Print each number j followed by a space, and keep the output on the same line using end=" ". After the inner loop ends, move to the next line using print(end="\n"). Repeat steps 4–6 until the pyramid is printed. Terminate the program.

# PROGRAM
~~~
n=int(input())
for i in range(1,n+1):
    for j in range(1,i+1):
        print(j,end=' ')
    print('')
~~~
# OUTPUT
<img width="1199" height="567" alt="image" src="https://github.com/user-attachments/assets/df9d06e4-bb84-4c8e-aa7e-fa2bf24a5eec" />

# RESULT
Thus the program to print a pyramid pattern of numbers based on the number of rows entered by the user has been implemented and executed successfully.

# Exp.No:2e SEB - SUM OF ODD NUMBER SERIES
# AIM
To write a Python program to calculate the sum of the odd number series from 1 to N using a loop.

# ALGORITHM
Start the program. Read a number num from the user using input(). Convert the input to an integer using int(). Initialize a variable sum to 0 to store the total sum. Loop from i = 1 to num (inclusive): Check if i is odd using i % 2 != 0. If true, add i to sum. After the loop, print the result in the format: "The sum of the series = " End the program.

# PROGRAM
~~~
num=int(input())
sum=0
for i in range(1,num+1):
  if(i%2!=0):
  sum+=i
print(f"The sum of the series = {sum}")
~~~
# OUTPUT
<img width="1199" height="360" alt="image" src="https://github.com/user-attachments/assets/de9cfd84-6efd-4b0e-b6eb-47b3ac671896" />

# RESULT
Thus the program to calculate the sum of the odd number series from 1 to N using a loop has been implemented and executed successfully.
