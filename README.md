# CODES-of-python

here some codes of c++ that we practiced in classes and assignments

&#x20;here some practicals from start to finish which we practiced in our class, so we are doing some coding now, lets get going



so our first code is hello python

simple to write hello in python or basically to print  anything in python, we just use the print function

print("python")

and when we run it i prints python. Simple as it can be, but thats not all to python if we introduce python in brief it is a programming language that is one of the most popular programming languages. It’s simple to use, packed with features and supported by a wide range of libraries and frameworks. Its clean syntax makes it beginner-friendly.

some features are :

A high-level language, used in data science, automation, AI, web development and more.

Known for its readability, which means code is easier to write, understand and maintain.

Backed by strong library support, we don’t have to build everything from scratch

Now back to our codes in this file we will be writing some codes which i learnt in lab classes and how it helped me grow in python programming and learn this language.(hands on) so what we are going to do in that first i will write a question then the answer to that question, lets begin,



q1 Write a program to print “Hello, Python”.

&#x20;Solution : print("HelloPython") #program 1 #Angel



q22. Write a program to display your name, age, and address.

Solution :

name="Angel" #as a string

age=17 #as a integer                 #program 2 #Angel A253175025010





address="India" #as a string

print(name)

print(age)

print(address)



3\. Write a program to demonstrate single-line and multi-line comments.

Solution :

\#single line comment #Angel A253175025010









\#multi line comments            #program 3

'''jkjhjgjfjhg

vgjhjh

hbjkh

hjkkkj

'''

print("lkj")

4\. Write a program to declare variables of different data types and print them.

Solution :

integer=10

float=10.45

double=10.22222

print(integer)

print(float)    # 4 #Angel A253175025010





print(double) 



5\. Write a program to read input from the user and display it.

Solution :

x=input("enter")      #program 5 #Angel A253175025010





print(x)



6\.  Write a program to swap two numbers using a temporary variable.

Solution :

a=5

b=4

c=a

a=b   # temp variable #Angel A253175025010





b=c

print(a)

print(b)  

7\.     Write a program to swap two numbers without using a temporary variable.

Solution:

a=10

b=5

a = a + b

b = a - b

a=  a - b           #without using temp program 7 #Angel A253175025010





print(a)

print(b)



8 Write a program to find the sum and product of two numbers.  

Solution:

a=4

b=7

product= a\*b

sum=a+b           #program 8 #Angel A253175025010





print(sum)

print(product)







&#x20;9 . Write a program to demonstrate Python indentation

Solution:

a=10

if(a<20):

&#x20;print("the number is less than 20")

&#x20;print("the number is between 1 to 10 ")

&#x20;                                              #program 9 (indentation)#Angel A253175025010







10\. Write a program to calculate the area of a rectangle 

Solution:

length=int(input("Enter the length:"))

breadth=int(input("Enter the breadth:"))

area = length\*breadth               # program 10 #Angel A253175025010





print("The area of rectangle is ",area)



11\.  Write a program to convert Celsius to Fahrenheit.

Solution:

temp\_celcius=int(input("Enter the temperature in celcius"))

temp\_fahrenheit=(temp\_celcius\*1.8 )+32

print(temp\_fahrenheit)                           #Angel A253175025010







12\. Write a program to find the square and cube of a number.

Solution:

a=int(input("Enter number: "))

square=a\*\*2

cube=a\*\*3s

print(square)                                              #12 #Angel A253175025010

print(cube)



13\. Write a program to display all Python keywords. 

Solution:

import keyword

\#get the list of all keywords

all\_keywords= keyword.kwlist

print(f"Total number of keywords : {len(all\_keywords)} ")   #13#Angel A253175025010





print("List of Python keywords :")

print(all\_keywords) 



14 .    Write a program to take multiple inputs in a single line. 

Solution:

\#User enters: Alice Bob Charlie

x,y,z=input("Enter three names: ").split()                 #14#Angel A253175025010





print(x,y,z)
6.  Write a program to swap two numbers using a temporary variable.
Solution :
a=5
b=4
c=a
a=b   # temp variable #Angel A253175025010


b=c
print(a)
print(b)  
7.     Write a program to swap two numbers without using a temporary variable.
Solution:
a=10
b=5
a = a + b
b = a - b
a=  a - b           #without using temp program 7 #Angel A253175025010


print(a)
print(b)

8 Write a program to find the sum and product of two numbers.  
Solution:
a=4
b=7
product= a*b
sum=a+b           #program 8 #Angel A253175025010


print(sum)
print(product)



 9 . Write a program to demonstrate Python indentation
Solution:
a=10
if(a<20):
 print("the number is less than 20")
 print("the number is between 1 to 10 ")
                                               #program 9 (indentation)#Angel A253175025010



10. Write a program to calculate the area of a rectangle 
Solution:
length=int(input("Enter the length:"))
breadth=int(input("Enter the breadth:"))
area = length*breadth               # program 10 #Angel A253175025010


print("The area of rectangle is ",area)

11.  Write a program to convert Celsius to Fahrenheit.
Solution:
temp_celcius=int(input("Enter the temperature in celcius"))
temp_fahrenheit=(temp_celcius*1.8 )+32
print(temp_fahrenheit)                           #Angel A253175025010



12. Write a program to find the square and cube of a number.
Solution:
a=int(input("Enter number: "))
square=a**2
cube=a**3s
print(square)                                              #12 #Angel A253175025010
print(cube)

13. Write a program to display all Python keywords. 
Solution:
import keyword
#get the list of all keywords
all_keywords= keyword.kwlist
print(f"Total number of keywords : {len(all_keywords)} ")   #13#Angel A253175025010


print("List of Python keywords :")
print(all_keywords) 

14 .    Write a program to take multiple inputs in a single line. 
Solution:
#User enters: Alice Bob Charlie
x,y,z=input("Enter three names: ").split()                 #14#Angel A253175025010


print(x,y,z)

15 .                   Write a program to demonstrate assignment operators.
Solution:
a = 5
b = 3


print("Initial values: a =", a, "b =", b)#Angel A253175025010




a += b  # a = a + b
print("a += b:", a)


a -= b  # a = a - b
print("a -= b:", a)


a *= b  # a = a * b
print("a *= b:", a)


a /= b  # a = a / b
print("a /= b:", a)


a %= b  # a = a % b #Angel A253175025010


print("a %= b:", a)


a **= b  # a = a ** b
print("a **= b:", a)         
      
16.       Write a program to check the type of a variable. 
Solution:
a = 5
b = 3.14
c = "hello"
d = [1, 2, 3]
e = True


print("Type of a:", type(a))  # int
print("Type of b:", type(b))  # float #Angel A253175025010
print("Type of c:", type(c))  # str
print("Type of d:", type(d))  # list
print("Type of e:", type(e))  # bool

17.  Write a program to demonstrate formatted output.
Solution:
name="Amit"
age=21 #Angel A253175025010
city="Chandigarh"                                                                     # Taking formatted output through abstraction 1
print(f"The name is {name} is {age} and he/she lives in {city}")

name="Amit"
age=21 #Angel A253175025010
city="Chandigarh"
print("the age of {}  and he/she  is of {} and he/she lives in {}".format(name,age,city))         # taking formatted output way 2     #17

