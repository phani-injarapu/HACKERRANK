n, a = int(input()), input().split()
a = [int(j) for j in a]

i = 1
f=0
for i in range(i, n):
    if not (a[i - 1] < a[i]):
        break
else:
    print("yes")
    f+=1

if f!=1:
    for i in range(i,n):
        if not (a[i-1] == a[i]):
            break
    else:
        print("yes")
        f+=1
if f!=1:
    for i in range(i,n):
        if not (a[i - 1] > a[i]):
            print("no")
            break
    else:
        print("yes")
