n=int(input())
for i in range(n):
    a,b=input().split()
    l=[]
    l.append(int(b))
    for j in range(int(a)):
        s=input()
        if s[0]=='P':
            x,id1=s.split()
            l.append(int(id1))
        else:
            l.append(l[-2])
    print("Player "+str(l.pop()))
