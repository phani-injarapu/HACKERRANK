items = []
for i in range(int(input())):
    a=input()
    if a[0:3] == 'Add':
        x,b=a.split()
        b = int(b)
        items.append(b)
    elif a[0:6] == 'Remove':
        if(len(items) == 0):
            print('Invalid')
        else:
            items.pop()
    elif a[0:7] == 'CallMin':
        if(len(items) == 0):
            print('Invalid')
        else:
            print(min(items))
    elif a[0:7] == 'CallMax':
        if(len(items) == 0):
            print('Invalid')
        else:
            print(max(items))