18. Write a program to calculate simple interest.
Solution:
#SI program
#Step 1: input from user
p=float(input("Enter the principal amount:"))
r=float(input("Enter the rate of interest:"))#Angel A253175025010
t=float(input("Enter the time period:"))                                                    #Simple interest #18
simple_interest=(p*r*t)/100
print("simple_interest",simple_interest)

19. Write a program to print numbers from 1 to 10.
for i in range(1,11):                                 # PRINT NUMBERS FROM 1 TO 10  #19#Angel A253175025010


    print(i)

20. Write a program to demonstrate multiple assignment.
a,b,c=input("Enter the numbers").split()                                        #20
print(a,b,c)
22.  Write a program to perform the division of two numbers.
#Step 1 read the string from the user
user_string=input("enter some text:")#Angel A253175025010


#Step 2 print the string back to the console                                  #22
print("You entered:",user_string)

23.  Write a program to demonstrate running a Python script.
# demo.py
print("Hello, this is a Python script running!")
# run_script.py
import subprocess


# Run the Python script#Angel A253175025010


subprocess.run(["python", "demo.py"])



24. Write a program to display the Python version installed
import sys            #Angel A253175025010
                                   #24 part 2
print(sys.version) 


25.   Write a program to demonstrate the use of input and output functions.
# input function
a=int(input("Enter the first number "))
b=int(input("Enter the second number "))                                          #25#Angel A253175025010


sum=a+b
print(f"Sum is: {sum}") # output function

Write a program to check whether a number is even or odd.
a=int(input("enter a number"))
if (a%2==0):
  print(f"{a} is even")                       #26#Angel A253175025010


else:
  print(f"{a} is odd ")

27. Write a program to check whether a number is positive, negative, or zero.
num=float(input("Enter a number :"))
if num>0: #Angel A253175025010
 print("Positive")                                              # 27
elif num <0:
 print("Negetive")
else:
  print("Zero")

28.  Write a program to find the largest of two numbers 
num1=float(input("Enter first number:"))
num2=float(input("Enter second number:"))        #way 1 of printing the largest numnber 28
print("Largest:",max(num1,num2)) #Angel A253175025010



29.  Write a program to find the largest of three numbers.
num1=float(input("Enter first number:"))
num2=float(input("Enter second number:"))
num3=float(input("Enter the third number"))
if num1>=num2 and num1>=num3:                        #Angel A253175025010
                                                           nh7u                                 #29
  print("Largest",num1)
elif num2>=num1 and num2>=num3:
  print("Largest",num2)#Angel A253175025010


else:
  print("Largest",num3) 

30. Write a program to perform all arithmetic operations on two numbers. 
num1=float(input("Enter first number:"))
num2=float(input("Enter second number:"))
print("Addition",num1+num2)
print("Substraction",num1-num2)                    #Angel A253175025010
                                    #30
print("Multiplication",num1*num2)

31. Write a program to demonstrate comparison operators.
a=5
b=10
print("a==b",a==b) #Equal
print("a!=b",a!=b) #Not equal #Angel A253175025010


print("a>b",a>b) #Greaterthan                                                                           #31
print("a<b",a<b) #Lessthan
print("a>=b:",a>=b) #greater than or equal #Angel A253175025010


print("a<=b:",a<=b) #Less than or equal

32 Write a program to demonstrate logical operators. 
a=True
b=False
print("a and b:",a and b) #Logical AND#Angel A253175025010


print("a or b",a or b) #Logical OR                                                                  #32
print("not a",not a) #Logical NOT 

33. Write a program to demonstrate bitwise operators.
# Program to demonstrate bitwise operators
                  a = 10   # Binary: 1010
b = 4    # Binary: 0100
print("a =", a, " b =", b)
# Bitwise AND
print("a & b =", a & b)   # 1010 & 0100 = 0000 (decimal 0)
# Bitwise OR
print("a | b =", a | b)   # 1010 | 0100 = 1110 (decimal 14)
# Bitwise XOR #Angel A253175025010


print("a ^ b =", a ^ b)   # 1010 ^ 0100 = 1110 (decimal 14)
# Bitwise NOT
print("~a =", ~a)         # ~1010 = -(a+1) = -11
# Bitwise Left Shift
print("a << 1 =", a << 1) # 1010 << 1 = 10100 (decimal 20)
# Bitwise Right Shift
print("a >> 1 =", a >> 1) # 1010 >> 1 = 0101 (decimal 5) 

34. Write a program to check whether a number is divisible by 5 and 11.


# Program to check divisibility by 5 and 11
# Take input from the user
num = int(input("Enter a number: "))
# Check divisibility#Angel A253175025010


if num % 5 == 0 and num % 11 == 0:
    print(f"{num} is divisible by both 5 and 11.")
elif num % 5 == 0:
    print(f"{num} is divisible by 5 but not by 11.")
elif num % 11 == 0:
    print(f"{num} is divisible by 11 but not by 5.")
else:
    print(f"{num} is not divisible  by either 5 or 11.")



35 Write a program to find the grade of a student using if-elif-else.
# Program to find the grade of a student
# Take input from the user
marks = int(input("Enter your marks: "))
# Determine grade using if-elif-else #Angel A253175025010


if marks >= 90:
    grade = "A+"
elif marks >= 80:
    grade = "A"
elif marks >= 70:
    grade = "B"
elif marks >= 60:                                #36 #Angel A253175025010


    grade = "C"
elif marks >= 50:
    grade = "D"
else:
    grade = "F"
# Display result
print(f"Your grade is: {grade}")

36.  Write a program to print numbers from 1 to 50 using a for loop
 Solution :# Program to print numbers from 1 to 50
             for i in range(1, 51):
                print(i) #Angel A253175025010





37 .   Write a program to print even numbers between 1 and 100.
Solution:
# Program to print even numbers between 1 and 100
for i in range(2, 101, 2):   # start at 2, go up to 100, step by 2
    print(i) #Angel A253175025010





 38 . Write a program to find the sum of the first n natural numbers
# Program to find the sum of the first n natural numbers
# Take input from the user
n = int(input("Enter the value of n: "))#Angel A253175025010


# Initialize sum
total = 0                                              
# Use a for loop to add numbers from 1 to n             #38
for i in range(1, n + 1):
    total += i
# Display the result #Angel A253175025010


print(f"The sum of the first {n} natural numbers is: {total}")

39. Write a program to calculate the factorial of a number using a loop.
Solution:
# Program to calculate the factorial of a number using a loop
# Take input from the user
num = int(input("Enter a number: "))
# Initialize factorial
factorial = 1                                
# Use a for loop to calculate factorial                  #39 #Angel A253175025010


for i in range(1, num + 1):
    factorial *= i
# Display result
print(f"The factorial of {num} is: {factorial}") 


40 . Write a program to reverse a number using a while loop
# Simple program to reverse a number               #40#Angel A253175025010


num = int(input("Enter a number: "))
rev = 0
while num > 0:
    rev = rev * 10 + num % 10
    num //= 10
print("Reversed number:", rev)

41. Write a program to count the number of digits in a number.
# Program to count the number of digits in a number
num = int(input("Enter a number: "))
count = 0
# Handle zero separately
if num == 0:
    count = 1
