a = [4, 8, 0, -1, -5]
result=min(enumerate(a), key=sorted)
print("Position : {}, Value : {}".format(*result))


