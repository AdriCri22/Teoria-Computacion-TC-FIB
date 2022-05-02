# Exercise 7

## Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/07/Statement_7.png)

## Image solution:
![Solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/07/Image_sol_7.png)

## Text solution:
    Z 0 0 1
    0 -> Za|ZAA              -> 1
    0 -> Zb|ZB               -> 2
    1 -> Aa|AAA, Ab|, Za|ZAA -> 1
    1 -> Zb|ZB               -> 2
    2 -> Z |Z                -> 0
    2 -> Bb|BB               -> 2
    2 -> Ba|                 -> 4
    4 -> Z |ZA               -> 1
    4 -> B |                 -> 2
