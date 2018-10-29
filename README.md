
1	string manipulation write a python program to find a factorial of a given no.
num=int(input("enter a given number:"))
factorial=1
if num<0:
    print("factorial does not exist for negative numbers")
elif num==0:
    print("factorial of 0 is 1")
else:
    for i in range(1,num+1):
        factorial=factorial*i
        print("the factorial of",num,"is",factorial)
        
OUTPUT:
enter a given number:7
the factorial of 7 is 1
the factorial of 7 is 2
the factorial of 7 is 6
the factorial of 7 is 24
the factorial of 7 is 120
the factorial of 7 is 720
the factorial of 7 is 5040