Else:
 while num != 0:
        num //= 10   # Remove last digit
        count += 1  
print("Number of digits:", count) 

42. Write a program to generate the Fibonacci series.
# Program to generate the Fibonacci series #Angel A253175025010


n = int(input("Enter the number of terms: "))
a, b = 0, 1
print("Fibonacci series:")
for i in range(n):
    print(a, end=" ")
    a, b = b, a + b

43. Write a program to check whether a number is a palindrome.
# Program to check whether a number is a palindrome #Angel A253175025010


num = int(input("Enter a number: "))
temp = num
rev = 0
while temp > 0:
    digit = temp % 10                               #43
    rev = rev * 10 + digit
    temp //= 10
if num == rev:
    print(num, "is a palindrome")
else:
    print(num, "is not a palindrome")

44. Write a program to demonstrate the break statement.
# Program to demonstrate break statement#Angel A253175025010


for i in range(1, 11):
    if i == 5:
        print("Break encountered at i =", i)
        break
    print("i =", i)
print("Loop terminated.")

45. Write a program to demonstrate the continue statement
# Program to demonstrate the continue statement#Angel A253175025010


for i in range(1, 11):
    if i == 5:
        print("Skipping i =", i)
        Continue
print("i =", i)
print("Loop completed.")

46. Write a program to check whether a number is prime.
# Program to check whether a number is prime
num = int(input("Enter a number: "))
if num <= 1:
    print(num, "is not a prime number")
else:
    is_prime = True
    for i in range(2, int(num**0.5) + 1):  # check up to sqrt(num) 46 #Angel A253175025010


        if num % i == 0:
            is_prime = False
            break


    if is_prime:
        print(num, "is a prime number")
    else:
        print(num, "is not a prime number") 





47. Write a program to print the multiplication table of a given number.
# Program to print the multiplication table of a given number
num = int(input("Enter a number: "))
print("Multiplication Table of", num)          #47#Angel A253175025010


for i in range(1, 11):
    print(num, "x", i, "=", num * i)

48. Write a program to demonstrate membership operators.
# Program to demonstrate membership operators #Angel A253175025010


numbers = [10, 20, 30, 40, 50]
print("List of numbers:", numbers)
# Using 'in' operator
If 20 in numbers:
    print("20 is present in the list")
# Using 'not in' operator
if 25 not in numbers:
    print("25 is not present in the list")
# Demonstrating with strings #Angel A253175025010


text = "Hello Angel"
if "Angel" in text:
    print("'Angel' is present in the string")
if "Krishna" not in text:
    print("'Krishna' is not present in the string")



49. Write a program to demonstrate identity operators 
# Program to demonstrate identity operators
x = [1, 2, 3]
y = [1, 2, 3]
z = x
print("x =", x)
print("y =", y)
print("z =", z)
# Using 'is' operator
print("x is z:", x is z)       # True, because z refers to the same object as x
print("x is y:", x is y)       # False, because y is a different object with the same values#Angel A253175025010


# Using 'is not' operator
print("x is not y:", x is not y)  # True, because x and y are different objects

50.Write a program to print patterns using nested loops.
# Program to print patterns using nested loops
rows = int(input("Enter number of rows: "))
print("Right-angled triangle pattern:")     #Angel A253175025010


for i in range(1, rows + 1):
    for j in range(1, i + 1):
        print("*", end=" ")
    print()  # move to next line     

51. Write a program to create a list and display its elements.
# Program to create a list and display its elements
# Creating a list
numbers = [10, 20, 30, 40, 50]
print("List elements are:")#Angel A253175025010


for num in numbers:                                            #51
    print(num)

52. Write a program to perform insertion and deletion operations on a list.
# Program to perform insertion and deletion on a list
# Initial list
numbers = [10, 20, 30, 40, 50]
print("Original list:", numbers)
# Insertion
numbers.insert(2, 25)   # insert 25 at index 2 #Angel A253175025010


print("After insertion:", numbers)
# Deletion
numbers.remove(40)      # remove element 40 #Angel A253175025010


print("After deletion:", numbers)




 53 . Write a program to find the largest  element in a list 
numbers = [12, 45, 7, 89, 34]
print("Largest element:", max(numbers))#Angel A253175025010

54 Write a program to find the sum and average of elements in a list
 numbers = [12, 45, 7, 89, 34]
# Calculate sum
total = sum(numbers)
# Calculate average
average = total / len(numbers)
print("Sum of elements:", total)#Angel A253175025010
print("Average of elements:", average)

55. Write a program to sort a list in ascending and descending order 
numbers = [12, 45, 7, 89, 34]
# Ascending order
ascending = sorted(numbers)
# Descending order
descending = sorted(numbers, reverse=True)#Angel A253175025010
print("Ascending order:", ascending)
print("Descending order:", descending)

 
56. Write a program to remove duplicate elements from a list 
numbers = [12, 45, 7, 89, 34, 12, 45]
# Remove duplicates using set
unique_numbers = list(set(numbers))
print("List without duplicates:", unique_numbers)

57. Write a program to perform list slicing   
# Example list
numbers = [10, 20, 30, 40, 50, 60, 70]
# Slicing examples
print("Original list:", numbers)
# First three elements
print("First three elements:", numbers[:3]) #Angel A253175025010
# Elements from index 2 to 5
print("Elements from index 2 to 5:", numbers[2:6])
# Last three elements
print("Last three elements:", numbers[-3:])
# Every second element
print("Every second element:", numbers[::2])
# Reversed list
print("Reversed list:", numbers[::-1])


58. Write a program to merge two lists.
# Input two lists from the user
list1 = list(map(int, input("Enter first list: ").split()))
list2 = list(map(int, input("Enter second list: ").split()))
# Merge the lists                                             #58 #Angel A253175025010


merged = list1 + list2
print("Merged list:", merged)

59. Write a program to create and print a tuple.
# Program to create and print a tuple from user input
# Taking input from user (space-separated numbers)
user_input = input("Enter elements of the tuple separated by spaces: ")
# Converting input into a tuple of integers          #59 #Angel A253175025010
my_tuple = tuple(map(int, user_input.split()))
# Printing the tuple
print("The tuple is:", my_tuple) 
  
60. Write a program to demonstrate the immutability of tuples.
# Program to show immutability of tuples
# Create a tuple
my_tuple = (10, 20, 30)
print("Original tuple:", my_tuple)
# Try to change one element
# This will give an error because tuples cannot be changed.  #Angel A253175025010


my_tuple[0] = 100  #this is the line that gives an error 
print("Tuple after change:", my_tuple)

#without this line, the tuple does not give an error; thus, tuples are immutable, and lists are mutable in Python. This demonstrates that tuples are immutable. 

61. Write a program to convert a tuple into a list.
# Program to convert a tuple into a list
# Create a tuple
my_tuple = (10, 20, 30, 40, 50)
print("Original tuple:", my_tuple)
# Convert tuple into list                #61 #Angel A253175025010
my_list = list(my_tuple)
# Print the list
print("Converted list:", my_list)
INDEX (PYTHON PROGRAMMING FILE)


Sno.
Experiment 
Date 
Status
62
  Write a program to create a set and perform union and intersection.


17 th March 26
Done 
63
  Write a program to check whether an element exists in a set.
