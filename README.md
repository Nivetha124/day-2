# day-2
n=list(map(int,input().split()))
a=[]
for i in n:
    product = 1
    for j in n:
        if(i!=j):
            product = product*j
    a.append(product)
print(a)
        
        
        

