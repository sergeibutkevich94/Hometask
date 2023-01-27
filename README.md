# Hometask
# lab:  с матбибл. рассчитайте объем шара и площадь круга


import math as ms

while True:
    print(f"Ecли нужен Vшара введите 1,если нужна Sкруга введите 2,если не хотите продолжать введите 3:")
    if int(input()) == 1:
        def v_shar(d):
            return print((4 / 3) * ms.pi * ((d / 2) ** 3))


        v_shar(int(input()))

    if int(input()) == 2:
        def s_kruga(r):
            return print(ms.pi * (r ** 2))


        s_kruga(int(input()))

    if int(input()) == 3:
        break
