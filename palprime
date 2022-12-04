print("Hello Guys this is a program to find Nth prime palindrome numbers........")
print("Basically prime numbers are those numbers which have only 2 factors 1 and itself.Eg. 2,3,5,7....")
print("Palindrome numbers are those numbers whose reverse is equal to the original number. Eg. 121,131,1234321.....")
print("So let's start........")
x=int(input("Enter nth no to which palindrome and prime is to be found : "))
n,c=1,0
while(c<x):
    n+=1
    for i in range(2,n+1):
        if(n%i==0):
            break
    if(i==n):
        s=str(n)
        if (s==s[::-1]):
            c=c+1
print(n)
