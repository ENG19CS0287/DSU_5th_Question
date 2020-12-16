# DSU_5th_Question
Please submit your answer here.
#Write a Python Program to check whether a number is palindrome or 

n=int(input("Enter number:"))
temp=n
rev=0
while(n>0):
    dig=n%10
    rev=rev*10+dig
    n=n//10 
if(temp==rev): 
    print("The number is a palindrome!") 
else: 
    print("The number isn't a palindrome!")
