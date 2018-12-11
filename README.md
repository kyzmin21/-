print("Види чесло")

b = int(input())
h = int(input())
a = int(input())

print("«Улитка»")

from math import ceil
print(ceil((h-a)/(a-b)+1) )
