a = 28
b = 36
k=a*b
while a!=b:
    if a>b:
        a=a-b
    else:
        b=b-a
print(b)
print("Ekub=",a)
print("Ekuk=",int(k/a))
