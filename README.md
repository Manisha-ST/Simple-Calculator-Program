# Simple-Calculator-Program

a=int(input("Enter 1st number:"))
b=int(input("Enter 2nd number:"))
c=input("Enter the operation +,-,/,*:")
print("the Result is:",end='')
if c=='+':
    print(a+b)
elif c=='-':
    print(a-b)
elif c=='/':
    print(a/b)
elif c=='*':
    print(a*b)
else:
    print("eoor : wrog operator entered")

Output:
Enter 1st number:21
Enter 2nd number:41
Enter the operation +,-,/,*:*
the Result is:861


