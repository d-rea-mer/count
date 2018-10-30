#python program to count number of digits of a given number
n=int(input("enter number")
count=0
while(n>0):
 dig=n%10       #to take the last digit of the number 
 count=count+1
 n=n//10        #to take the next last digit of the number 
print(count)
