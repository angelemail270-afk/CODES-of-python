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



---------File ---------------------------Thank you—------------------Mst—--------------Complete


























 




















































(More programs coming in the future)

