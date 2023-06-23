nums = (42, 13243)
step = min(nums)
list5 = range(min(nums), max(nums) + step, step)

for i in list5:
    li = list(list5)
    print(li)
    break
