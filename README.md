# Function to calculate factorial using a for loop
num=int(input("Enter a number :"))
fact = 1
n=1
while n<=num :
    fact=fact*n
    n=n+1
    print("The factorial of " ,num, "is" , fact)
