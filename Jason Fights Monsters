n,hit,t=map(int,input().split())
l = sorted([int(i) for i in input().split()[0:n]])
res,h=0,0
for i in l:
    h = i // hit+(1 if i%hit else 0)
    if t >= h:
        t -= h
        res += 1
    else: break
print(res)
