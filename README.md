# python-conditional-statements2
num=int(input("enter the number:"))
if num==0:
    print("Zero number")
elif num>0:
    print("Positive number")
else:
    print("Negative number")
output===
          enter the number: 57
          Positive number

'''Write a program to print days using if-els-if condition'''
num=int(input("enter the number:"))
if num==1:print("Sunday")
elif num==2:print("Monday")
elif num==3:print("Tuesday")
elif num==4:print("Wednesday")
elif num==5:print("Thursday")
elif num==6:print("Friday")
elif num==7:print("Saturday")
else:
    print("Wrong input")
output===
          enter the number: 5
           Thursday


'Write a program to find the entered character is a Vowel or a constant using,while user input could be either upper or lower case using if-elif-else'''
char=input("enter a alphabet")
if char=='a' or char=='e' or char=='i' or char=='o' or char=='u':
    print(char, "is a vowel")
elif char=='A' or char=='E' or char=='I' or char=='O' or char=='U':
    print(char, "is a vowel")
else:
    print(char, " is a consonent")
output===enter a alphabet E
E is a vowel

'''create a simple calc by using if-elif to perform arithmetic operations +-* by choice of users input'''
a=float(input("enter the value of a:"))
b=float(input("enter the value of b:"))
op=input("enter the operator(+, _, *, /):")
if op=='+':
    print("result:",a+b)
elif op=='-':
    print("result:",a-b)
elif op=='*':
    print("result:",a*b)
elif op=='/':
    print("result:",a/b)
else:
    print("invalid number")
output===Skip to Main
Untitled16
Last Checkpoint: 1 hour ago
Python 3 (ipykernel)
Trusted










Code

JupyterLab


Python 3 (ipykernel)


'Write a program to find the entered character is a Vowel or a constant using,while user input could be either upper or lower case using if-elif-else'''
char=input("enter a alphabet")
if char=='a' or char=='e' or char=='i' or char=='o' or char=='u':
    print(char, "is a vowel")
elif char=='A' or char=='E' or char=='I' or char=='O' or char=='U':
    print(char, "is a vowel")
else:
    print(char, " is a consonent")
enter a alphabet E
E is a vowel







'''create a simple calc by using if-elif to perform arithmetic operations +-* by choice of users input'''
a=float(input("enter the value of a:"))
b=float(input("enter the value of b:"))
op=input("enter the operator(+, _, *, /):")
if op=='+':
    print("result:",a+b)
elif op=='-':
    print("result:",a-b)
elif op=='*':
    print("result:",a*b)
elif op=='/':
    print("result:",a/b)
else:
    print("invalid number")
    output===Skip to Main
Untitled16
Last Checkpoint: 1 hour ago
Python 3 (ipykernel)
Trusted










Code

JupyterLab


Python 3 (ipykernel)


'Write a program to find the entered character is a Vowel or a constant using,while user input could be either upper or lower case using if-elif-else'''
char=input("enter a alphabet")
if char=='a' or char=='e' or char=='i' or char=='o' or char=='u':
    print(char, "is a vowel")
elif char=='A' or char=='E' or char=='I' or char=='O' or char=='U':
    print(char, "is a vowel")
else:
    print(char, " is a consonent")
enter a alphabet E
E is a vowel







'''create a simple calc by using if-elif to perform arithmetic operations +-* by choice of users input'''
a=float(input("enter the value of a:"))
b=float(input("enter the value of b:"))
op=input("enter the operator(+, _, *, /):")
if op=='+':
    print("result:",a+b)
elif op=='-':
    print("result:",a-b)
elif op=='*':
    print("result:",a*b)
elif op=='/':
    print("result:",a/b)
else:
    print("invalid number")



    #if-else statement for number determination of even or odd
num=int(input("enter the number :"))
if num%2==0:
    print(num, "is even")
else:
    print(num, "is odd")
    
    output===
               enter the number : 11
                  11 is odd
               enter the number : 22
                  22 is even

#if-elif else statement for number determination of even or odd
a=int(input("enter a :"))
b=int(input("enter b:"))
if a>b:
    print("Largest:",a)
elif a<b:
    print("Largest:",b)
else:
    print("Both numbers are equal")

    Output 1===
              enter a : 5
               enter b: 9
                Largest: 9
    Output 2===
             enter a : 5
             enter b: 5
           Both numbers are equal

 
 
#Nested if for checking the number is both poistive and even 
num=int(input("enter the number"))
if num>0:
    print("it is a positive number")
    if num%2==0:
        print("it is a even number")
    else:
        print("it is a odd  number")
else:
    print("it is a negative number")

Output 1==-
         enter the number 5
     it is a positive number
        it is a odd  number
Output 2===
        enter the number 8
     it is a positive number
        it is a even number
Output 3===
            enter the number -1
           it is a negative number


num=int(input("enter the number"))
while num>=1:
    print(num,end='')
    num-=1
OUTPUT===
enter the number 20
2019181716151413121110987654321


    