17 th March 26
Done
64
Write a program to create a dictionary and display its keys and values.
17th March 26 
Done
65
Write a program to add and delete elements in a dictionary.
17 th March 26
Done
66
Write a program to count the frequency of characters in a string
17 th March 26
Done
67
  Write a program to check whether a key exists in a dictionary.


17 th March 26
Done
68
Write a program to define and call a function.


31 st March 26
Done
69
Write a program to pass arguments to a function.


31 st March 26
Done
70
Write a program to demonstrate keyword arguments.


31 st March 26
Done
71
Write a program to return values from a function.



31 st March 26
Done
72
Write a program to find the factorial of a number using a function.


31 st March 26
Done
73
  Write a program to demonstrate local and global variables.


31 st March 26
Done
74
  Write a program to find the maximum of two numbers using a function.


31 st March 26
Done
75
 Write a program to check whether a string is a palindrome using a function.


31 st March 26
Done
76
.  Write a program to demonstrate variable-length arguments.


31 st March 26
Done
77
  Write a program to use built-in sequence functions.


31 st March 26
Done
78
 Write a program to find the sum of the list elements using a function.


31 st March 26
Done
79
  Write a program to iterate through a dictionary.


31 st March 26
Done
80
  Write a program to find the second-largest element in a list.


31 st March 26
Done


81


Write a program to install a package using PIP.


7th April 26
Done
82
Write a program to use the math package.


7th April 26
Done
83
.  Write a program to generate random numbers using the random package.


7th April 26
Done
84
  Write a program to import and use a Python package.


7th April 26
Done
85
 Write a program to define a class and create an object.


7th April 26
Done
86
Write a program to demonstrate the use of the self variable.


7th April 26
Done
87


Sno.
Write a program to create a class with a constructor.
Experiment
7th April 
26
Done
88
 Write a program to define methods inside a class.


7th April 26
Done
89
Write a program to access class variables and instance variables.


7th April 26
Done
90
 Write a program to demonstrate single inheritance.


7th April 26
Done
91
 Write a program to demonstrate multilevel inheritance.


7th April 26
Done
92
 Write a program to demonstrate method overriding.


7th April 26
Done
93
 Write a program to demonstrate polymorphism.


7th April 26
Done
94
 Write a program to create a student class with details.




Done
95
 Write a program to create a bank account class with deposit and withdrawal methods.


7th April 26
Done
96
 Write a program to demonstrate encapsulation using private variables.


7th April 26
Done
97
  Write a program to create a class-based calculator.


7th April 26
Done
98
  Write a program to use a Python package inside a class.


7th April 26
Done
99
.  Write a program to demonstrate constructor overloading using default arguments.


7th April 26
Done
100
Write a program to design a real-world application using OOPS concepts.
7th April 26
Done




#62.  Write a program to create a set and perform union and intersection.



# Create two sets
set1 = {1, 2, 3, 4, 5}
set2 = {4, 5, 6, 7, 8}


# Perform union
union_set = set2.union(set1)


# Perform intersection           #A253175025010
                                   #Angel
intersection_set = set1.intersection(set2)


# Display results
print("Set 1:", set1)
print("Set 2:", set2)
print("Union of sets:", union_set)
print("Intersection of sets:", intersection_set)







63 Write a program to check whether an element exists in a set.#A2531750250  #Angel
# Create a set
my_set = {10, 20, 30, 40, 50}


# Take element from user
element = int(input("Enter an element to check: "))


# Check existence  #A2531750250  #Angel


if element in my_set:
    print(element, "exists in the set.")
else:
    print(element, "does NOT exist in the set.")











64. Write a program to create a dictionary and display its keys and values.

my_set = {10, 20, 30, 40, 50}


# Take element from user
element = int(input("Enter an element to check: "))


# Check existence #A2531750250  #Angel
if element in my_set:
    print(element, "exists in the set.")
else:
    print(element, "does NOT exist in the set.")




#65. Write a program to add and delete elements in a dictionary.



# Creating a dictionary
student = {
    "name": "Palak",
    "age": 20,
    "course": "BCA"
}


print("Original Dictionary:", student)


# ---- Adding a new element ---- #A2531750250  #Angel
student["city"] = "Mohali"     # adding new key-value pair
print("After Adding Element:", student)


# ---- Deleting an element ----
del student["age"]             # deleting a key-value pair
print("After Deleting Element:", student)








 66 Write a program to count the frequency of characters in a string.
# Program to count the frequency of characters in a string


string = input("Enter a string: ")


frequency = {}  # empty dictionary #A2531750250  #Angel


for char in string:
    if char in frequency:
        frequency[char] += 1
    else:
        frequency[char] = 1


print("Character Frequency:")
for key, value in frequency.items():
    print(key, ":", value)








67.  Write a program to check whether a key exists in a dictionary.
# Create a dictionary
student = {
    "name": "Palak",
    "age": 20,
    "course": "BCA"
}


# Take key from user #A2531750250  #Angel
key = input("Enter the key to check: ")


# Check if key exists
if key in student:
    print("Key exists in the dictionary.")
else:
    print("Key does NOT exist in the dictionary.")



68. Write a program to define and call a function.
# Define a function using a lambda (no def keyword)
greet = lambda name: print("Hello,", name, "! Welcome to Python programming.")


# Call the function #A2531750250  #Angel
greet("Alice")
greet("Bob")




69 Write a program to pass arguments to a function.
# Create a function dynamically (no def, no lambda written directly)
code = """
def add_numbers(a, b):
    return a + b
"""
exec(code)   # Executes the string and defines add_numbers


# Call the function with arguments #A2531750250  #Angel
result1 = add_numbers(5, 10)
result2 = add_numbers(20, 30)


print("The sum of 5 and 10 is:", result1)
print("The sum of 20 and 30 is:", result2)







70. Write a program to demonstrate keyword arguments
 Define a function using a lambda (no def keyword)
introduce = lambda name, age, city: print(f"Name: {name}, Age: {age}, City: {city}")


# Call the function using keyword arguments#A2531750250  #Angel
introduce(name="Alice", age=25, city="New York")
introduce(city="London", name="Bob", age=30)




71. Write a program to return values from a function.
# Define a function using a lambda (no def keyword)
square = lambda x: x * x


# Call the function and store returned values
result1 = square(5)
result2 = square(10)


# Display the results #A2531750250  #Angel
print("Square of 5 is:", result1)
print("Square of 10 is:", result2)



72. Write a program to find the factorial of a number using a function 
def factorial(n):
    "Return the factorial of a given number n."""
    if n < 0:
        return "Factorial is not defined for negative numbers."
    elif n == 0 or n == 1:
        return 1
    else:
        result = 1
        for i in range(2, n + 1):
            result *= i
        return result


# Example usage: #A2531750250  #Angel
num = int(input("Enter a number: "))
print(f"The factorial of {num} is {factorial(num)}")



73. Write a program to demonstrate local and global variables.
# Global variable
x = 10
print("Global variable x =", x)


# Demonstrating a local variable inside a block
for i in range(1):
    y = 5   # local to this block
    print("Inside block:")
    print("Global variable x =", x)
    print("Local variable y =", y)


