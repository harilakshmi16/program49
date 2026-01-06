num=int(input("enter an integer:"))
isprime=1
for i in range(2,num//2):
if(num%i==0):
isprime=0
break
if(isprime==1):
print(num,"is a prime number")
else:
print(num,"is not a prime number")
Output:
enter an integer:6
6 is not a prime number
