print("Види чесло")

b = int(input())
h = int(input())
a = int(input())

print("«Улитка»")

from math import ceil
print(ceil((h-a)/(a-b)+1) )


from random import*
playing = True
while playing == True:
    print("Привет как тебя зовут?")
    имя = input(">>>")
    print("види имя друга")
    друг = input(">>>")
    print("хатите узнать правила игры да/нет")
    answer = input(">>>").lower()
    if answer == "да":
        print('''Щяс вы должны вибрать з другам свой рису например:альянс,гоблини,пацики з райна.
а патом ви появтесь на поле и ваи далжна унежтжать друг друга''')
    if answer == "нет":
        print("")
        print("игрок",имя,"виберите свой рису альянс,гоблини,пацики з райна")
        any9 = input(">>>").lower()      
        print(имя,"ви теперь",any9,)


        print("игрок",друг,"виберите свой рису альянс,гоблини,пацики з райна")
        ans7 = input(">>>").lower()
        print(имя,"ви теперь",ans7,)
from random import*
speed(1)
shape("turtle")
for count in range(4):
    forward(100)
    left(90)
done()
