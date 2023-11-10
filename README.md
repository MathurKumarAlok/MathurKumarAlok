n = int(input("enter a number :"))
x = 0
y = 1
if n==2 :
    print(x)
    print(y)
else :
    print(x)
    print(y)
    for i in range (n-2):
        next_fab = x+y
        print(next_fab)
        x=y
        y=next_fab
