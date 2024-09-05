# calculator-python
# Online Python - IDE, Editor, Compiler, Interpreter

def sum (a, b): 
    return (a + b) 

    
a= int(input('Enter 1st number:  '))
b= int(input('Enter 2nd number: '))

print(f'Sum of {a} and {b} is {sum(a, b )}') 

def add (x, y): 
    return x + y
    
def subtract (x, y):
    return x - y
    
def multiply (x, y): 
    return x * y
    
def divide (x, y): 
    if y !=0: 
        return x / y
    else: 
        return "Error! division by zero."
        
print("Select operation:")
print("1. Add")
print("2. Subtract")
print("3. Multiply")
print("4. Divide")

choice = input("enter choice (1/2/3/4):")

num1= float(input("enter first number:"))
num2= float(input("enter second number:"))

if choice == "1": 
    print(f"{num1} + {num2} = {add(num1, num2 )}")
elif choice== '2':
    print(f"{num1} - {num2} = {subtract(num1, num2 )}")
elif choice== '3':
     print(f"{num1} * {num2} = {multiply(num1, num2 )}")
elif choice== '4':
     print(f"{num1} / {num2} = {divide(num1, num2 )}")
else: 
    ("Invalid input")
