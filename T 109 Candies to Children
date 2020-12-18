n = int(input())
l = list(map(int,input().split()))
a=[]
for i in range(n):
    a.append(1)
for i in range(1, n):
    if(l[i]>l[i-1]):
        a[i]=a[i-1]+1
for i in range(n-2,-1,-1):
    if(l[i]>l[i+1]):
        a[i]=max(a[i+1]+1,a[i])         
print(sum(a))
