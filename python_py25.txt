import random

lista=[]
for _ in range(10):
    szam=random.randint(0,50)
    if szam %4 ==0:
        lista.append(szam)


print(lista)
print(len(lista))