# Exercise 16

## Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/16/Statement_16.png)

## Image solution:
![Solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/16/Image_sol_16.png)

## Text solution:
    Z 0 0 3
    0 -> Za|ZA, Zb|ZB               -> 1
    1 -> Aa|AA, Bb|BB, Ab|AB, Ba|BA -> 1
    1 -> Aa|, Bb|, A |, B |         -> 2
    2 -> Aa|, Bb|                   -> 2
    2 -> Z |Z                       -> 3
