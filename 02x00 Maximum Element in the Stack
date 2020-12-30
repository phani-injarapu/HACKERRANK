items = [0]
for i in range(int(input())):
    nums = list(map(int, input().split()))
    if nums[0] == 1:
        items.append(max(nums[1], items[-1]))
    elif nums[0] == 2:
        items.pop()
    else:
        print(items[-1])
