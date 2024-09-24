# Number-series.py

s = int(input("enter starting point:"))
e = int(input("enter ending point:"))
u = int(input("enter updationo choice:"))

print("choice 'H' for horizontal")
print("choice 'v' for vertical")
n = int(input("enter ur choice:"))
if n=="H":
    print("choice "F" for forward order")
    print("choice "R" for reverse order")
    m = int(input("enter ur choice:"))
    if m == "F": 
       for i in range(s,e+1,u):
           print(i,end='')
    elif m == "R":
        for i in range(e,s-1,-u):
            print(i,end=' ')
    elif n == "v":
         print("choice "F" for forward order")
         print("choice "R" for reverse order")
    else:
         print("invalid choice")
    m = input("enter ur choice:")
    if m == "F":
       for i in range(s,e+1,u):
           print(i)
    elif m == "R":
        for i in range(e,s-1,-u): 
            print(i)
        else:
            print("invalid choice")
