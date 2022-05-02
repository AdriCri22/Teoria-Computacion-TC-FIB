# Exercise 19

## Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/19/Statement_19.png)

## Image solution:
![Solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/19/Image_sol_19.png)

## Text solution:
    Z 0 3
    0 -> Zb|Z        -> 0
    0 -> Za|ZA       -> 1
    0 -> Zc|Z        -> 2
    1 -> Aa|AA, Ab|A -> 1
    1 -> Ac|A        -> 2
    2 -> Ab|, Aa|A   -> 2
    2 -> Z |Z        -> 3
    3 -> Za|Z        -> 3
