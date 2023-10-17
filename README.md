# simplecalculator
# my first code in python 
# This code will take two numbers and an operator as input from the user, perform the corresponding mathematical operation based on the operator provided, #and print the result to the console.

num1=""
num2=""
oper=""
answer=""
num1=float(input("inset number 1:"))
num2=float(input("inset number 2:"))
oper=input("inset operator:")
if oper=="*" :
   answer= num1*num2
elif oper=="+" :
   answer= num1+num2
elif oper=="-" :
   answer= num1-num2
elif oper=="/" :
   answer= num1/num2
else: print("invalid operator")
print(answer)