print("\nOutside block:") #A2531750250  #Angel
print("Global variable x =", x)
# Trying to access y here will still work in Python, but it's considered local to the block above.
# In a strict function scope, y would not exist outside.



74. Write a program to find the maximum of two numbers using a function.
# Function to find the maximum of two numbers
def find_max(a, b):
    if a > b:
        return a
    else:
        return b


# Call the function with arguments #A2531750250  #Angel
num1 = 15
num2 = 25


result = find_max(num1, num2)


print("The maximum of", num1, "and", num2, "is:", result)

75Write a program to check whether a string is a palindrome using a function.
# Function to check a palindrome
def is_palindrome(s):
    # Remove spaces and convert to lowercase for uniformity
    s = s.replace(" ", "").lower()
    # Compare a string with its reverse
    return s == s[::-1]


# Test the function #A2531750250  #Angel
word1 = "madam"
word2 = "hello"
word3 = "Race car"


print(f"'{word1}' is palindrome? ->", is_palindrome(word1))
print(f"'{word2}' is palindrome? ->", is_palindrome(word2))
print(f"'{word3}' is palindrome? ->", is_palindrome(word3))




76 Write a program to demonstrate variable-length arguments.
# Function with variable-length arguments #A2531750250  #Angel
def show_details(*args, **kwargs):
    print("Arguments (args):")
    for arg in args:
        print(arg)
   
    print("\nKeyword Arguments (kwargs):")
    for key, value in kwargs.items():
        print(f"{key} = {value}")


# Call the function with different numbers of arguments
show_details(10, 20, 30, name="Alice", age=25, city="New York")



77Write a program to use built-in sequence functions.
# Demonstrating built-in sequence functions #A2531750250  #Angel


numbers = [10, 25, 7, 42, 18]


print("Numbers:", numbers)


# Length of the list
print("Length of list:", len(numbers))


# Maximum value
print("Maximum value:", max(numbers))


# Minimum value
print("Minimum value:", min(numbers))


# Sum of all elements
print("Sum of elements:", sum(numbers))


# Sorted list
print("Sorted list:", sorted(numbers))


# Reversed list
print("Reversed list:", list(reversed(numbers)))

78Write a program to find the sum of list elements using a function.
# Function to calculate the sum of list elements
def list_sum(numbers):
    total = 0
    for num in numbers:
        total += num
    return total


# Example list
my_list = [10, 20, 30, 40, 50]


# Call the function   #A2531750250  #Angel
result = list_sum(my_list)


print("The list is:", my_list)
print("The sum of list elements is:", result)


79 Write a program to iterate through a dictionary.

# Define a dictionary
student = {
    "name": "Alice",
    "age": 21,
    "course": "Computer Science",
    "grade": "A"
}

# Function to iterate through a dictionary        #A2531750250  #Angel
def iterate_dictionary(d):
    for key, value in d.items():
        print(f"{key} : {value}")

# Example usage
print("Dictionary contents:")
iterate_dictionary(student)


80. Write a program to find the second-largest element in a list.
# Program to find the second largest element in a list


def second_largest(numbers):
    # Remove duplicates to handle repeated values
    unique_numbers = list(set(numbers))
   
    # Sort the list in descending order #A2531750250  #Angel
    , unique_numbers.sort(reverse=True)
   
    if len(unique_numbers) < 2:
        return None  # No second largest if list has fewer than 2 unique elements
    else:
        return unique_numbers[1]


# Example list
my_list = [10, 20, 4, 45, 99, 99, 18]


result = second_largest(my_list)


print("The list is:", my_list)
if result is None:
    print("The second largest element is:", result)
else:
    print("The list does not have a second largest element.")



#81.  Write a program to install a package using PIP.
# Program to install a package using pip

import subprocess
import sys

def install_package(package_name):          #A2531750250  #Angel
    """Install a package using pip."""
    try:
        subprocess.check_call([sys.executable, "-m", "pip", "install", package_name])
        print(f"Package '{package_name}' installed successfully!")
    except Exception as e:
        print(f"An error occurred: {e}")

# Example: install the 'requests' package
install_package("requests")

82. Write a program to use the math package.
# Program to use the math package

import math

# Using some math functions
num = 16
sqrt_val = math.sqrt(num)        # Square root
power_val = math.pow(2, 5)       # 2 raised to the power 5
factorial_val = math.factorial(5) # Factorial of 5
sin_val = math.sin(math.pi / 2)   # Sine of 90 degrees (π/2 radians)

# Using math constants
pi_val = math.pi
e_val = math.e

# Display results
print(f"Square root of {num} = {sqrt_val}")
print(f"2^5 = {power_val}")
print(f"Factorial of 5 = {factorial_val}")
print(f"Sine of π/2 = {sin_val}")
print(f"Value of π = {pi_val}")
print(f"Value of e = {e_val}")


83.  Write a program to generate random numbers using the random package.
# Program to generate random numbers using the random package

import random

# Generate a random integer between 1 and 100
rand_int = random.randint(1, 100)

# Generate a random float between 0 and 1          #A2531750250  #Angel
rand_float = random.random()

# Generate a random number from a range with step
rand_range = random.randrange(10, 100, 5)  # multiples of 5 between 10 and 100

# Pick a random element from a list
items = ['apple', 'banana', 'cherry', 'date']
rand_choice = random.choice(items)

# Shuffle a list randomly
le(items)

# Display results
print(f"Random integer (1–100): {rand_int}")
print(f"Random float (0–1): {rand_float}")
print(f"Random number from range (10–100 step 5): {rand_range}")
print(f"Random choice from list: {rand_choice}")
print(f"Shuffled list: {items}")



84.  Write a program to import and use a Python package.
# Program to import and use a Python package

import statistics

# Sample data
data = [10, 20, 30, 40, 50]

# Using functions from the statistics package, , mean_val = statistics.mean(data)       # Average
median_val = statistics.median(data)   # Middle value
stdev_val = statistics.stdev(data)     # Standard deviation          #A2531750250  #Angel

# Display results
print(f"Data: {data}")
print(f"Mean = {mean_val}")
print(f"Median = {median_val}")
print(f"Standard Deviation = {stdev_val}")


85.  Write a program to define a class and create an object.
# Program to define a class and create an object

# Define a class named 'Car..'
class Car:
    def __init__(self, brand, model, year):
        self.brand = brand
        self.model = model
        self.year = year

    def display_info(self):
        print(f"Car: {self.brand} {self.model} ({self.year})")

# Create an object of the Car class
my_car = Car("Toyota", "Corolla", 2022)

# Call the method to display car info, on
my_car.display_info()


86. Write a program to demonstrate the use of the self variable.
# Program to demonstrate the use of the self variable

class Student:
    def __init__(self, name, grade):
        self.name = name      # 'self.name' refers to the instance variable
        self. grade = grade    # 'self.grade' refers to the instance variable
#A2531750250  #Angel
    def display(self):
        print(f"Student Name: {self.name}")
        print(f"Grade: {self.grade}")

# Create an object of the Student class
student1 = Student("Angel", "A+")

# Call the display method
student1.display()


87.	Write a program to create a class with a constructor.
# Program to create a class with a constructor

class Book:
    def __init__(self, title, author, year):
        # Constructor initializes object attributes
        self. title = title
        self.author = author
        self.year = year

    def display_info(self):
        print(f"'{self.title}' by {self.author}, published in {self.year}")

