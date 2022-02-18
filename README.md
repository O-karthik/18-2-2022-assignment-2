# 18-2-2022-assignment-2
n=int(input("enter number:"))
s=0
f=1
for i in range(1,n+1):
    f=f*i
    s=s+f
print("sum of factorial:",s)
