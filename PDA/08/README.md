# Exercise 8

## Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/08/Statement_8.png)

## Image solution:
![Solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/08/Image_sol_8.png)

## Text solution:
    Z 0 0 2
    0 -> Za|ZAA       -> 1
    0 -> Zb|ZB        -> 2
    1 -> Z |Z         -> 0
    1 -> Aa|AAA, Ab|  -> 1
    2 -> Za|ZAA       -> 1
    2 -> Bb|BB, Zb|ZB -> 2
    2 -> Ba|          -> 4
    4 -> Z |ZA        -> 1
    4 -> B |          -> 2