# Create objects of the Book class
book1 = Book("The Alchemist", "Paulo Coelho", 1988)
book2 = Book("Wings of Fire", "A.P.J. Abdul Kalam", 1999)

# Call the method to display book info
book1.display_info()
book2.display_info()

88. Write a program to define methods inside a class.
# Program to define methods inside a class

class Calculator:
    def __init__(self, num1, num2):
        self.num1 = num1
        self.num2 = num2

    def add(self):
        return self.num1 + self.num2
#A2531750250  #Angel
    def subtract(self):
        return self.num1 - self.num2     

    def multiply(self):
        return self.num1 * self.num2

    def divide(self):
        if self.num2 != 0:
            return self.num1 / self.num2
        else:
            return "Error: Division by zero."

# Create an object of the Calculator class
calc = Calculator(10, 5)

# Call the methods
print("Addition:", calc.add())
print("Subtraction:", calc.subtract())
print("Multiplication:", calc.multiply())
print("Division:", calc.divide())

89. Write a program to access class variables and instance variables.

# Program to access class variables and instance variables

class Employee:
    # Class variable (shared by all instances)
    company_name = "TechNova Solutions"

    def __init__(self, name, salary):
        # Instance variables (unique to each object)
        self.name = name
        self.salary = salary

    def display_info(self):
        print(f"Employee Name: {self.name}")
        print(f"Salary: ₹{self.salary}")
        print(f"Company: {Employee.company_name}")  # Accessing class variable

# Create objects of the Employee class
emp1 = Employee("Angel", 75000)
emp2 = Employee("Ravi", 68000)
#A2531750250  #Angel

# Access instance and class variables
emp1.display_info()
print()  # Blank line for readability
emp2.display_info()



90. Write a program to demonstrate single inheritance.
# Program to demonstrate single inheritance

# Parent class  #A2531750250  #Angel
class Person:
    def __init__(self, name, age):
        self.name = name
        self.age = age

    def show_details(self):
        print(f"Name: {self.name}")
        print(f"Age: {self.age}")

# Child class inheriting from Person
class Student(Person):
    def __init__(self, name, age, student_id):
        super().__init__(name, age)  # Call parent constructor
        self.student_id = student_id

    def show_student(self):
        self.show_details()  # Call parent method
        print(f"Student ID: {self.student_id}")

# Create an object of the Student class
student1 = Student("Angel", 20, "S12345")

# Call the method to display student info
student1.show_student()

91.  Write a program to demonstrate multilevel inheritance.
# Program to demonstrate multilevel inheritance

# Base class
Person:
    def __init__(self, name):
        self.name = name

    def show_name(self):
        print(f"Name: {self.name}")

# Intermediate class inheriting from Person
class Student(Person):
    def __init__(self, name, student_id):
        super().__init__(name)
        self.student_id = student_id

    def show_student_id(self):
        print(f"Student ID: {self.student_id}")

# Derived class inheriting from Student
class GraduateStudent(Student):
    def __init__(self, name, student_id, thesis_title):
        super().__init__(name, student_id)
        self.thesis_title = thesis_title

    def show_thesis(self):
        print(f"Thesis Title: {self.thesis_title}")

# Create an object of GraduateStudent
grad_student = GraduateStudent("Angel", "S12345", "AI in Spiritual Storytelling")

# Call methods from all levels of inheritance
grad_student.show_name()
grad_student.show_student_id()
grad_student.show_thesis()



92. Write a program to demonstrate method overriding.
# Program to demonstrate method overriding #A2531750250  #Angel

# Parent class
class Animal:
    def speak(self):
        print("The animal makes a sound.")

# Child class overriding the speak method
class Dog(Animal):
    def speak(self):
        print("The dog barks.")

# Another child class
class Cat(Animal):
    def speak(self):
        print("The cat meows.")

# Create objects
generic_animal = Animal()
dog = Dog()
cat = Cat()

# Call the speak method on each object
, , generic_animal.speak()  # Calls Animal's method
dog.speak()             # Calls Dog's overridden method
cat.speak()             # Calls Cat's overridden method




93.  Write a program to demonstrate polymorphism.
# Program to demonstrate polymorphism  #A2531750250  #Angel

class Bird:
    def sound(self):
        print("Birds make various sounds.")

class Sparrow(Bird):
    def sound(self):
        print("Sparrow chirps.")

class Parrot(Bird):
    def sound(self):
        print("Parrot talks.")

# Function that uses polymorphism
def make_sound(bird):
    bird.sound()

# Create objects
generic_bird = Bird()
sparrow = Sparrow()
parrot = Parrot()

# Call the same method on different objects
make_sound(generic_bird)
make_sound(sparrow)

94.  Write a program to create a student class with details.
# Program to create a Student class with details #A2531750250  #Angel

class Student:
    def __init__(self, name, roll_no, grade, section):
        self.name = name
        self.roll_no = roll_no
        self.grade = grade
        self.section = section

    def display_details(self):
        print("Student Details:")
        print(f"Name     : {self.name}")
        print(f"Roll No  : {self.roll_no}")
        print(f"Grade    : {self.grade}")
        print(f"Section  : {self.section}")

# Create an object of the Student class
student1 = Student("Angel", "S101", "A+", "Blue")

# Call the method to display student details
for student1.display_details()

95.  Write a program to create a bank account class with deposit and withdrawal methods.
# Program to create a BankAccount class with deposit and withdraw methods

class BankAccount:
    def __init__(self, account_holder, balance=0):
        self.account_holder = account_holder
        self.balance = balance

    def deposit(self, amount):
        if amount > 0:
            self.balance += amount
            print(f"₹{amount} deposited. New balance: ₹{self.balance}")
        else:
            print("Deposit amount must be positive.")

    def withdraw(self, amount):
        if amount <= self.balance:
            self.balance -= amount
            print(f"₹{amount} withdrawn. New balance: ₹{self.balance}") #A2531750250  #Angel
        else:
            print("Insufficient balance.")

    def display_balance(self):
        print(f"{self.account_holder}'s current balance: ₹{self.balance}")

# Create an object of BankAccount
account1 = BankAccount("Angel", 5000)

# Perform transactions
account1.display_balance()
account1.deposit(1500)
account1.withdraw(2000)
account1.withdraw(6000)  # Should show insufficient balance


96.  Write a program to demonstrate encapsulation using private variables.
# Program to demonstrate encapsulation using private variables

class Account:
    def __init__(self, account_holder, balance):
        self.account_holder = account_holder
        self.__balance = balance  # Private variable using double underscore

    def deposit(self, amount):
        if amount > 0:
            self.__balance += amount
            print(f"₹{amount} deposited.")
        Else:  
            print("Invalid deposit amount.")  #A2531750250  #Angel

    def withdraw(self, amount):
        if amount <= self.__balance: 
            self.__balance -= amount
            print(f"₹{amount} withdrawn.")
        else:
            print("Insufficient balance.")

    def show_balance(self):
        print(f"{self.account_holder}'s balance: ₹{self.__balance}")

# Create an object
acc = Account("Angel", 5000)

# Accessing methods
acc.deposit(1000)
acc.withdraw(2000)
acc.show_balance()

