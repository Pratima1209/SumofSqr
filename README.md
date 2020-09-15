# SumofSqr

#Python Program for Sum of squares of first n natural numbers

n=int(input("Enter the Number:"))

def sqr(n):
    total=0                                     # Value after expression execution of total = 0,1,5,14,30
    for i in range(1,n+1):                      # range value = 0,1,2,3,4
        total=total+(i*i)                       # sqr of = 0,1,4,9,16
    return total

print(sqr(n))
        
