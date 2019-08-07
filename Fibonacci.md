# Jaiprakash4024
Fibonacci Series using python
lst=[]
lst.append(0)
lst.append(1)
n=int(input("Enter a number :"))
for i in range(2,n):
    sum1=lst[i-1]+lst[i-2]
    lst.append(sum1)
print(lst[n-1])