# Trying to access private variable directly (not recommended)
# print(acc.__balance)  # This will raise an AttributeError

# Accessing private variable using name mangling (not recommended but possible)
print("Accessing private balance:", acc._Account__balance)


97.  Write a program to create a class-based calculator.
# Program to create a class-based calculator

class Calculator:
    def __init__(self, num1, num2):    #A2531750250  #Angel
        self.num1 = num1
        self.num2 = num2

    def add(self):
        return self.num1 + self.num2

    def subtract(self):
        return self.num1 - self.num2

    def multiply(self):
        return self.num1 * self.num2

    def divide(self):
        if self.num2 != 0:
            return self.num1 / self.num2
        else:
            return "Error: Division by zero.."

# Create an object of the Calculator class
calc = Calculator(25, 5)

# Perform operations
print("Addition:", calc.add())
print("Subtraction:", calc.subtract())
print("Multiplication:", calc.multiply())
print("Division:", calc.divide())


98.  Write a program to use a Python package inside a class.
# Program to use a Python package inside a class  #A2531750250  #Angel

import math  # Importing the math package

class MathOperations:
    def __init__(self, number):
        self.number = number

    def square_root(self):
        return math.sqrt(self.number)

    def power(self, exponent):
        return math.pow(self.number, exponent)

# Create an object of MathOperations
operation = MathOperations(16)

# Call methods
print("Square Root:", operation.square_root())
print("Power (raised to 3):", operation.power(3))


99.  Write a program to demonstrate constructor overloading using default arguments.
# Program to demonstrate constructor overloading using default arguments
#A2531750250  #Angel
class Student:
    def __init__(self, name="Unknown", roll_no=None, grade="Not Assigned"):
        self.name = name
        self.roll_no = roll_no
        self.grade = grade

    def display(self):
        print("Student Details:")
        print(f"Name     : {self.name}")
        print(f"Roll No  : {self.roll_no}")
        print(f"Grade    : {self.grade}")

# Creating objects with different constructor arguments
student1 = Student("Angel", "S101", "A+")
student2 = Student("Ravi", "S102")         # Grade will use default
student3 = Student("Priya")                # Roll No and Grade will use default
student4 = Student()                       # All values will use default

# Displaying details
student1.display()
print()
student2.display()
print()
student3.display()
print()
student4.display()


100. Write a program to design a real-world application using OOPS concepts.
# Real-world application: Library Management System
#A2531750250  #Angel
# Base class
Item:
    def __init__(self, title, author, year):
        self.title = title
        self.author = author
        self.year = year

    def display_info(self):
        print(f"Title : {self.title}")
        print(f"Author: {self.author}")
        print(f"Year  : {self.year}")

# Derived class for books
class Book(Item):
    def __init__(self, title, author, year, genre):
        super().__init__(title, author, year)
        self.genre = genre

    def display_info(self):  # Polymorphism: overriding method
        super().display_info()
        print(f"Genre : {self.genre}")

# Derived class for magazines
class Magazine(Item):
    def __init__(self, title, author, year, issue_number):
        super().__init__(title, author, year)
        self.issue_number = issue_number

    def display_info(self):  # Polymorphism
        super().display_info()
        print(f"Issue : {self.issue_number}")

# Library class using encapsulation
class Library:
    def __init__(self):
        self.__collection = []  # Private variable

    def add_item(self, item):
        self.__collection.append(item)
        print(f"Added: {item.title}")

    def show_collection(self):
        print("\nLibrary Collection:")
        for item in self.__collection:
            item.display_info()
            print("-" * 30)

# Create library and items
lib = Library()
book1 = Book("The Alchemist", "Paulo Coelho", 1988, "Fiction")
mag1 = Magazine("National Geographic", "Various", 2023, "April")

# Add items to library
lib.add_item(book1)
lib.add_item(mag1)

# Display all items
lib.show_collection() 
#Set2:Write a Python program that accepts a password (string)from the user and checks whether it meets the following conditions: length of the password should be at least 8 characters,
 #it must contain at least one digit, and it must contain at least one uppercase letter.
 #if the password does not satisfy the required criteria, prompt the user to enter the password again. Once a valid password is entered, display the passwordand  terminate the loop
#CORRECTED PASSWORD
# Password validation program
while True:
    password = input("Enter a password: ")


    # Check each rule
    has_min_length = len(password) >= 8
    has_digit = any(ch.isdigit() for ch in password)
    has_upper = any(ch.isupper() for ch in password)


    # If all rules met, print and break
    if has_min_length and has_digit and has_upper:
        print("Valid password:", password)
        break
    else:
        # Tell the user what's missing and loop again
        print("Invalid password. Please ensure it meets all the following:")
        if not has_min_length:
            print("- At least 8 characters long")
        if not has_digit:
            print("- Contains at least one digit (0-9)")
        if not has_upper:
            print("- Contains at least one uppercase letter (A-Z)")
        print("Try again.\n")


#SET 2 Write a Python program that accepts 10 integer values from the user and stores them in a list.
#Find how many times a specific number occurs in the list and display its position. Arrange the elements in ascending order and then reverse the order of the elements.
#Create a duplicate copy of the list and display it. At the end ,remove all elements from the original list and display the result.
# Program using a while loop for input
L1 = []
i = 0


# Step 1: Accept 10 integer values using a while loop
print("Enter 10 integer values:")
while i < 10:
    num = int(input(f"Enter number {i+1}: "))
    L1.append(num)
    i += 1


print("\nOriginal List:", L1)


# Step 2: Find how many times a specific number occurs and display its positions
search_num = int(input("\nEnter the number to search: "))
count = L1.count(search_num)


if count > 0:
    print(f"\nThe number {search_num} occurs {count} times.")
    positions = [i for i, val in enumerate(L1) if val == search_num]
    print("Positions:", positions)
else:
    print(f"\nThe number {search_num} does not occur in the list.")


# Step 3: Arrange elements in ascending order
L1.sort()
print("\nList in Ascending Order:", L1)


# Step 4: Reverse the order of elements
L1.reverse()
print("List in Descending Order:", L1)


# Step 5: Create a duplicate copy of the list
L2 = L1.copy()
print("\nDuplicate Copy of List:", L2)


# Step 6: Remove all elements from the original list
L1.clear()
print("Original List after removing all elements:", L1)
(Task 1 )
#Design a class Library that maintains a collection of books.
#Each book should have attributes like title and author.
#Implement methods to add books, remove books, and search for a book by title. Make sure your search method handles cases where the book is not found.
class Book:
    def __init__(self, title, author):
        self.title = title
        self.author = author


    def __str__(self):
        return f"'{self.title}' by {self.author}"




class Library:
    def __init__(self):
        self.books = []


    def add_book(self, book):
        """Add a Book object to the library."""
        self.books.append(book)
        print(f"Added: {book}")


    def remove_book(self, title):
        """Remove a book by title. Handles case if not found."""
        for book in self.books:
            if book.title.lower() == title.lower():
                self.books.remove(book)
                print(f"Removed: {book}")
                return
        print(f"No book found with title '{title}'.")


    def search_book(self, title):
        """Search for a book by title. Returns the book or a message if not found."""
        for book in self.books:
            if book.title.lower() == title.lower():
                print(f"Found: {book}")
                return book
        print(f"No book found with title '{title}'.")
        return None




