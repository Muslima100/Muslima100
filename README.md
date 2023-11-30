
import math

def salom(a,h):
    c=a/2
    b=math.sqrt(math.pow(c,2)+math.pow(h,2))
    p=a+b+h
    print("Uchburchak prematri:",p)
    
a=float(input("sonni kiriting"))
h=float(input("sonni kiriting"))
salom(a,h)
a1=float(input("sonni kiriting"))
h1=float(input("sonni kiriting"))
salom(a1,h1)
a2=float(input("sonni kiriting"))
h2=float(input("sonni kiriting"))
salom(a2,h2)
