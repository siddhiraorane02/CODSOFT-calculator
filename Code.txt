def add(a, b):
    return a+b
def sub(a, b):
    return a-b
def mul(a, b):
    return a*b
def div(a, b):
    return a/b
print('|+ -|')
print('|* /|')
O=input("Enter Operator: \n")
A =float(input("Enter First Operand: \n"))
B =float(input("Enter Second Operand: \n"))

match O :
    case '+':
        print("Result is: ",add(A,B))
    case '-':
        print("Result is: ",sub(A,B))
    case '*':
        print("Result is: ",mul(A,B))
    case '/':
        print("Result is: ",div(A,B))
    case _:
        print("Operator is incorrect")
    


