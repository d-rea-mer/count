#python program to count number of digits of a given number
n=int(input("enter")
count=0
while(n>0):
 dig=n%10
 count=count+1
 n=n//10
print(count)