# Example usage:
library = Library()


book1 = Book("The Great Gatsby", "F. Scott Fitzgerald")
book2 = Book("1984", "George Orwell")


library.add_book(book1)
library.add_book(book2)


library.search_book("1984")
library.remove_book("The Great Gatsby")
library.search_book("The Great Gatsby")

(Task 2)
Write a Python program to implement a food delivery billing system using inheritance and method overriding. Create a base class Order with a method bill(amount, distance=0, time=None) that returns the base bill equal to the order amount. Then create two derived classes, RegularOrder and ExpressOrder, that override the bill() method. In the RegularOrder class, if the delivery distance is more than 10 km, the order should not be allowed, and an appropriate message should be displayed; if the time is "peak", a 15% extra charge should be added, otherwise the normal bill should be returned. In the ExpressOrder class, the order should always be allowed, with an additional fixed delivery charge of ₹50; if the distance is less than 5 km, a 10% discount should be applied, otherwise the normal bill should be charged. The program should take input for amount, distance, time, and type of order, and display the final bill.
class Order:
    def bill(self, amount, distance=0, time=None):
        " Base bill: returns the order amount."""
        return amount




class RegularOrder(Order):
    def bill(self, amount, distance=0, time=None):
        "Regular order billing logic."""
        if distance > 10:
            print("❌ Regular orders cannot be delivered beyond 10 km.")
            return None
        if time == "peak":
            total = amount + (0.15 * amount)
            print(f"Peak hour charge applied (15% extra).")
        else:
            total = amount
        return total




class ExpressOrder(Order):
    def bill(self, amount, distance=0, time=None):
        "Express order billing logic."""
        delivery_charge = 50
        total = amount + delivery_charge
        if distance < 5:
            discount = 0.10 * total
            total -= discount
            print(f"✅ 10% discount applied for short distance (<5 km).")
        else:
            print(f"Fixed delivery charge ₹{delivery_charge} applied.")
        return total




# --- Main Program ---
amount = float(input("Enter order amount (₹): "))
distance = float(input("Enter delivery distance (km): "))
time = input("Enter time (peak/off-peak): ").strip().lower()
order_type = input("Enter type of order (regular/express): ").strip().lower()


if order_type == "regular":
    order = RegularOrder()
elif order_type == "express":
    order = ExpressOrder()
else:
    print("Invalid order type.")
    exit()


final_bill = order.bill(amount, distance, time)
if final_bill is not None:
    print(f"\nFinal Bill Amount: ₹{final_bill:.2f}")




(Task 3)
#Write a Python program to design a hotel booking system using multiple inheritance. Create a base class Room that stores the room type (e.g., "Standard", "Deluxe") and price per night, and includes a method display_room() to show room details. Create another base class Booking that stores the number of nights and number of guests and includes a method calculate_cost() to compute the total cost as price per night multiplied by the number of nights. Then create a derived class HotelBooking that inherits from both Room and Booking, and adds a method final_amount() to adjust the total cost such that if the number of nights is more than 3, a 10% discount is applied, and if the room type is "Deluxe", a 20% surcharge is added. The program should take input for room type, price, nights, and guests, and display the room details, total cost before adjustment, and final payable amount.
class Room:
    def __init__(self, room_type, price_per_night):
        self.room_type = room_type
        self.price_per_night = price_per_night


    def display_room(self):
        print(f"Room Type: {self.room_type}")
        print(f"Price per Night: ₹{self.price_per_night}")




class Booking:
    def __init__(self, nights, guests):
        self.nights = nights
        self.guests = guests


    def calculate_cost(self, price_per_night):
        return price_per_night * self.nights




class HotelBooking(Room, Booking):
    def __init__(self, room_type, price_per_night, nights, guests):
        Room.__init__(self, room_type, price_per_night)
        Booking.__init__(self, nights, guests)


    def final_amount(self):
        base_cost = self.calculate_cost(self.price_per_night)
        final_cost = base_cost


        # Apply discount if nights > 3
        if self.nights > 3:
            discount = 0.10 * final_cost
            final_cost -= discount
            print("✅ 10% discount applied for staying more than 3 nights.")


        # Apply surcharge if Deluxe room
        if self.room_type.lower() == "deluxe":
            surcharge = 0.20 * final_cost
            final_cost += surcharge
            print("⚠️ 20% surcharge applied for Deluxe room.")


        return base_cost, final_cost




# --- Main Program ---
room_type = input("Enter room type (Standard/Deluxe): ").strip()
price_per_night = float(input("Enter price per night (₹): "))
nights = int(input("Enter number of nights: "))
guests = int(input("Enter number of guests: "))


booking = HotelBooking(room_type, price_per_night, nights, guests)


print("\n--- Booking Details ---")
booking.display_room()
print(f"Number of Nights: {nights}")
print(f"Number of Guests: {guests}")


base_cost, final_cost = booking.final_amount()
print(f"\nTotal Cost before adjustment: ₹{base_cost:.2f}")
print(f"Final Payable Amount: ₹{final_cost:.2f}")





(Task 4)
Write a Python program to implement a student performance system using multilevel inheritance. Create a base class Student that stores the roll number and name and includes a method display_student() to show student details. Then create a derived class Marks that inherits from Student and stores marks of three subjects, along with a method total_marks() to calculate the total marks. Further, create another derived class Result that inherits from Marks and includes a method calculate_grade() to determine the grade based on total marks, such that marks greater than or equal to 80 correspond to Grade A, marks between 60 and 79 correspond to Grade B, marks between 40 and 59 correspond to Grade C, and marks below 40 correspond to Fail. The program should take input for student details and marks, and display the student information, total marks, and final grade.
class Student:
    def __init__(self, roll_no, name):
        self.roll_no = roll_no
        self.name = name


    def display_student(self):
        print(f"Roll Number: {self.roll_no}")
        print(f"Name: {self.name}")




class Marks(Student):
    def __init__(self, roll_no, name, m1, m2, m3):
        super().__init__(roll_no, name)
        self.m1 = m1
        self.m2 = m2
        self.m3 = m3


    def total_marks(self):
        return self.m1 + self.m2 + self.m3




class Result(Marks):
    def __init__(self, roll_no, name, m1, m2, m3):
        super().__init__(roll_no, name, m1, m2, m3)


    def calculate_grade(self):
        total = self.total_marks()
        if total >= 80:
            grade = "A"
        elif 60 <= total < 80:
            grade = "B"
        elif 40 <= total < 60:
            grade = "C"
        else:
            grade = "Fail"
        return grade




# --- Main Program ---
roll_no = input("Enter Roll Number: ")
name = input("Enter Name: ")
m1 = int(input("Enter marks for Subject 1: "))
m2 = int(input("Enter marks for Subject 2: "))
m3 = int(input("Enter marks for Subject 3: "))


student_result = Result(roll_no, name, m1, m2, m3)


print("\n--- Student Performance ---")
student_result.display_student()
total = student_result.total_marks()
print(f"Total Marks: {total}")
print(f"Final Grade: {student_result.calculate_grade()}")























---------File ---------------------------Thank you—------------------Mst—--------------Complete


























 




















































(More programs coming in the future)

