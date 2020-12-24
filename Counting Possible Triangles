n = int(input())
arr = list(map(int,input().split()))
arr.sort()
res = 0
for k in range(2,n):
    i = 0
    j = k-1
    while i < j:
        if arr[i] + arr[j] > arr[k]:
            res += (j-i)
            j -= 1 
        else:
            i += 1
print(res % (10**9+7))
