n = int(input('Число монеток: '))
from random import randint
a=0
b=0
for i in range(n):
    t = randint(0, 1)
    print(t, end=" ")
    if t > 0: a += 1
    else: b += 1
print()
if a > b:
    print(b)
else:
    print(a)
