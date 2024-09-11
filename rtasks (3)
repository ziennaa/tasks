# -*- coding: utf-8 -*-

"""
Q1: Write a program to determine if the sum of two numbers
is divisible by 7 (using if-else) and divisible
 by 5 (using a ternary operator).
 """
n1=int(input("enter a number: "))
n2=int(input("enter a number: "))
sum=n1+n2
print("divisible" if sum % 7 == 0 and sum % 5 == 0 else "not divisible")

"""
Q2: Write a program to calculate the factorial of a given number using a for loop.
"""
n=int(input("enter a number: "))
a=1
for i in range(1, n+1, 1):
  a=a*i
print("Factorial of", n, "is", a)

"""
Q3: Write a program that:
Uses a function to determine if a given string is a palindrome.
In the main function, swaps the case of all letters
in the original string (e.g., Input: aBC, Output: Abc).
"""
def palindrome(w):
  w=w.lower()
  if w==w[::-1]:
    print("It's a palindrome")
  else:
    print("It's not a palindrome")
w=input("enter a word: ")
palindrome(w)
M=list(w)
k=[]
for i in M:
  if i==i.lower():
    i=i.upper()
    k.append(i)
  else:
    i=i.lower()
    k.append(i)
m="".join(map(str, k))
print(m)

"""
Q4: Write a program to:
Find the transpose of a given matrix.
Calculate the sum of the elements in each column of the original matrix.
"""
#writing a matrix
c=int(input("enter no of coloumns: "))
r=int(input("no of ROWS: "))
MATRIX=[]
COLOUMN=[]
#enter elements
for i in range(1, r+1, 1):
  ROW=[]
  for j in range(1, c+1, 1):
    element=int(input(f"Enter A[{i}][{j}]: "))
    ROW.append(element)
  MATRIX.append(ROW)
print("Matrix A")
#printing matrix first
for i in MATRIX:
  print(i)
#taking a transpose
TRANSPOSE=[]
for i in range(c):
  TRANSPOSE.append([])
print("Transpose of Matrix A")
for i in range(r):
  for j in range(c):
    TRANSPOSE[j].append(MATRIX[i][j])
for i in TRANSPOSE:
  print(i)
#sum of coloumns
for j in range(c):
    col_sum = 0
    for i in range(r):
        col_sum += MATRIX[i][j]
    print("Sum of column", j+1, ":", col_sum)