# Python--


import time as t
print("This is a calculator ")
a = int(input("Enter the 1 number :"))
b = int(input("Enter the 2 number: "))
c= int(input("Enter the coblier 1 =+ 2=- 3=* and 4=/:"))
if c==1:
    print(f"{a} + {b}")
    print("Answer :" ,a+b)
    
if c==2 :
    print(f"{a} - {b}")
    print("Answer :",a-b)
    
if c==3:
    print(f"{a} × {b}")
    print("Answer:",a*b)
    
if c==4 :
    print(f"{a} ÷ {b}")
    print("Answer :",a/b)
    
    
else:
    print("==> Enter the valid Santax <==")