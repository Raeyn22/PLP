# PLP Python Week One Assignment;
# A Simple Calculator Made with Python.
# The code for the simple computer:
def add(x, y):
  return x + y

def subtract(x, y):
  return x - y

def multiply (x, y):
  return x * y

def divide(x, y):
  if y !=0:
    return x / y
  else:
    return 'Invalid'

operation=input('Choose an operation:+ add, - subtract, * multiply, / divide:  ')

num1=int(input('Enter 1st number:  '))
num2=int(input('Enter 2nd number:  '))

#Addition
if operation=='+':
 print(num1, '+', num2, '=', add(num1, num2))
 print(num1+num2)
#Subtraction
elif operation=='-':
 print(num1, '-', num2, '=', subtract(num1, num2))
 print(num1-num2)
#Multiplication
elif operation=='*':
 print(num1, '*', num2, '=', multiply(num1, num2))
 print(num1*num2)
#Division
elif operation=='/':
 print(num1, '/', num2, '=', div(num1, num2))
 print(num1/num2)

else:
  print('Invalid')
